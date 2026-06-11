# ⚡ AI Hub — AI 서비스 모음

> AI 서비스를 카테고리별로 한눈에 모아둔 개인 허브 사이트

🔗 **라이브 사이트:** https://ms3120042000-create.github.io/ai-hub/  
📦 **저장소:** https://github.com/ms3120042000-create/ai-hub

---

## 📋 프로젝트 개요

| 항목 | 내용 |
|---|---|
| 기술 스택 | HTML / CSS / JavaScript (단일 파일) |
| 배포 | GitHub Pages (master 브랜치 자동 배포) |
| 총 서비스 수 | 65개+ |
| 방문자 카운터 | hits.sh 연동 |

---

## 🗂️ 카테고리 구조

### ⭐ 자주 쓰는 AI
| 소카테고리 | 서비스 |
|---|---|
| 즐겨찾기 | Claude, Gemini, ChatGPT, Canva, Lovable, Gamma, Google AI Studio |
| 디자인/학습 | Docshunt, Padlet, CapCut, Figmapedia, AI×Figma 강의 |

### 🤖 AI 어시스턴트
| 소카테고리 | 서비스 |
|---|---|
| 대화형 AI | Claude, ChatGPT, Gemini, Grok, Genspark, Microsoft Copilot, Meta AI, DeepSeek, Poe, Character.AI |
| 검색 AI | Perplexity, You.com, Phind |
| 생산성 AI | NotebookLM, Gamma, Notion AI |

### 🎨 AI 이미지
| 소카테고리 | 서비스 |
|---|---|
| 이미지 생성 | Whisk, Midjourney, DALL-E 3, Stable Diffusion, Adobe Firefly, Leonardo AI, Flux, Krea AI, Civitai |
| 디자인 AI | Ideogram, Recraft |

### 🎵 AI 음악/영상
| 소카테고리 | 서비스 |
|---|---|
| 음악 생성 | SUNO, Udio, Mubert |
| 영상 생성 | Runway, Pika, HeyGen, Sora, Kling AI, Vidu, Luma AI, Descript |
| 음성 생성 | ElevenLabs |

### 💻 AI 코딩
| 소카테고리 | 서비스 |
|---|---|
| 코드 어시스턴트 | GitHub Copilot, Cursor, Windsurf, Replit, Claude Code |
| 웹 빌더 | Lovable, V0, Bolt.new, Vercel |

### 📚 AI 리소스
| 소카테고리 | 서비스 |
|---|---|
| 모델 허브 | Hugging Face, GitHub, Ollama, LM Studio |
| 개발 플랫폼 | Google AI Studio, OpenAI Platform, Anthropic Console, Groq, Together AI, OpenRouter, Replicate, Dify |
| 자동화 | n8n, Make |

---

## ✨ 주요 기능

- **상단 탭 메뉴** — 6개 대카테고리 빠른 전환
- **사이드바** — 소카테고리 필터링 + 서비스 수 표시
- **카드 형식** — 파비콘, 설명, 방문하기 버튼
- **🔥 HOT / ✨ NEW 배지** — 주목 서비스 표시
- **검색** — 이름·설명·카테고리 전체 검색
- **방문자 카운터** — hits.sh 실시간 카운트
- **Open Graph 태그** — 카카오톡·슬랙 링크 미리보기
- **반응형 디자인** — 모바일 지원

---

## 📝 작업 이력

| 날짜 | 작업 내용 |
|---|---|
| 2026-06-11 | 프로젝트 최초 생성 — 48개 AI 서비스, 5개 카테고리 |
| 2026-06-11 | 15개 서비스 추가 (ElevenLabs, NotebookLM, Gamma, Poe, Character.AI, Descript, Luma AI, Krea AI, Civitai, OpenRouter, Replicate, Dify, n8n, Make, Notion AI) |
| 2026-06-11 | GitHub Pages 배포 완료 |
| 2026-06-11 | Open Graph 메타태그 추가 (링크 미리보기) |
| 2026-06-11 | ⭐ 자주 쓰는 AI 카테고리 신설 — Claude, Gemini, ChatGPT, CapCut, Canva, Lovable |
| 2026-06-11 | 자주 쓰는 AI에 Gamma, Google AI Studio 추가 |
| 2026-06-11 | 디자인/학습 소카테고리 — Figmapedia, AI×Figma 강의, Padlet, CapCut, Docshunt 추가 |
| 2026-06-11 | 방문자 카운터 추가 (hits.sh) |
| 2026-06-11 | 중복 제거 — CapCut(즐겨찾기 중복), Canva AI(동일 URL 중복) |

---

## 🚀 로컬 실행

별도 서버 불필요 — `index.html`을 브라우저로 바로 열기

```bash
# 저장소 클론
git clone https://github.com/ms3120042000-create/ai-hub.git

# index.html 을 브라우저로 열기
```

## 🔄 서비스 추가 방법

`index.html` 내 `S` 배열에 아래 형식으로 추가 후 `git push`:

```javascript
{ n:"서비스명", d:"설명", u:"https://...", c:"카테고리", s:"소카테고리", color:"#색상코드" }
```

`badge` 필드 옵션: `"hot"` 또는 `"new"`
