# HTRB (hight temperature reverse bias)
### 개요
- IGBT, MOSFET 또는 기타 전력 반도체의 열 적, 전기적 스트레스를 모두 적용하여
  DUT의 고장 메커니즘을 검사하는 응용 소프트웨어입니다.

### 주요기능
1. HVPS 3대와 TCP/IP 통신하여 Drain과 Source 사이 고압의 역 바이어스를
  적용하고 누설 전류 값을 측정합니다.
2. 전압, 전류 데이터를 정기적으로 기록하고, 로깅데이터를 CSV 파일 형태로 저장합니다.
3. Chamber와의 Serial 통신을 통한, 온도 제어가 가능합니다.
