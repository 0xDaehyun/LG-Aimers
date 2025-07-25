# D&O 해커톤 과제: 곤지암 리조트 식음업장 수요예측

## 📌 대회 주제  
**곤지암 리조트 데이터 분석 및 식음업장 수요예측**

## 🏆 사업 배경·목표  
- **시장 현황**  
  - 국내 관광·레저사업 경쟁 심화  
  - 운영비용 상승으로 식음·부대시설 효율화·효과성 확보 필요  
- **사업 목표**  
  - 식음매장 운영 고도화를 통한 비용 최적화(손실 저감)  
  - 고객 만족도 향상

## 📈 수행 단계  
1. **계절성 분석**  
   - 봄·여름·가을·겨울별 수요 추세 확인  
2. **내부 데이터 연계 분석**  
   - POS 매출 ↔ 객실정보·예약·부대시설 이용 간 상관관계 파악  
3. **외부 변수 적용**  
   - 기온, 관광객 수, 지역 행사 등 영향도 분석  
4. **수요예측 모델링**  
   - 최적 모델 선정 후 일일 방문자 예측 및 시각화  

## 📊 데이터 구성  
- **내부 데이터**  
  1. 예약·투숙정보  
     - 객실 유형별 일일 예약율, 투숙 고객 정보  
  2. POS 매출 정보  
     - 업장별 결제 건수·금액  
  3. 부대시설 이용 정보  
     - 스키장·스파·화담숲 등 일별 이용객 수  
- **외부 데이터 (선택 활용)**  
  - 일별 기온·강수량, 관광 트렌드(OTA), 지역 행사 정보  

## 🤖 분석 & 모델링 접근  
- **방문객 규모 예측**: 업장별 일일 방문 인원 예측  
- **외부 요인 영향도**: 다변량 회귀·상관 분석으로 주요 변수 영향 평가  
- **메뉴별 수요 예측**: 매출 데이터를 활용해 메뉴별 판매량 예측  

## 🎯 기대 효과  
- 식자재 준비 및 인력 스케줄 최적화  
- 고객 맞춤 서비스 제공 및 혼잡도 완화  
- 데이터 기반 의사결정 체계 구축을 통한 운영 혁신  
