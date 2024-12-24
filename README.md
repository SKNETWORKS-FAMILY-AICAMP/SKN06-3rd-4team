# SKN06-3rd-4Team


# 👩‍⚖️세법 질의응답 시스템👨‍⚖️ 

**프로젝트명:** 세법 확인 챗봇 시스템  
**개발기간:** 2024.12.24 - 2024.12.26

## 💻 팀 소개

# 팀명: Home Tax 

![TaxTaxesGIF](https://github.com/user-attachments/assets/9fb562c4-7193-4f3c-87a8-68022176d9d8)


| [노원재] | [박서윤] | [박유나] | [유경상] | [전하연] |
|:-------:|:-------:|:-------:|:-------:|:-------:|
|    ![TaxesTaxEvasionGIF](https://github.com/user-attachments/assets/6933ed25-632f-42a2-a53c-a02c91928555)
     |     ![CleanEnergyHappyTaxDayGIF](https://github.com/user-attachments/assets/7109d3fd-e23f-455b-9623-f194be72639c)
    |     ![TaxDayMoneyGIF](https://github.com/user-attachments/assets/80dc5c60-0d5c-4fea-a43d-28936d635f4e)
    |     ![TheSimpsonsTaxTimeGIF](https://github.com/user-attachments/assets/052dc98b-907e-480d-92ac-33cef1d67940)
    |         |

---

### 📌 1. 프로젝트 개요

#### 1.1. 개발 동기 및 목적  
본 프로젝트는 **복잡한 세법 관련 질문에 대한 신속하고 정확한 답변 제공**을 목표로 하는 **세법 확인 챗봇 시스템**을 구현하고자 했습니다. 법제처에서 제공하는 세법 관련 데이터를 활용하여 세금 관련 질의에 대한 정확한 답변을 제공하는 챗봇 시스템을 개발했습니다.  

#### 1.2. 필요성  
세법은 복잡하고 자주 개정되어 일반인들이 이해하기 어려운 경우가 많습니다. 특히 **개인과 기업의 세금 관련 문의**에 대해 신속하고 정확한 정보 제공이 필요합니다. 따라서, **세금 관련 자주 묻는 질문**에 즉시 답변할 수 있는 챗봇 시스템을 통해 **세법에 대한 접근성을 향상**시키고 사용자들의 이해를 돕고자 했습니다.

#### 1.3. 개발 목표  
- **정확한 정보 제공:** 최신 세법 규정과 절차 반영  
- **정확성 향상:** 일반적인 챗봇 한계를 넘는 **구체적이고 정확한 세법 관련 답변 제공**  
- **사용자 경험 개선:** 직관적이고 빠른 세법 정보 제공을 위한 **UI/UX 최적화**  

---

### 📌 2. 상세 내용

#### 2.1. 데이터 수집 및 전처리
- **법제처**에서 세법 관련 데이터 다운로드
- pdf파일에서 표 데이터 가져오기
- 불필요하게 반복되는 부분 제거  
- 삭제된 조항 제거

#### 2.2. 벡터 데이터베이스 구현 
- 전처리된 데이터를 벡터화
- 선택한 벡터 데이터베이스에 데이터 저장

#### 2.3. RAG 구현
- 질의 처리 로직 구현
- 관련 정보 검색 메커니즘 구축

#### 2.4. LLM 연동
- 선택한 LLM과 RAG 시스템 연동
- 검색된 정보를 바탕으로 답변 생성 로직 구현
  
#### 5. 성능 테스트 및 평가 (-----evaluation까지 안하면 평가는 삭제------)
- 다양한 세법 관련 질의에 대한 시스템 응답 테스트
- 정확성, 관련성, 응답 시간 등 평가 지표 설정 및 측정
  
---
### 📌 3. 답변 검증
- **검증 방법:** 사용자가 입력한 질문과 챗봇의 응답을 비교하고, 실제 법령에 명시된 내용을 확인하여 정확성을 검증합니다.
- **결과:** 시스템이 제공하는 답변의 정확성과 일관성을 지속적으로 모니터링하여 시스템을 개선합니다.

---
### 📌 4. streamlit 구현(------스트림릿까지 올린다면-------)






---
