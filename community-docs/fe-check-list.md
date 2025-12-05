# 진행 상황 체크 리스트

## HTML, CSS, js 이벤트 핸들링

---

- [ ] 로그인
- [ ] 회원가입
- [ ] 회원정보 수정
- [ ] 회원 비번번호 수정
- [ ] 게시글 목록
- [ ] 게시글 상세
- [ ] 게시글 추가
- [ ] 게시글 수정
- [ ] Header
- [ ] Footer(약관)

## 약관 페이지 개발

---

- [ ] 커뮤니티 이용약관
- [ ] 개인정보처리방침

## API(js) 연결

---

**로그인 페이지**
- [ ] POST /auth 로그인
- [ ] DELETE /auth 로그아웃

**회원가입 페이지**
- [ ] GET /images/pre-signed-url Pre-signed URL 조회
- [ ] POST /users 회원가입

**회원정보-일반정보 수정 페이지**
- [ ] GET /images/pre-signed-url Pre-signed URL 조회
- [ ] PUT /users/:userId 회원정보 수정
- [ ] DELETE /users/:userId 회원 탈퇴

**회원정보-비밃번호 수정 페이지**
- [ ] PUT /users/:userId 회원정보 수정

**게시글 목록 페이지**
- [ ] GET /posts 게시글 목록 조회

**게시글 상세 페이지**
- [ ] GET /posts/:postId 게시글 상세 조회
- [ ] DELETE /posts/:postId 게시글 삭제
- [ ] POST? PUT? /likes 좋아요 생성 또는 삭제
- [ ] GET /comments 댓글 조회
- [ ] POST /comments/:commentId 댓글 생성
- [ ] PUT /comments/:commentId 댓글 수정
- [ ] DELETE /comments/:commentId 댓글 삭제

**게시글 추가 페이지**
- [ ] GET /images/pre-signed-url Pre-signed URL 조회
- [ ] POST /posts

**게시글 수정 페이지**
- [ ] GET /images/pre-signed-url Pre-signed URL 조회
- [ ] PUT /posts/:postId

**Header**
<!-- 로그인 또는 회원가입 응답으로 주는 데이터로 헤더 데이터 넣기 가능 -->

**Footer**
<!-- 호출 형식 정해지면 작성 예정-->

## QA(Quality Assurance)

---

- [ ] 로그인
- [ ] 회원가입
- [ ] 회원정보 수정
- [ ] 회원 비번번호 수정
- [ ] 게시글 목록
- [ ] 게시글 상세
- [ ] 게시글 추가
- [ ] 게시글 수정
- [ ] Header
- [ ] Footer(약관)