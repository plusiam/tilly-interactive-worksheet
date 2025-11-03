# 🎨 틸리 인터랙티브 학습지

> 그림책 '틸리'를 읽고 용기와 실천에 대해 깊이 생각해보는 웹 기반 학습 도구

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18-blue)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-38bdf8)](https://tailwindcss.com/)
[![Deploy Status](https://github.com/plusiam/tilly-interactive-worksheet/actions/workflows/deploy.yml/badge.svg)](https://github.com/plusiam/tilly-interactive-worksheet/actions)

## 🚀 라이브 배포

**📱 지금 바로 사용하기:**
```
https://plusiam.github.io/tilly-interactive-worksheet/
```

## 📚 소개

**틸리 인터랙티브 학습지**는 그림책 '틸리'를 읽은 후, 학생들이 용기의 의미를 자기 삶과 연결하여 내면화할 수 있도록 설계된 웹 기반 교육 도구입니다.

### ✨ 주요 특징

- 🎯 **7단계 구조화된 학습** - 단계별로 생각을 깊이 있게 발전
- 🎨 **인터랙티브 그림 그리기** - Canvas API로 직접 '벽' 표현
- 💾 **자동 저장 기능** - 로컬 스토리지로 진행 상황 보존
- 📱 **반응형 디자인** - PC, 태블릿 모두 지원
- 🖨️ **PDF 출력** - 완성된 학습지 저장 및 인쇄
- 🌈 **직관적 UI** - 학생 친화적인 색상과 이모지

## 🚀 빠른 시작

### 방법 1: 바로 실행 (가장 간단!)

```bash
# 1. 저장소 클론
git clone https://github.com/plusiam/tilly-interactive-worksheet.git

# 2. 파일 열기
cd tilly-interactive-worksheet
open index.html  # Mac
# 또는
start index.html  # Windows
```

### 방법 2: 라이브 서버로 실행

```bash
npm install
npm run dev
```

### 방법 3: 온라인 접속

GitHub Pages에서 자동 배포됩니다:
```
https://plusiam.github.io/tilly-interactive-worksheet/
```

## 🎓 교육 목표

1. **자기 인식** - 자신의 두려움과 어려움 명확히 하기
2. **사회적 학습** - 친구와 대화하며 공감과 연대 경험
3. **창의적 표현** - 추상적 개념을 시각적으로 표현
4. **가치 탐구** - 자신에게 중요한 가치 발견
5. **실천 계획** - 구체적이고 실현 가능한 행동 계획 수립

## 📖 7단계 학습 구조

| 단계 | 제목 | 주요 활동 | 시간 |
|------|------|-----------|------|
| 0 | 시작하기 | 오리엔테이션 | 5분 |
| 1 | 나의 벽 찾기 | 어려운 일 3가지 작성 | 10분 |
| 2 | 친구와 나누기 | 2인 대화 및 공감 | 10분 |
| 3 | 벽에 가치 새기기 | 캔버스 그림 + 가치 작성 | 10분 |
| 4 | 용기란? | 용기 개념 정의하기 | 10분 |
| 5 | 틸리의 방법 | 그림책 분석 및 방법 찾기 | 10분 |
| 6 | 나의 실천 | 구체적 실천 계획 수립 | 10분 |
| 7 | 완료 | 요약 확인 및 저장 | 5분 |

**총 소요 시간**: 약 70-80분 (2교시)

## 🛠️ 기술 스택

- **React 18** - UI 컴포넌트 프레임워크
- **Tailwind CSS** - 유틸리티 CSS 프레임워크
- **Lucide React** - 아이콘 라이브러리
- **Canvas API** - 그림 그리기 기능
- **Local Storage** - 브라우저 저장소
- **Vite** - 번들러 (선택사항)
- **GitHub Actions** - CI/CD 자동 배포

## 📱 지원 환경

- **브라우저**: Chrome, Edge, Safari, Firefox (최신 버전)
- **기기**: PC, 노트북, 태블릿, 스마트폰
- **화면**: 768px 이상 권장
- **인터넷**: 최초 로드 시에만 필요 (이후 오프라인 가능)

## 👩‍🏫 교사용 가이드

### 수업 준비

1. **그림책 준비**: '틸리' 그림책
2. **기기 준비**: 학생 1인 1대 또는 2인 1조
3. **링크 공유**: https://plusiam.github.io/tilly-interactive-worksheet/

### 수업 진행 예시

**[1교시 - 40분]**
```
📚 그림책 '틸리' 함께 읽기 (15분)
→ 1-3단계 활동 (25분)
```

**[2교시 - 40분]**
```
💭 4-6단계 활동 (30분)
→ 7단계 완료 및 발표 (10분)
```

자세한 가이드는 [교사용 가이드](./docs/teacher-guide.md)를 참고하세요.

## 📊 학습 효과

- 📈 **메타인지 발달** - 자기 감정과 두려움 인식
- 🤝 **사회정서 학습** - 공감과 연대 경험
- 💭 **창의적 사고** - 추상적 개념의 구체화
- ⚡ **실행 기능** - 계획 수립과 실천 의지
- 🎯 **가치 내재화** - 핵심 가치 탐구

## 🔐 개인정보 보호

- ✅ 모든 데이터는 **로컬 기기에만** 저장
- ✅ 외부 서버로 전송되지 않음
- ✅ 브라우저 캐시 삭제 시 데이터 삭제
- ✅ 완전한 오프라인 작동

## 📞 지원 및 기여

### 버그 리포트
GitHub Issues에서 버그를 리포트해주세요.

### 기능 제안
새로운 기능 아이디어를 Issue로 제안해주세요.

### 기여하기
Pull Request를 환영합니다!

```bash
# 1. Fork
# 2. Branch 생성
git checkout -b feature/amazing-feature

# 3. Commit
git commit -m 'Add amazing feature'

# 4. Push
git push origin feature/amazing-feature

# 5. Pull Request 생성
```

## 📄 라이선스

MIT License - 자유롭게 사용, 수정, 배포 가능

## 🙏 감사의 말

이 프로젝트는 교육 현장의 선생님들과 학생들의 피드백으로 만들어졌습니다.

---

## 🎯 로드맵

### v1.1 (진행 중)
- [x] 자동 배포 (GitHub Pages + GitHub Actions)
- [x] 빌드 최적화 (Vite)
- [ ] 태블릿 터치 최적화
- [ ] 다국어 지원 (영어)

### v2.0 (계획)
- [ ] 교사 대시보드
- [ ] 학급 데이터 통계
- [ ] Google Sheets 연동
- [ ] AI 피드백 기능

## 📚 관련 리소스

- [빠른 시작 가이드](./QUICKSTART.md)
- [배포 가이드](./DEPLOY.md)
- [교사용 상세 가이드](./docs/teacher-guide.md)
- [변경 기록](./CHANGELOG.md)

---

**Made with ❤️ for Education**

블로그: [GitHub Pages](https://plusiam.github.io/tilly-interactive-worksheet/)
