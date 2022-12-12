
### STM32 정리 notion : <a href="https://quasar-nerine-685.notion.site/STM32-92299ef58e76439ebe51a0c7b2dc05ad" target="_blank"><img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white"/></a>

### 회로도 : <a href="https://quasar-nerine-685.notion.site/529cd8d243c84cbda501ea06b3f23517" target="_blank"><img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white"/></a>

### C언어 정리 notion : <a href="https://quasar-nerine-685.notion.site/C-f1d930156bd3401d8eea20b046bc36cd" target="_blank"><img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white"/></a>

### 암호 및 무결성 검사 : <a href="https://quasar-nerine-685.notion.site/423f780bbe0f417c9540c5ddc983380d" target="_blank"><img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white"/></a>

--------------




### [stm32 통신_I2C]
- I2C통신의 정의: <a href="https://velog.io/@chaeyoonl/STM32-I2C%EB%9E%80" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> <a href="https://velog.io/@chaeyoonl/STM32-I2C-HAL-%ED%95%A8%EC%88%98" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- 외부 EEPROM 주소 접근 : <a href="https://velog.io/@chaeyoonl/STM32-I2C%EC%99%B8%EB%B6%80-EEPROM-%EC%A3%BC%EC%86%8C-%EC%A0%91%EA%B7%BC" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- 외부 EEPROM 사용 코드: <a href="https://github.com/chaeyoonl/Embedded_STM32_Study_I2C_External_EEPROM" target="_blank"><img src="https://img.shields.io/github/stars/org?style=social"/></a>
- 통신 분석: <a href="https://velog.io/@chaeyoonl/stm32-I2C-%ED%86%B5%EC%8B%A0-%EB%B6%84%EC%84%9DEEPROM" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- 관련 해결 오류: <a href="https://velog.io/@chaeyoonl/STM32-I2C-EEPROM-HALBUSY-%EC%98%A4%EB%A5%98" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> <a href="https://velog.io/@chaeyoonl/STM32-I2C-EEPROM-HALI2CMemWrite-not-write-%EC%98%A4%EB%A5%98" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- I2C를 사용할때는 push pull이 아닌 open drain을 사용해야 한다. (버스의 장치가 손상될 수 있기 때문)

  <push pull, open drain>
  - push pull: <a href="https://velog.io/@chaeyoonl/push-pull" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
  - open drain: <a href="https://velog.io/@chaeyoonl/open-drain" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 

- RESTART를 이용한 I2C 통신: <a href="https://velog.io/@chaeyoonl/stm32-restart%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%9C-I2C-%ED%86%B5%EC%8B%A0" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> <a href="https://velog.io/@chaeyoonl/stm32-I2C-%ED%86%B5%EC%8B%A0%EC%8B%9C%EC%97%90-restart%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EC%9D%B4%EC%9C%A0" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a>


### [stm32 sleep mode와 wakeup]
- sleep mode, stop mode, standby mode의 차이: <a href="https://velog.io/@chaeyoonl/stm32-sleep-mode-stop-mode-standby-mode%EC%9D%98-%EC%B0%A8%EC%9D%B4" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- sleep mode 사용: <a href="https://velog.io/@chaeyoonl/stm32-sleep-mode-%EC%82%AC%EC%9A%A9" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- stop mode 사용: <a href="https://velog.io/@chaeyoonl/stm32-stop-mode-%EC%82%AC%EC%9A%A9" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- standby mode 사용: <a href="https://velog.io/@chaeyoonl/stm32-standby-mode-%EC%82%AC%EC%9A%A9" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- 절전모드 알고리즘 및 코드 작성: <a href="https://github.com/chaeyoonl/Embedded_STM32_Study/blob/main/sleep%20mode%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98.PNG" target="_blank"><img src="https://img.shields.io/github/stars/org?style=social"/></a> <a href="https://github.com/chaeyoonl/Embedded_STM32_Study/blob/main/sleep%2C%20stop%2C%20standby%20mode_main.c" target="_blank"><img src="https://img.shields.io/github/stars/org?style=social"/></a>
- 디지털 멀티미터로 측정한 읿반 상태와 sleep mode, stop mode, standby mode 상태의 전류 차이 확인

### [stm32 클린코드]
- Pin naming: <a href="https://github.com/chaeyoonl/Embedded_STM32_Study/blob/main/spi_main.c" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 







------------------------------------


