



# Arduino-Matrix-Eyes ![arduinoThumb](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/1e80c0a0-27bd-4b96-a6e1-88ef7eca9098) ![C++-Logo wine](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/882aa901-1f05-43d5-9574-60db4e7b6537)
![Dotmtrix_Cascade](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/3d10a97a-748b-4a50-bb93-089b6e61ba68)


## INITIALE()
![eye1](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/19a7e124-1af5-41d3-8f7e-f5c98f870b03)![eye1m](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/618d3c63-5457-4e37-aa8d-31714565e029)


```C
 void INITIALE()
 {
int Pos1[8] = {90, 90, 90, 90, 90, 90, 90, 90};
int Pos2[8] = {0, 0, 0, 0, 0, 0, 0, 0};
int Pos3[8] = {90, 90, 90, 90, 90, 90, 90, 90};
int Pos4[8] = {180, 180, 180, 180, 180, 180, 180, 180};
int Pos5[8] = {90, 90, 90, 90, 90, 90, 90, 90};
int Pos6[8] = {0, 0, 0, 0, 0, 0, 0, 0};
int Pos7[8] = {90, 90, 90, 90, 90, 90, 90, 90};
int Pos8[8] = {180, 180, 180, 180, 180, 180, 180, 180};

for (int s = 0; s < 8; s++) {
  servo1.write(Pos1[s]);
  servo2.write(Pos2[s]);
  servo3.write(Pos3[s]);
  servo4.write(Pos4[s]);
  servo5.write(Pos5[s]);
  servo6.write(Pos6[s]);
  servo7.write(Pos7[s]);
  servo8.write(Pos8[s]);
  delay(200);
    Serial.println(s);
  }
 }
```
## DANCE1()
![eye2](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/2b9ab9f5-bf69-4fc9-a2c1-0eb8647c13ed)![eye2m](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/49c11df1-dba5-4108-8ab4-b90d3e26cc24)


 ```C
 void DANCE1()
 {
int Pos1[8] = {90, 90, 45, 135, 135, 45, 45, 90};
int Pos2[8] = {0, 0, 0, 0, 0, 0, 0, 0};
int Pos3[8] = {90, 45, 45, 135, 135, 45, 45, 90};
int Pos4[8] = {180, 180, 180, 180, 180, 180, 180, 180};
int Pos5[8] = {90, 45, 45, 135, 135, 45, 45, 90};
int Pos6[8] = {0, 0, 0, 0, 0, 0, 0, 0};
int Pos7[8] = {90, 45, 45, 135, 135, 45, 45, 90};
int Pos8[8] = {180, 180, 180, 180, 180, 180, 180, 180};

for (int s = 0; s < 8; s++) {
  servo1.write(Pos1[s]);
  servo2.write(Pos2[s]);
  servo3.write(Pos3[s]);
  servo4.write(Pos4[s]);
  servo5.write(Pos5[s]);
  servo6.write(Pos6[s]);
  servo7.write(Pos7[s]);
  servo8.write(Pos8[s]);
  delay(200);
    Serial.println(s);
  }
 }
```
