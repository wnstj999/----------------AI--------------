# 📘 Multi-Cam AI Security System  
### 멀티 CCTV 기반 외부인 탐지 & 통합 이동경로 추적 시스템 제안서

## 1️⃣ 프로젝트 개요
### ■ 프로젝트명  
**Multi-Camera Integrated Security AI**

### ■ 핵심 목표  
- 멀티 CCTV 동일 인물 자동 식별 (Re-ID)
- 지도 기반 실시간 이동 경로 통합 시각화
- 내부인/외부인 얼굴 임베딩 비교를 통한 자동 분류
- 외부인 알림 시스템(App/Web)

## 2️⃣ 프로젝트 필요성
- 출입통제 한계 → CCTV와 동선 추적 필요
- 관제 인력 부족 → AI 자동 분석 필요
- 보안·스마트빌딩·제조 산업 실수요 매우 높음

## 3️⃣ 전체 시스템 아키텍처
[CCTV Streams] → [YOLO Detection] → [Re-ID Matching]  
→ [Face Embedding 비교] → [내/외부인 판정]  
→ [지도 기반 위치 표시] → [이동경로 생성] → [알림]

## 4️⃣ 기술 상세
### ✔ Detection: YOLOv8  
### ✔ Re-ID 모델: OSNet, TransReID  
### ✔ Face Embedding: ArcFace / InsightFace  
### ✔ 지도 기반 디지털 트윈: 2D 평면도 매핑  
### ✔ 알림: Firebase / Webhook

## 5️⃣ 데이터셋 확보
- YOLO: COCO 기반 사전학습 모델 → 추가 데이터 필요 없음  
- Re-ID: Market-1501, DukeMTMC-ReID 사전학습 모델 사용  
- Face Embedding: ArcFace pretrained → 직원 얼굴 1~3장만 필요

## 6️⃣ 구현 난이도 & 역할
- AI 모델 직접 학습 불필요, 사전학습 모델 조합 방식
- 역할: AI 엔진 / 백엔드 서버 / 프론트 지도 UI

## 7️⃣ 산출물
- 멀티 CCTV 통합 관제 UI
- 지도 기반 이동경로 시각화
- 내부/외부인 판정 기능
- 외부인 실시간 알림 시스템
- 시연 영상 및 매뉴얼

## 8️⃣ 프로젝트 가치
- 실제 기업 보안 문제 해결
- 스마트빌딩·스마트팩토리와 완벽히 연계
- 데이터 확보 문제 없음
- 발표 및 데모 임팩트 큼
