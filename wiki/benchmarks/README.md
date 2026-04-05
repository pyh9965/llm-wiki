# 벤치마크 및 평가 방법

## 주요 벤치마크

| 벤치마크 | 평가 항목 | 설명 |
|----------|-----------|------|
| MMLU | 지식 | 57개 분야 다지선다 문제 |
| HumanEval | 코딩 | Python 코드 생성 |
| GSM8K | 수학 | 초등 수준 수학 문제 |
| HellaSwag | 상식 추론 | 문장 완성 |
| ARC | 과학 | 초중등 과학 |
| TruthfulQA | 사실성 | 거짓 정보 생성 방지 |
| MATH | 고급 수학 | 경시대회 수준 문제 |

## 평가 지표
- **Accuracy**: 정확도
- **Pass@k**: 코딩 평가에서 k번 시도 중 통과율
- **BLEU/ROUGE**: 텍스트 생성 품질
- **Perplexity (PPL)**: 언어 모델 불확실성

## 리더보드
- [Chatbot Arena (LMSYS)](https://chat.lmsys.org/)
- [Open LLM Leaderboard (Hugging Face)](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)
