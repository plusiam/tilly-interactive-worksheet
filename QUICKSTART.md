# 🎯 빠른 시작 가이드

## 👨‍🏫 교사용 (간단 버전)

### 1️⃣ 학생에게 공유하기

```
📱 이 링크를 클릭하세요:
https://plusiam.github.io/tilly-interactive-worksheet/
```

**특징:**
- 💾 자동 저장 (브라우저 저장소)
- 📱 모든 기기 지원 (PC, 태블릿, 스마트폰)
- 🖨️ PDF 저장 및 인쇄 가능
- ⚡ 인터넷 없이도 작동

### 2️⃣ 수업 진행

**1교시 (40분)**
```
📚 그림책 '틸리' 함께 읽기 (15분)
↓
1단계: 나의 벽 찾기 (5분)
2단계: 친구와 나누기 (10분)
3단계: 벽에 가치 새기기 (10분)
```

**2교시 (40분)**
```
4단계: 용기란? (10분)
5단계: 틸리의 방법 (10분)
6단계: 나의 실천 (15분)
7단계: 완료 및 저장 (5분)
```

---

## 💻 개발자용 (기술 버전)

### 1️⃣ 로컬 환경 설정

```bash
git clone https://github.com/plusiam/tilly-interactive-worksheet.git
cd tilly-interactive-worksheet
npm install
npm run dev
```

### 2️⃣ 개발 중

- 파일 수정 → 자동 반영
- `src/` 폴더에 코드 작성
- 실시간 미리보기

### 3️⃣ 배포하기

```bash
npm run build    # 프로덕션 빌드
git add .
git commit -m "feat: 새로운 기능"
git push origin main
```

→ 자동 배포 (GitHub Actions)
→ 5-10분 후 라이브

---

## 📊 프로젝트 구조

```
tilly-interactive-worksheet/
├── index.html              # 메인 페이지
├── package.json            # npm 의존성
├── vite.config.js          # 빌드 설정
├── tailwind.config.js      # 스타일 설정
├── DEPLOY.md               # 배포 가이드 (자세함)
├── QUICKSTART.md           # 이 파일
├── README.md               # 프로젝트 소개
└── docs/
    └── teacher-guide.md    # 교사 수업 가이드
```

---

## ✨ 주요 기능

| 기능 | 설명 |
|------|------|
| **7단계 구조** | 단계별로 체계적인 학습 진행 |
| **그림 그리기** | Canvas API로 벽을 직접 표현 |
| **자동 저장** | 로컬 스토리지에 자동 저장 |
| **PDF 출력** | 결과물을 PDF로 저장/인쇄 |
| **반응형 디자인** | PC, 태블릿, 스마트폰 모두 지원 |

---

## 🎓 학습 효과

✅ **자기 인식** - 자신의 두려움 명확히 하기
✅ **공감** - 친구와의 대화를 통한 공감 경험
✅ **창의성** - 추상적 개념을 시각적으로 표현
✅ **실천력** - 구체적이고 실현 가능한 계획 수립

---

## 🆘 문제 해결

### 배포 후 변경사항이 안 보여요
1. 브라우저 캐시 삭제 (Ctrl+Shift+Delete)
2. 시크릿 모드에서 확인
3. 5-10분 기다리기

### 로컬에서 에러가 발생해요
```bash
rm -rf node_modules dist
npm install
npm run dev
```

### GitHub Actions 배포 실패
1. [GitHub Actions 로그](../../actions) 확인
2. 로컬에서 `npm run build` 테스트
3. 필요시 이전 버전으로 되돌리기

---

## 📚 더 알아보기

- **상세 배포 가이드**: [DEPLOY.md](./DEPLOY.md)
- **교사 수업 가이드**: [docs/teacher-guide.md](./docs/teacher-guide.md)
- **프로젝트 소개**: [README.md](./README.md)
- **변경 기록**: [CHANGELOG.md](./CHANGELOG.md)

---

## 🤝 기여하기

버그 리포트, 기능 제안, Pull Request 환영합니다!

```bash
# 1. Fork & Clone
# 2. Branch 생성
git checkout -b feature/amazing-feature

# 3. 작업 후 Commit
git commit -m 'Add amazing feature'

# 4. Push
git push origin feature/amazing-feature

# 5. Pull Request 생성
```

---

**🎯 라이브 사이트**: https://plusiam.github.io/tilly-interactive-worksheet/

Made with ❤️ for Education
