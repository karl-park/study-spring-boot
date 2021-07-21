# study-spring-boot
Studying Spring Boot

Reference: 
1. https://start.spring.io/
2. https://docs.spring.io/spring-boot/docs/2.1.18.RELEASE/reference/html/index.html
3. https://docs.spring.io/spring-boot/docs/current/reference/html/features.html#features.kotlin

# Day1

## 맛보기
Install & Hello World

```groovy
// app.groovy
@RestController
class ThisWillActuallyRun {

	@RequestMapping("/")
	String home() {
		"Hello World!"
	}

}
```

and run it
```
$ spring run ./app.groovy

# goto http://localhost:8080/ then you can see the page printing "Hello World"
```



## Kotlin Supports
- https://docs.spring.io/spring-boot/docs/current/reference/html/features.html#features.kotlin
- https://spring.io/guides/tutorials/spring-boot-kotlin/ << demn good!

## Initializr
![image](https://user-images.githubusercontent.com/7299877/126358581-334df3a6-4cec-4742-ade8-47957c0bc188.png)



