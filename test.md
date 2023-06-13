| Project                                                      | Date        |
| ------------------------------------------------------------ | ----------- |
| [VULNWEB] - Web Application Penetration Testing 1st Test Brief Report Rev.1 | 10 Oct 2022 |



## Assessment Scope

|  ID  | Target         | Detail |
| :--: | -------------- | ------ |
|  1.  | IP or URL (IP) |        |
|  2.  | IP or URL (IP) | XXXX   |



## Vulnerability Summary

### 1. IP or URL(IP)

|  ID  | Vulnerability      |              Severity               |
| :--: | ------------------ | :---------------------------------: |
| 1.1  | Vulnerability Name | <font color=Red>**Critical**</font> |
| 1.2  | Vulnerability Name | <font color=Orange>**High**</font>  |
| 1.3  | Vulnerability Name | <font color=Gold>**Medium**</font>  |
| 1.4  | Vulnerability Name |   <font color=gree>**Low**</font>   |

### 2. http://testaspnet.vulnweb.com/ (44.238.29.244)

|  ID  | Vulnerability |              Severity              |
| :--: | ------------- | :--------------------------------: |
| 2.1  | SQL Injection | <font color=Orange>**High**</font> |
| 2.2  | Stored XSS    | <font color=Orange>**High**</font> |
| 2.3  |               |                                    |
|      |               |                                    |



<P style="page-break-before: always"/>


## 1. IP or URL(IP)


###  1.1 Vulnerability Name

| ID   | URL / Location                  | Parameter or Port | Severity                            |
| :--: | ----------------------------------- | --------------------------- | :----------------------------------------------------: |
|1.1.1  | PATH or Full URL or IP	| -                                  | <font color=Red>**Critical**</font> |
|1.1.2|PATH or Full URL or IP | -         | <font color=Red>**Critical**</font> |



#### Vulnerability Details

*Short details to clarify what this application is vulnerable or/and missing, what the impact or what attacker can do*

During testing, the penetration tester noticed that ... `[< Why/What's the application is missing/vulnerable >]`. `[< What's an attacker can do >] `.`[< What's the impact >]`

(Optional) For more information, please refer to: 

- Link-1
- Link-2

#### Exploitation Details

##### 1.3.1  http://testphp.vulnweb.com/guestbook.php

- Navigate to URL : http://testphp.vulnweb.com/guestbook.php
- In the message box enter XSS Payload and add message

###### HTTP Request

```http
POST /guestbook.php HTTP/1.1
Host: testphp.vulnweb.com
Content-Length: 83
Cache-Control: max-age=0
Upgrade-Insecure-Requests: 1
Origin: http://testphp.vulnweb.com
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/108.0.5359.125 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Referer: http://testphp.vulnweb.com/guestbook.php
Accept-Encoding: gzip, deflate
Accept-Language: en-US,en;q=0.9
Connection: close

name=anonymous+user&text=%3Cscript%3Ealert%281%29%3C%2Fscript%3E&submit=add+message

```

###### Result

![Screenshot 2023-01-04 at 14.26.14](Template - Brief Report (1st test) Rev.3.assets/Screenshot 2023-01-04 at 14.26.14.png)

<P style="page-break-before: always"/>


##### 1.1.2 PATH or Full URL or IP

- Step-1
- Step-2

###### HTTP Request

```http
GET / HTTP/1.1
Host: test.template

```

- Step-3

###### HTTP Response

```http

```



###### Result

*\<Screenshot\>*



#### Solution(s)

1. X-1

2. X-2

   For more information, please refer to:

   - Link-1
   - Link-2

<P style="page-break-before: always"/>


### 1.2 Vulnerability Name


|  ID   | URL / Location         | Parameter or Port |              Severity               |
| :---: | ---------------------- | ----------------- | :---------------------------------: |
| 1.2.1 | PATH or Full URL or IP | -                 | <font color=Red>**Critical**</font> |
| 1.2.2 | PATH or Full URL or IP | -                 | <font color=Red>**Critical**</font> |



#### Vulnerability Details

#### Exploitation Details

##### 1.2.1 PATH or Full URL or IP

- Step-1

  *\<Screenshot\>*

- Step-2

  *\<Screenshot\>*

###### HTTP Request

```http
GET / HTTP/1.1
Host: test.template

```

- Step-3

###### HTTP Response

```http

```



###### Result

*\<Screenshot\>*

<P style="page-break-before: always"/>

##### 2.2 PATH or Full URL or IP


- Step-1

  *\<Screenshot\>*

- Step-2

  *\<Screenshot\>*

###### HTTP Request

```http
GET / HTTP/1.1
Host: test.template

```

- Step-3

###### HTTP Response

```http

```



```python
import m3ez

pri
```



###### Result

*\<Screenshot\>*



#### Solution(s)

1. X-1

2. X-2

   For more information, please refer to:

   - Link-1
   - Link-2

<P style="page-break-before: always"/>
