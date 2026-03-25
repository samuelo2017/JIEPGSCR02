{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Comparativa: Eclipse Z7 vs Nexys A7-100T\
\
## 1. Eclipse Z7\
\
### Descripci\'f3n General\
La **Eclipse Z7** es una placa de desarrollo basada en FPGA (Field Programmable Gate Array) de Digilent, que combina la flexibilidad de un FPGA Xilinx Zynq con la facilidad de uso de la plataforma Arduino.\
\
### Caracter\'edsticas Principales\
- **FPGA**: Xilinx Zynq-7020 (Z-7020)\
- **Arquitectura**: Sistema en Chip (SoC) que integra un procesador ARM Cortex-A9 de doble n\'facleo con l\'f3gica programable FPGA\
- **Factor de forma**: Compatible con shields Arduino\
- **Memoria**: \
  - 512 MB DDR3 SDRAM\
  - 32 MB Quad-SPI Flash\
  - MicroSD slot\
- **Conectividad**:\
  - Ethernet 10/100\
  - USB OTG\
  - USB-JTAG para programaci\'f3n\
  - Puerto microUSB para alimentaci\'f3n y comunicaci\'f3n serial\
- **Perif\'e9ricos**:\
  - 4 LEDs\
  - 2 pulsadores\
  - 2 switches\
  - 8 canales PWM\
  - Conectores Pmod para expansi\'f3n\
\
### Aplicaciones T\'edpicas\
- Prototipado r\'e1pido con FPGA\
- Sistemas embebidos con procesador ARM\
- Procesamiento de se\'f1ales digitales (DSP)\
- Control industrial\
- Visi\'f3n por computadora\
- Aplicaciones de Internet de las Cosas (IoT)\
\
### Herramientas de Desarrollo\
- **Vivado Design Suite**: Para dise\'f1o de hardware FPGA\
- **Vitis (antiguo SDK)**: Para desarrollo de software en ARM\
- **Arduino IDE**: Opcional para programaci\'f3n simplificada\
- **Xilinx SDK**: Para aplicaciones embebidas\
\
### Ventajas\
- \uc0\u9989  Combina procesador ARM con FPGA en un solo chip\
- \uc0\u9989  Compatibilidad con shields Arduino\
- \uc0\u9989  Buena relaci\'f3n costo-beneficio\
- \uc0\u9989  Amplia documentaci\'f3n y comunidad\
- \uc0\u9989  Excelente para proyectos h\'edbridos hardware/software\
\
### Desventajas\
- \uc0\u10060  Curva de aprendizaje pronunciada para FPGA\
- \uc0\u10060  Requiere licencia Vivado (versi\'f3n gratuita limitada)\
- \uc0\u10060  Consumo de energ\'eda moderado\
\
---\
\
## 2. Nexys A7-100T\
\
### Descripci\'f3n General\
La **Nexys A7-100T** es una placa de desarrollo FPGA de Digilent, dise\'f1ada espec\'edficamente para aplicaciones de l\'f3gica programable, basada en el chip Xilinx Artix-7.\
\
### Caracter\'edsticas Principales\
- **FPGA**: Xilinx Artix-7 (XC7A100T)\
- **L\'f3gica**: 101,440 celdas l\'f3gicas, 4,860 slices\
- **Factor de forma**: Dise\'f1o standalone con m\'faltiples perif\'e9ricos integrados\
- **Memoria**:\
  - 128 MB DDR3 SDRAM\
  - 16 MB Quad-SPI Flash\
  - MicroSD slot\
- **Conectividad**:\
  - USB-JTAG para programaci\'f3n\
  - USB-UART para comunicaci\'f3n serial\
  - Ethernet 10/100\
  - USB host\
- **Perif\'e9ricos**:\
  - 16 switches\
  - 16 LEDs\
  - 5 pulsadores\
  - Pantalla OLED (128x32)\
  - 4 displays de 7 segmentos\
  - 4 conectores Pmod\
  - Conector VGA\
  - Audio jack\
  - Conector para micr\'f3fono\
\
### Aplicaciones T\'edpicas\
- Educaci\'f3n en dise\'f1o digital\
- Prototipado de sistemas digitales\
- Procesamiento de se\'f1ales\
- Dise\'f1o de procesadores personalizados\
- Sistemas de adquisici\'f3n de datos\
- Implementaci\'f3n de algoritmos en hardware\
\
### Herramientas de Desarrollo\
- **Vivado Design Suite**: Dise\'f1o y programaci\'f3n FPGA\
- **Vitis**: Para desarrollo de software (cuando se usa MicroBlaze)\
- **Digilent Adept**: Utilidad para programaci\'f3n y control\
\
### Ventajas\
- \uc0\u9989  Gran cantidad de perif\'e9ricos integrados\
- \uc0\u9989  Ideal para aprendizaje de FPGA\
- \uc0\u9989  Excelente documentaci\'f3n educativa\
- \uc0\u9989  Mayor cantidad de recursos l\'f3gicos que la Z7\
- \uc0\u9989  Perfecta para proyectos puramente digitales\
\
### Desventajas\
- \uc0\u10060  No tiene procesador ARM integrado\
- \uc0\u10060  Requiere dise\'f1o de procesador soft-core (MicroBlaze) para aplicaciones embebidas\
- \uc0\u10060  Mayor precio que modelos similares\
- \uc0\u10060  Sin compatibilidad directa con Arduino\
\
---\
\
## Comparativa Directa\
\
| Caracter\'edstica | Eclipse Z7 | Nexys A7-100T |\
|----------------|------------|---------------|\
| **FPGA** | Zynq-7020 (SoC) | Artix-7 (XC7A100T) |\
| **Celdas L\'f3gicas** | 85,000 | 101,440 |\
| **Procesador** | ARM Cortex-A9 dual-core | Requiere MicroBlaze (soft-core) |\
| **Memoria RAM** | 512 MB DDR3 | 128 MB DDR3 |\
| **Memoria Flash** | 32 MB | 16 MB |\
| **Switches** | 2 | 16 |\
| **LEDs** | 4 | 16 |\
| **Pulsadores** | 2 | 5 |\
| **Pmod Conectores** | 4 | 4 |\
| **Ethernet** | S\'ed | S\'ed |\
| **VGA** | No | S\'ed |\
| **Audio** | No | S\'ed |\
| **OLED** | No | S\'ed |\
| **Arduino Compatible** | S\'ed | No |\
| **Uso Principal** | Sistemas embebidos h\'edbridos | Educaci\'f3n y dise\'f1o digital |\
\
---\
\
## Recomendaciones de Uso\
\
### Elige Eclipse Z7 si:\
- Necesitas un sistema embebido con procesador ARM\
- Quieres combinar hardware personalizado con software de alto nivel\
- Planeas usar shields Arduino para expansi\'f3n r\'e1pida\
- Desarrollas aplicaciones de IoT o control industrial\
\
### Elige Nexys A7-100T si:\
- Te enfocas en aprendizaje de dise\'f1o digital con FPGA\
- Necesitas muchos perif\'e9ricos para proyectos educativos\
- Desarrollas procesadores personalizados o sistemas puramente digitales\
- Trabajas en procesamiento de se\'f1ales o video\
\
---\
\
## Recursos \'datiles\
\
### Documentaci\'f3n Oficial\
- **Eclipse Z7**: [Digilent Reference](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/start)\
- **Nexys A7-100T**: [Digilent Reference](https://reference.digilentinc.com/reference/programmable-logic/nexys-a7/start)\
\
### Comunidades\
- Digilent Forums\
- Reddit r/FPGA\
- Xilinx Community Forums\
- Hackster.io\
\
### Herramientas\
- **Xilinx Vivado**: [Descarga gratuita](https://www.xilinx.com/products/design-tools/vivado.html)\
- **Digilent Adept**: [Sistema de programaci\'f3n](https://digilent.com/reference/software/adept/start)\
\
---\
\
## Conclusi\'f3n\
\
Ambas placas son excelentes opciones en el ecosistema de desarrollo con FPGA, pero est\'e1n orientadas a diferentes necesidades:\
\
La **Eclipse Z7** destaca por su arquitectura h\'edbrida (procesador + FPGA), siendo ideal para sistemas embebidos complejos donde se requiere tanto software como hardware personalizado.\
\
La **Nexys A7-100T** es una plataforma educativa completa con abundantes perif\'e9ricos, perfecta para el aprendizaje de dise\'f1o digital y prototipado de sistemas puramente basados en hardware.\
\
La elecci\'f3n entre ambas depender\'e1 fundamentalmente del tipo de proyecto que se desee desarrollar y del enfoque requerido entre hardware y software.\
\
---\
\
*\'daltima actualizaci\'f3n: Marzo 2026*}