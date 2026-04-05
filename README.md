# LLM Wiki

LLM(대형 언어 모델, Large Language Model)에 관한 지식을 체계적으로 정리한 위키입니다.

## LLM이란?

LLM은 방대한 양의 텍스트 데이터로 학습된 인공지능 언어 모델입니다.  
GPT, Claude, Gemini 같은 AI 어시스턴트의 핵심 기술입니다.

## 📁 구조

```
wiki/
├── models/       # 모델별 상세 정리 (GPT, Claude, Gemini, LLaMA 등)
├── concepts/     # 핵심 개념 (Transformer, Attention, RLHF 등)
├── papers/       # 주요 논문 요약
├── tools/        # 관련 도구 및 프레임워크
└── benchmarks/   # 성능 평가 벤치마크
```

## 🚀 빠른 시작

1. 처음이라면 → [`wiki/concepts/transformer.md`](wiki/concepts/transformer.md) 부터 읽기
2. 모델 비교가 궁금하다면 → [`wiki/models/`](wiki/models/)
3. 논문을 찾는다면 → [`wiki/papers/`](wiki/papers/)

## 📚 주요 카테고리

| 카테고리 | 내용 |
|----------|------|
| [모델](wiki/models/) | GPT, Claude, Gemini, LLaMA 등 주요 모델 정리 |
| [개념](wiki/concepts/) | Transformer, Attention, RLHF 등 핵심 개념 |
| [논문](wiki/papers/) | Attention is All You Need 등 중요 논문 요약 |
| [도구](wiki/tools/) | LangChain, Ollama 등 개발 도구 |
| [벤치마크](wiki/benchmarks/) | MMLU, HumanEval 등 성능 평가 지표 |

## 🤝 기여 방법

1. 이 레포를 Fork
2. 새 브랜치 생성: `git checkout -b docs/새문서이름`
3. 문서 작성 후 커밋: `git commit -m "docs: 새 문서 추가"`
4. Pull Request 생성

## 📝 작성 규칙

- 한글로 작성 (전문 용어는 영어 병기)
- 마크다운(.md) 형식 사용
- 출처 및 참고 링크 반드시 포함
