# 코멘토 직무부트캠프
IT 대기업 현업 개발자와 함께 하는 백엔드 개발 실무 (2021. 10. 26 ~ 2021. 11. 23)

## Week-01 
### (Spring 개발환경 설정)

**환경 구축을 하면서 난 오류 종류**
1. web.xml <web-app> 태그 오류
2. root-context.xml <context:component-scan> 태그 오류
3. log4j.xml "log4j.dtd" 파일을 찾을 수 없는 오류
  
**오류 해결방안**   
1. <web-app> 태그의 xsi:schemaLocation의 주소 부분에 'java' 단어를 'JAVA'로 변경
2. <beans> 태그에 xmlns:context="http://www.springframework.org/schema/context" 추가 후, root-context.xml namespaces에서 context default version 설정
3. <!DOCTYPE> 부분의 "log4j.dtd" 부분을 "http://logging.apache.org/log4j/1.2/apidocs/org/apache/log4j/xml/doc-files/log4j.dtd"로 변경 후, 변경한 주소에서 'log4j.dtd' 파일을 다운 후, log4j.xml과 같은 위치에 복붙

**실행결과**  
  
![1주차 과제 실행결과](https://user-images.githubusercontent.com/77434165/139442240-eda63ebb-3846-4a76-ace4-bd5ca501d369.png)
  
## Week-02

1. HTTP 통신에 대하여
2. 클라이언트와 서버 간 요청과 응답 과정
3. API 문서 작성 방법

## Week-03
### (Spring Boot 개발환경 설정)
**실행결과**
  
![image1](https://user-images.githubusercontent.com/77434165/140966599-3fdc4ec1-b882-4ae6-a897-f87c2596ff43.png)
![image2](https://user-images.githubusercontent.com/77434165/140968545-12064d76-b08c-4229-8933-f4e1e0763c05.png)

## Week-04

