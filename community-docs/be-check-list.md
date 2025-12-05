# 진행 상황 체크 리스트
## API 개발

---

(251205)가장 최신 API 개요는 BE 레포지토리에서 관리 됩니다. 해당 파일은 최신 파일이 아닙니다.

- [ ] GET /images/pre-signed-url Pre-signed URL 조회

- [ ] POST /auth 로그인
- [ ] DELETE /auth 로그아웃

- [ ] POST /users 회원가입
- [ ] PUT /users/:userId 회원정보 수정
- [ ] DELETE /users/:userId

- [ ] POST /posts
- [ ] GET /posts 게시글 목록 조회
- [ ] GET /posts/:postId 게시글 상세 조회
- [ ] DELETE /posts/:postId 게시글 삭제
- [ ] PUT /posts/:postId

- [ ] POST? PUT? /likes 좋아요 생성 또는 삭제

- [ ] GET /comments 댓글 조회
- [ ] POST /comments/:commentId 댓글 생성
- [ ] PUT /comments/:commentId 댓글 수정
- [ ] DELETE /comments/:commentId 댓글 삭제

## 인가

---

- [ ] 세션, 쿠키
- [ ] JWT