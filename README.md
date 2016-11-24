# Regex
#### [Date](https://regex101.com/r/lQ0lL8/40) in format dd/mm/yyyy 
```java
/^([1-9]|0[1-9]|[12][0-9]|3[01])\D([1-9]|0[1-9]|1[012])\D(19[0-9][0-9]|20[0-9][0-9])$/
```
#### [HTML](https://regex101.com/r/lQ0lL8/42) tags
```java
/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/
```
#### Username 3-16 chars, alphanum, hypehns and underscores
```java
/^[a-z0-9_-]{3,16}$/
```
#### Password 8-64 chars, alphanum, hypehns and underscores
```java
/^[a-z0-9_-]{8,64}$/
```
#### Hex Value
```java
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
```
#### URL Slug
```java
/^[a-z0-9-]+$/,
```
#### Email
```java
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```
#### URL
```java
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
```
#### IPv4 Address
```java
/^(?:(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.){3}(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)$/
```
#### Positive non zero integer
```java
/^\d+$/
```
#### Negative integer
```java
/^-\d+$/
```
#### Integer
```java
/^-?\d+$/
```
#### Positive integer or float
```java
/^\d*\.?\d+$/
```
#### Negative integer or float
```java
/^-\d*\.?\d+$/
```
#### Positive or negative integer or floats
```java
/^-?\d*\.?\d+$/,
```
#### Phone number with min 3 digits
```java
/^\+?[\d\s]{3,}$/
```
#### Matches new line
```java
/[\r\n]|$/
```
### License
[MIT License](http://dsf.com)
