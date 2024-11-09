JSTL(JSP Standard Tag Library) 
------------------------------
이름 그대로다. JSP에서 사용할 수 있는 태그들을 표준화해서 모아놓은 라이브러리라 생각하면 된다.

![image](https://github.com/user-attachments/assets/c2c94b7b-2dba-4718-8fb2-89a68101331f)

#### 태그 라이브러리에는 위와 같은 5가지가 있는데 MVC 패턴에서는 Core, Formatting, Functions 3가지 범주의 라이브러리만 사용한다.

![image](https://github.com/user-attachments/assets/ba0594bc-7706-4f8f-a6a4-1cb0be15447e)

#### JSTL Core는 위와 같은 태그들이 있다. 태그 라이브러리에 왜 접두사 c를 붙일까?

![image](https://github.com/user-attachments/assets/76363a6b-0b95-44a9-b1d5-5cba1b9862c7)

#### 접두사를 사용하지 않으면 Jasper가 "이거 뭐야? 출력태그인가? 뭐지?" 하며 구분을 못하는 문제가 발생할 수 있다.
#### 접두사를 붙이면 해당 태그가 JSTL의 태그임을 Japser에게 알려줄 수 있게 되는 것이다.

![image](https://github.com/user-attachments/assets/2e7600eb-d575-45ce-b52a-c5698f10818b)

#### 태그를 직접 만들 수도 있는데, 이건 그냥 그런 게 있구나 하고 넘어가자.
#### 참고로, uri란 식별자의 기능을 하기 때문에 중복되는 이름을 사용하면 안된다.
#### 그래서 보통은 위처럼 도메인을 가져다 쓰는 경우가 많다.

![image](https://github.com/user-attachments/assets/a7b9a357-e817-48ec-84c0-19546ba42773)

#### 식별자인 uri가 너무 길기 때문에 별명인 prefix 접두사를 사용한다고 생각하면 된다.


