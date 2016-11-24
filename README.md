# Regex
#### Boolean
```java
/^(?i)(true|false)$/
```
https://regex101.com/r/lQ0lL8/63
#### Date in format dd/mm/yyyy
```java
/^([1-9]|0[1-9]|[12][0-9]|3[01])\D([1-9]|0[1-9]|1[012])\D(19[0-9][0-9]|20[0-9][0-9])$/
```
https://regex101.com/r/lQ0lL8/46
#### Date in format yyyy-MM-dd
```java
/^(19|20)\d\d([- /.])(0[1-9]|1[012])\2(0[1-9]|[12][0-9]|3[01])$/
```
https://regex101.com/r/lQ0lL8/60
#### HTML tags
```java
/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/
```
https://regex101.com/r/lQ0lL8/58
#### Username 3-16 chars, alphanum, hypehns and underscores
```java
/^[a-z0-9_-]{3,16}$/
```
https://regex101.com/r/lQ0lL8/42
#### Password 8-64 chars, alphanum, hypehns and underscores
```java
/^[a-z0-9_-]{8,64}$/
```
https://regex101.com/r/lQ0lL8/43
#### Hex Value
```java
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
```
https://regex101.com/r/lQ0lL8/44
#### ISBN
```java
/^ISBN:(\d{12}(?:\d|X))$/
```
https://regex101.com/r/lQ0lL8/65
#### URL Slug
```java
/^[a-z0-9-]+$/
```
https://regex101.com/r/lQ0lL8/57
#### Email
```java
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```
https://regex101.com/r/lQ0lL8/45
#### URL
```java
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
```
https://regex101.com/r/lQ0lL8/48
#### IPv4 Address
```java
/^(?:(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.){3}(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)$/
```
https://regex101.com/r/lQ0lL8/47
#### Mac Address
```java
/^([0-9a-fA-F][0-9a-fA-F]:){5}([0-9a-fA-F][0-9a-fA-F])$/
```
https://regex101.com/r/lQ0lL8/59
#### Base64
```java
/^(?:[A-Za-z0-9+\/]{4})*(?:[A-Za-z0-9+\/]{2}==|[A-Za-z0-9+\/]{3}=)$/
```
https://regex101.com/r/lQ0lL8/61
#### Positive non zero integer
```java
/^\d+$/
```
https://regex101.com/r/lQ0lL8/52
#### Negative integer
```java
/^-\d+$/
```
https://regex101.com/r/lQ0lL8/53
#### Integer
```java
/^-?\d+$/
```
https://regex101.com/r/lQ0lL8/54
#### Positive integer or float
```java
/^\d*\.?\d+$/
```
https://regex101.com/r/lQ0lL8/55
#### Negative integer or float
```java
/^-\d*\.?\d+$/
```
https://regex101.com/r/lQ0lL8/56
#### Positive or negative integer or floats
```java
/^-?\d*\.?\d+$/
```
https://regex101.com/r/lQ0lL8/51
#### Phone number with min 3 digits
```java
/^\+?[\d\s]{3,}$/
```
https://regex101.com/r/lQ0lL8/50
#### Matches new line
```java
/[\r\n]|$/
```
https://regex101.com/r/lQ0lL8/49
#### Credit Card Number
```java
/^(?:4[0-9]{12}(?:[0-9]{3})?|5[1-5][0-9]{14}|(222[1-9]|22[3-9][0-9]|2[3-6][0-9]{2}|27[01][0-9]|2720)[0-9]{12}|6(?:011|5[0-9][0-9])[0-9]{12}|3[47][0-9]{13}|3(?:0[0-5]|[68][0-9])[0-9]{11}|(?:2131|1800|35\d{3})\d{11})|62[0-9]{14}$/
```
https://regex101.com/r/lQ0lL8/62
### License
[MIT License](http://dsf.com)
