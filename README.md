# pmjn1025-BookFlix_alpha

b반 9조 북플릭스입니다. <br>
S.A 상세 설명 : https://danwoo2.tistory.com/entry/Chapter-1-9%EC%A1%B0-SA-Starting-Assignment

![image](https://user-images.githubusercontent.com/76934018/178942458-5c592cbd-a5b9-4072-b1e7-c3425bb75dae.png)

1.  프로젝트명
 : 북플릭스 (BOOKFLIX) 

2. 소개
- 자신이 읽은 책들에 대해 간단한 리뷰를 등록할 수 있는 페이지입니다. 

3. 와이어프레임

1)홈 화면
![image](https://user-images.githubusercontent.com/76934018/178941364-8e71d5ba-a8e1-4b17-b52d-e5f9765657d0.png)

2)로그인 페이지
![image](https://user-images.githubusercontent.com/76934018/178941399-59b10c07-1cd8-479e-8437-7f760056707a.png)

3)회원가입 페이지
![image](https://user-images.githubusercontent.com/76934018/178941444-f4d345a5-cb24-4cb2-adf8-06019785e05d.png)

4)메인 페이지
![image](https://user-images.githubusercontent.com/76934018/178941506-49c38c57-02f4-43e3-945e-3b309d04e713.png)

5)프로필 페이지
![image](https://user-images.githubusercontent.com/76934018/178941589-896c88fc-169d-464b-887c-23dfad5a1365.png)

4. 개발 기능 계획 및 기술 매니저님께 피드백 받은 내용

1) 수정 시작
![피드백 내용](https://user-images.githubusercontent.com/76934018/178860343-c7f1acc8-7af8-4344-a48b-35c8c51be9a2.png)

가장 초기부터 

1. 기능들마다 URL이 중복되는 문제

- 기능들끼리 api가 동일하면 충돌하게 된다.
 

2. 팀원들과의 api 동일하게 맞추기

- 서로 api를 다르게 작성해게 되면  에러발생
 

3. CRUD에 집중하자.

-  기본적인 데이터 처리 기능에 집중하자

-  Create(생성) / Read(읽기) / Update(갱신) / Delete(삭제)


2) 최종 수정
![최종 수정](https://user-images.githubusercontent.com/76934018/178860696-d002eaec-a225-4342-8cf0-eda9aff8b57a.png)


1. 로그인 페이지

2. 회원가입 페이지

3. 메인페이지

4. 프로필페이지

7번에 있던 회원탈퇴를 삭제한 이유.

회원탈퇴는 로그인한 사람한테만 보이게끔 하려고 계획했었다.

하지만 팀원들과의 회의 끝에 회원탈퇴는 하나의 페이지로 보기 어렵고,

부수적인 기능이라고 판단해서 회원탈퇴를 맡았던 팀원이 프로필 페이지 구현하는 것으로 계획 변경.
