# Transformer 아키텍처

## 개요
Transformer는 2017년 Google이 발표한 "Attention is All You Need" 논문에서 제안된 신경망 아키텍처입니다.
현대 LLM의 기반이 되는 핵심 구조입니다.

## 핵심 구성 요소

### 1. Self-Attention (자기 주의 메커니즘)
입력 시퀀스 내 각 토큰이 다른 모든 토큰과의 관계를 계산합니다.
- **Query (Q)**: 현재 토큰의 질의 벡터
- **Key (K)**: 다른 토큰의 키 벡터
- **Value (V)**: 다른 토큰의 값 벡터

```
Attention(Q, K, V) = softmax(QK^T / √dk) * V
```

### 2. Multi-Head Attention
여러 개의 Attention을 병렬로 수행하여 다양한 관점에서 정보를 취합합니다.

### 3. Feed-Forward Network
각 토큰에 독립적으로 적용되는 2층 완전 연결 신경망입니다.

### 4. Layer Normalization
학습 안정화를 위한 정규화 층입니다.

### 5. Positional Encoding
순서 정보가 없는 Attention에 위치 정보를 추가합니다.

## 참고 자료
- [Attention is All You Need (2017)](https://arxiv.org/abs/1706.03762)
