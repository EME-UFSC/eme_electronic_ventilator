## Documentation for dealing with stm32f373rc

---

### Datasheet:
https://www.st.com/resource/en/datasheet/stm32f373rc.pdf

---

### Reference Manual:
https://www.st.com/resource/en/reference_manual/dm00041563-stm32f37xxx-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf

---

### Hall description:
https://www.st.com/resource/en/user_manual/dm00122016-description-of-stm32f3-hal-and-low-layer-drivers-stmicroelectronics.pdf

---

### Memory boot mode:
https://www.st.com/resource/en/user_manual/dm00122016-description-of-stm32f3-hal-and-low-layer-drivers-stmicroelectronics.pdf

Details:
 - It uses Pattern2 (p.22):
   - Boot0 = 1 (**pin**), nBoot1= 1 (**bit**),
 - Resources used: (p.96-98)
   - RCC (with HSE) -> 16MHz -> ok
   - RAM -> 5KB -> ok
   - System Memory -> 8 KB -> ok
   - IWDG -> max if enabled -> ok
 - DFU, USART1 or USART2 are functional -> ok
 
 ---
 
 ### SDADC:
 https://www.st.com/resource/en/application_note/dm00070480-getting-started-with-stm32f37x38x-sdadc-sigmadelta-adc-stmicroelectronics.pdf
 
 ---
