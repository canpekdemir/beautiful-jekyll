---
layout: post
title: Constructing a mail Rest API
subtitle: Spring Boot and ActiveMQ
tags: [java, rest,spring,activemq,java8,mail,messaging queue,rest api,spring,spring boot,spring4]
---
This is a sample mail rest api project which uses spring boot and activemq. 

You can change mail smtp configurations from application.yml file.

You can find the project as a whole in [here](https://github.com/canpekdemir/springboot-mail-activemq)

**Sample Usage**

You can post the sample json request to the url: [http://localhost:8080/mail](http://localhost:8080/mail)

```javascript
{
     "sender": "canpekdemir@yandex.com",
      "replyTo": "canpekdemir1912@gmail.com",
      "toList": ["canpekdmr@gmail.com", "can.pekdemir@iyzico.com", "canpekdemir@yandex.com"],
      "subject": "spring boot rest api with activemq",
      "body": "<html><head><title>Page Title</title></head><body><h1>This is a Heading</h1><p>This is a paragraph.</p></body></html>"
}        
```