### [IAR Embedded Workbench IDE]
- 관련 오류 해결: <a href="https://velog.io/@chaeyoonl/IAR-%EB%9D%BC%EC%9D%B4%EC%84%BC%EC%8A%A4-%EC%98%A4%EB%A5%98" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> <a href="https://velog.io/@chaeyoonl/IAR-Probe-not-found-%EC%98%A4%EB%A5%98" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a>  <a href="https://velog.io/@chaeyoonl/IAR-STM32CubeMX-Code-Generation-%EC%98%A4%EB%A5%98" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> <a href="https://velog.io/@chaeyoonl/IAR-char-const-%EC%98%A4%EB%A5%98" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> <a href="https://velog.io/@chaeyoonl/IAR-I2C-%EC%84%A4%EC%A0%95-%EC%98%A4%EB%A5%98" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> <a href="https://velog.io/@chaeyoonl/IAR-%EC%98%A4%EB%A5%98%ED%95%B4%EA%B2%B0driver-error" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- 디버거를 이용한 어셈블리 분석: <a href="https://velog.io/@chaeyoonl/IAR-Embedded-Workbench-IDE-%EB%94%94%EB%B2%84%EA%B1%B0%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EC%96%B4%EC%85%88%EB%B8%94%EB%A6%AC-%EB%B6%84%EC%84%9D" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- IAR Embedded Work를 VS Code에서 사용하는 방법: <a href="https://velog.io/@chaeyoonl/IAR-Embedded-Work%EB%A5%BC-VS-Code%EC%97%90%EC%84%9C-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 



### [STM32CubeMX Code Generation 이후 설정]
- Code Generation을 진행한 뒤에 삭제가 되는 부분이 있기에, 재정의 해주어야 하는 부분이 있다. (오류로 추측된다)
- main의 #include 부분이 삭제되기에, Code Generation 이전에 해당 부분을 미리 복사해둔 뒤에 붙여넣기를 하면 편하다.
- I2C 설정 부분 (stm32f4xx_hal_msp.c) : <a href="https://velog.io/@chaeyoonl/STM32-I2C-EEPROM-HALBUSY-%EC%98%A4%EB%A5%98" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a>
- USART 인터럽트 부분 (stm32f4xx_it.c) : <a href="https://velog.io/@chaeyoonl/stm32-UART-%EC%9D%B8%ED%84%B0%EB%9F%BD%ED%8A%B8-%EC%84%A4%EC%A0%95%EB%B6%80%EB%B6%84" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a>


------------------------------------


### [회로분석]
- 물리 KEY 분석: <a href="https://velog.io/@chaeyoonl/%ED%9A%8C%EB%A1%9C%EB%B6%84%EC%84%9D-%EB%AC%BC%EB%A6%ACKEY-%ED%9A%8C%EB%A1%9C-%EB%B6%84%EC%84%9D" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 



------------------------------------

### [CAN 통신]
- CAN 통신 소개 : <a href="https://velog.io/@chaeyoonl/CAN-%ED%86%B5%EC%8B%A0-%EC%86%8C%EA%B0%9C" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- CAN 통신 회로 설계 : <a href="https://velog.io/@chaeyoonl/CAN-%ED%86%B5%EC%8B%A0-%ED%9A%8C%EB%A1%9C-%EC%84%A4%EC%A0%95" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- CAN 통신 MCU (STM32F446RE) 프로젝트 생성 및 설정 (pin, clock 등) : <a href="https://velog.io/@chaeyoonl/CAN-%ED%86%B5%EC%8B%A0-MCU-STM32F446RE-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%83%9D%EC%84%B1-%EB%B0%8F-%EC%84%A4%EC%A0%95-pin-clock-%EB%93%B1" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a>
- CAN 통신 속도 : <a href="https://velog.io/@chaeyoonl/CAN-%ED%86%B5%EC%8B%A0-%EC%86%8D%EB%8F%84" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- CAN FRAME : <a href="https://velog.io/@chaeyoonl/CAN-FRAME" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 
- CAN Filtering : <a href="https://velog.io/@chaeyoonl/CAN-Filtering" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a> 

- CAN Rx Code : <a href="https://github.com/chaeyoonl/CAN_Rx/tree/main" target="_blank"><img src="https://img.shields.io/github/stars/org?style=social"/></a>


------------------------------------


<!--
**chaeyoonl/chaeyoonl** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<a href="https://velog.io/@chaeyoonl" target="_blank"><img src="https://img.shields.io/badge/VELOG-20c997?style=flat-square&logo=Vimeo&logoColor=white"/></a>
<a href="https://blog.naver.com/gkdtkd280" target="_blank"><img src="https://img.shields.io/badge/Naver-03C75A?style=flat-square&logo=Naver&logoColor=white"/></a>
<a href="https://www.notion.so/acbd75c84e834e45acfe388eda1d1b26?v=e9b06de1c0e84822b5dc504cd82473ff&p=098edb9156c04742bc660258b8a8d34d" target="_blank"><img src="https://img.shields.io/github/stars/org?style=social"/></a>

[![Velog's GitHub stats](https://velog-readme-stats.vercel.app/api?name=chaeyoonl&color=dark)](https://velog-readme-stats.vercel.app/api/redirect?name=chaeyoonl)
