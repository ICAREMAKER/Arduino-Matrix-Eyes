



# Arduino-Matrix-Eyes ![arduinoThumb](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/1e80c0a0-27bd-4b96-a6e1-88ef7eca9098) ![C++-Logo wine](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/882aa901-1f05-43d5-9574-60db4e7b6537)
![Dotmtrix_Cascade](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/3d10a97a-748b-4a50-bb93-089b6e61ba68)


## Yeux fermés
![eye1](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/19a7e124-1af5-41d3-8f7e-f5c98f870b03)![eye1m](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/618d3c63-5457-4e37-aa8d-31714565e029)

#### °Oeil gauche
```C
void OeilGauche1() {
	byte image1_Oeil_Gauche[] = {
   B00000010,  // oeil gauche
   B00110001,
   B01100001,
   B01100001,
   B00110001,
   B00110001,
   B00000000
};
  for (int i = 0; i < 8; i++)  { lc.setRow(0,i,image1_Oeil_Gauche[i]); }
}
```
#### °Oeil droit
 ```C
void OeilDroit1() {
	byte image1_Oeil_Droit[] = {
   B00000000,  // oeil droit
   B00110001,
   B00110001,
   B01100001,
   B01100001,
   B00110001,
   B00110001,
   B00000010
};
  for (int i = 0; i < 8; i++) { lc.setRow(0,i,image1_Oeil_Droit[i]); }
}
```
## Yeux ouverts
![eye2](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/2b9ab9f5-bf69-4fc9-a2c1-0eb8647c13ed)![eye2m](https://github.com/ICAREMAKER/Arduino-Matrix-Eyes/assets/107696317/49c11df1-dba5-4108-8ab4-b90d3e26cc24)

#### °Oeil gauche
 ```C
 void OeilGauche2() {
	byte image2_Oeil_Gauche[] = {
   B00000010,  // oeil gauche
   B01111001,
   B10000101,
   B10110101,
   B10110101,
   B10000101,
   B01111001,
   B00000000
};
  for (int i = 0; i < 8; i++) { lc.setRow(1,i,image2_Oeil_Gauche[i]); }
}
```
#### °Oeil droit
 ```C
void OeilDroit2() {
	byte image2_Oeil_Droit[] = {
   B00000000,  // oeil droit
   B01111001,
   B10000101,
   B10110101,
   B10110101,
   B10000101,
   B01111001,
   B00000010
};
  for (int i = 0; i < 8; i++) { lc.setRow(1,i,image2_Oeil_Droit[i]); }
}
```
