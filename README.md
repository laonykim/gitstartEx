# gitstartEx

# 첫번째 제목
안녕하세요.
김채원입니다.
---
***
## 두번째 제목
1. 안녕하세요.

2. 김채원입니다.

3. 반가워요.
***
### 세번째 제목
- 안녕하세요
- 김채원입니다
* 반가워요
#### 네번째 제목
+ 안녕하세요
+ 김채원입니다
  + 반가워요
    + 잘 부탁해요!
        + 화이팅
##### 다섯번째 제목
**안녕하세요**하세요

_김채원_입니다.

___김채원___입니다.

***김채원***입니다.

~~반가워요.~~
 
####### 여섯번째 제목

***
1. 한 줄 소스 코드
 `var arr = new Array();`
       arr[0] = "홍길동";
       arr[5] = 12345;
       arr[10] = "서울시 강남구";
       arr[15] = "aaa@naver.com";
      // document.write("arr[0] :" , arr[0]); 
      // 배열명.length : 배열의 갯수 구하기
      
2. 여러줄 소스코드      
      ```
      for(var idx=0;idx<arr.length; idx++){
         document.write("</br>arr["+idx+"] : " + arr[idx]);
      }
      
      //초기값이 있는 배열선언
      var arr2 = new Array("HTML","CSS","JAVASCRIPT");
      var arr3 = ["Spring","mybatis"];

      //배열에 데이터 추가
      arr2.push("JSP");
      document.write("</br> arr2 : " + arr2);
      console.log(arr2);
      //배열의 값을 특정문자 만들기
      var arrStr = arr2.join('/');
      document.write("</br>arrStr : " + arrStr);

      // 배열의 마지막 값 제거하기
      arr2.pop();
      document.write("</br>arr1.pop() : " + arr2);
      
      // 배열과 배열 합치기
      var arr4 = arr2.concat(arr3);  //arr3.concat(arr2)
      document.write("</br>arr4 : " , arr4);
