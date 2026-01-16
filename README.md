# 💰 Budgeto - Smart Expense Tracker PWA

<div align="center">
  <img src="icons/icon-512x512.png" alt="Budgeto Icon" width="200" />
  
  **한국어 | ไทย | English**
  
  스마트한 지출 관리를 위한 Progressive Web App
</div>

## ✨ Features

- 📊 **수입/지출 추적**: 카테고리별로 쉽게 기록하고 관리
- 💰 **예산 관리**: 월별 예산 설정 및 실시간 모니터링
- 🌍 **다국어 지원**: 한국어, 태국어, 영어 지원
- 🌙 **다크 모드**: 눈이 편한 다크/라이트 테마 전환
- 📅 **월간 내비게이션**: 과거 데이터 손쉽게 조회
- 📱 **모바일 최적화**: 홈 화면에 설치하여 앱처럼 사용
- 🔒 **오프라인 지원**: 인터넷 없이도 완벽하게 동작
- 💾 **로컬 저장**: 브라우저에 안전하게 데이터 저장

## 🚀 Quick Start

### 온라인 데모

GitHub Pages에서 바로 사용: [https://YOUR_USERNAME.github.io/moneyplan](https://YOUR_USERNAME.github.io/moneyplan)

### 로컬 실행

1. 이 저장소를 클론합니다:
```bash
git clone https://github.com/YOUR_USERNAME/moneyplan.git
cd moneyplan
```

2. 로컬 서버를 실행합니다:
```bash
# Python 3 사용
python -m http.server 8000

# 또는 Node.js 사용
npx serve
```

3. 브라우저에서 접속:
```
http://localhost:8000
```

## 📱 모바일 홈 화면에 설치

### iOS (Safari)

1. Safari에서 앱 접속
2. 공유 버튼 (⬆️) 탭
3. "홈 화면에 추가" 선택
4. "추가" 버튼 탭

### Android (Chrome)

1. Chrome에서 앱 접속
2. 주소창의 "설치" 버튼 탭
3. 또는 메뉴 (...) > "홈 화면에 추가" 선택

## 🛠️ Technology Stack

- **Frontend**: React 18 (ESM)
- **UI**: Tailwind CSS
- **Icons**: Lucide React
- **PWA**: Service Worker, Web App Manifest
- **Storage**: localStorage (클라이언트 사이드)

## 📂 Project Structure

```
moneyplan/
├── index.html          # 메인 애플리케이션
├── manifest.json       # PWA 매니페스트
├── sw.js              # Service Worker
├── icons/             # 앱 아이콘
│   ├── icon-72x72.png
│   ├── icon-192x192.png
│   ├── icon-512x512.png
│   └── apple-touch-icon.png
└── README.md
```

## 🎨 Features in Detail

### 캐릭터 시스템
귀여운 Pompit 캐릭터가 여러분의 재정 상태에 따라 반응합니다:
- 😊 **Happy**: 저축률이 높을 때
- 😢 **Sad**: 지출이 많을 때
- 😴 **Sleeping**: 데이터가 없을 때
- 🤓 **Scanning**: 영수증 스캔 중

### 카테고리

**지출**:
식비, 간식, 음료, 카페, 교통, 주거, 쇼핑, 문화, 미용, 건강, 반려견, 기타

**수입**:
월급, 프리랜서, 선물, 기타

## 🔧 Development

### Prerequisites
- 모던 웹 브라우저 (Chrome, Safari, Firefox 등)
- Python 3 또는 Node.js (로컬 서버용)

### 새 기능 추가
1. `index.html`의 React 컴포넌트 수정
2. 필요시 `manifest.json` 업데이트
3. Service Worker 캐시 버전 업데이트 (`sw.js`의 `CACHE_NAME`)

## 📦 Deployment

### GitHub Pages

1. GitHub에 저장소 생성

2. 코드 푸시:
```bash
git init
git add .
git commit -m "Initial commit: Budgeto PWA"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/moneyplan.git
git push -u origin main
```

3. GitHub Repository Settings:
   - **Settings** > **Pages**
   - **Source**: Deploy from a branch
   - **Branch**: main / (root)
   - **Save**

4. 몇 분 후 `https://YOUR_USERNAME.github.io/moneyplan` 에서 접속 가능

### 기타 호스팅

- **Vercel**: `vercel deploy`
- **Netlify**: Drag & drop 또는 Git 연동
- **Cloudflare Pages**: Git 연동

## 🔒 Privacy & Security

- 모든 데이터는 **브라우저 로컬 스토리지**에만 저장됩니다
- **서버로 전송되지 않습니다**
- 계정 생성이나 로그인 불필요
- 완전한 프라이버시 보장

## 📝 License

MIT License - 자유롭게 사용, 수정, 배포하세요!

## 🤝 Contributing

이슈 제보 및 Pull Request는 언제나 환영합니다!

## 💡 Credits

Created with ❤️ for better financial management

---

<div align="center">
  Made with React + PWA
</div>
