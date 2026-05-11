# 솔레노이드 키보드 프로젝트

기계식 키보드 입력에 맞춰 솔레노이드가 실제로 타격하는 DIY 실험 프로젝트입니다.
타자기 같은 물리적인 타건감과 소리를 구현하는 것을 목표로 제작했습니다.

## 프로젝트 특징

* 솔레노이드를 이용한 물리 타격 구조
* 핸드와이어 키보드 매트릭스 제작
* IRLZ44N MOSFET 기반 솔레노이드 제어
* 3D 프린트 하우징 및 구조물 설계
* 타입라이터 느낌의 타건 사운드 실험
* 브레드보드 및 PCB 기반 테스트 진행

---

## 사용 부품

* Arduino Pro Micro
* IRLZ44N MOSFET
* 솔레노이드
* 기계식 키보드 스위치
* 정류 다이오드 (1N4007 등)
* 저항

  * 220Ω
  * 10kΩ
* 배터리 팩
* 3D 프린트 부품

---

## 현재 상태

* 키보드 매트릭스 입력 테스트 완료
* 솔레노이드 단독 구동 성공
* MOSFET 제어 테스트 완료
* PCB 프로토타입 제작 진행
* 구조 및 전원 설계 수정 중

---

## 참고 자료

프로젝트 제작 과정에서 아래 자료들을 참고했습니다.

* [Cracked - Hand Wiring a Custom Keyboard](https://blog.noavermeers.ch/understanding-the-keyboard-matrix/?utm_source=chatgpt.com)
* [QMK Documentation](https://docs.qmk.fm/?utm_source=chatgpt.com)
* [Arduino 공식 사이트](https://www.arduino.cc/?utm_source=chatgpt.com)
* [Keyboard Matrix Explained](https://pcbheaven.com/wikipages/How_Key_Matrices_Works/?utm_source=chatgpt.com)

---

## 목표

단순한 전자 키보드가 아니라,
실제로 기계가 움직이며 타건하는 감각을 구현하는 입력 장치를 만드는 것이 목표입니다.

추후에는:

* 무선화
* 사운드 튜닝
* 타자기식 메커니즘 추가
* 알고리즘 기반 인터랙션
* 아트/퍼포먼스 활용

등을 실험할 예정입니다.

---

## 주의사항

솔레노이드는 순간적으로 큰 전류를 사용합니다.
반드시 플라이백 다이오드를 사용하고, 전원 및 발열에 주의해야 합니다.

전자회로 및 배터리 사용 시 안전에 주의하세요.

---

## 라이선스

본 프로젝트는 MIT 라이선스를 따릅니다.

프로젝트의 사용, 수정, 배포, 상업적 이용이 가능하지만,
원본 저작권 표시 및 라이선스 내용은 반드시 포함되어야 합니다.
