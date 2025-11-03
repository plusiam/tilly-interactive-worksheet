# 🚀 배포 가이드

## 자동 배포 (GitHub Pages)

이 프로젝트는 GitHub Actions를 통해 **자동으로 배포**됩니다.

### 🎯 작동 방식

1. `main` 브랜치에 `push`하면
2. GitHub Actions가 자동으로 빌드 → 배포
3. GitHub Pages에서 라이브 서빙

### 📱 라이브 URL

```
https://plusiam.github.io/tilly-interactive-worksheet/
```

---

## 🔧 로컬 개발 (개발자용)

### 1️⃣ 설치

```bash
# 저장소 클론
git clone https://github.com/plusiam/tilly-interactive-worksheet.git
cd tilly-interactive-worksheet

# 의존성 설치
npm install
```

### 2️⃣ 개발 서버 실행

```bash
npm run dev
```

- 자동으로 `http://localhost:3000` 열림
- 파일 수정 시 실시간 반영 (Hot Module Reload)

### 3️⃣ 프로덕션 빌드

```bash
npm run build
```

- `dist/` 폴더에 최적화된 파일 생성
- 번들 크기: ~50KB (gzip)
- 콘솔 로그 제거, 코드 압축

### 4️⃣ 미리보기

```bash
npm run preview
```

- 빌드된 파일을 로컬에서 테스트

---

## 📝 배포 워크플로우

```
코드 수정
   ↓
git add .
git commit -m "메시지"
git push origin main
   ↓
GitHub Actions 자동 실행
   ↓
npm run build
   ↓
GitHub Pages 배포
   ↓
✅ https://plusiam.github.io/tilly-interactive-worksheet/ 에서 확인
```

---

## 🔐 GitHub Pages 설정 확인

1. GitHub 저장소 → **Settings**
2. **Pages** 섹션 확인
3. **Build and deployment** 에서 `GitHub Actions` 선택됨

---

## ✅ 배포 상태 확인

GitHub 저장소 → **Actions** 탭에서 실시간 배포 상태 확인 가능

### 성공 사인 ✅
- 녹색 체크마크 표시
- "Build successful!" 메시지

### 실패 시 ❌
- 빨간색 X 표시
- 에러 로그 확인 가능

---

## 🎓 교사용 팁

### 학생에게 공유하기

1. **URL 공유**: `https://plusiam.github.io/tilly-interactive-worksheet/`
2. **QR 코드**: GitHub Pages URL을 QR 코드로 변환
3. **모바일**: iOS Safari, Chrome 모두 지원

### 수정 후 배포

1. 로컬에서 수정
```bash
git add .
git commit -m "fix: 오타 수정"
git push
```

2. 5-10분 후 자동 배포됨
3. 학생들의 브라우저에서 새로고침

### 버전 관리

```bash
# 특정 버전으로 되돌리기
git log  # 커밋 목록 확인
git revert <commit-hash>  # 특정 커밋 취소

# 또는 이전 버전으로 돌아가기
git checkout <commit-hash>
git push -f origin main
```

---

## 🆘 문제 해결

### Q: 배포 후 변경사항이 안 보여요
**A:** 
- 브라우저 캐시 삭제 (Ctrl+Shift+Delete)
- 또는 시크릿 모드에서 확인
- 5-10분 정도 기다려보기

### Q: 배포가 실패했어요
**A:**
1. GitHub Actions 로그 확인
2. 빌드 오류 메시지 확인
3. 로컬에서 `npm run build` 테스트
4. 필요시 이전 버전으로 되돌리기

### Q: 로컬에서는 잘 되는데 배포하면 안 돼요
**A:**
```bash
# 캐시 삭제 후 재빌드
rm -rf node_modules dist
npm install
npm run build
```

---

## 📚 참고 자료

- [GitHub Pages 공식 문서](https://pages.github.com/)
- [GitHub Actions 공식 문서](https://docs.github.com/actions)
- [Vite 공식 문서](https://vitejs.dev/)

---

**Made with ❤️ for Education**

마지막 배포: 2025-11-03
