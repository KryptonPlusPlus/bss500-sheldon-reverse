# Componentes do Amplificador

Lista de Materiais para a PCB bss500ap do amplificador Sheldon BSS500.

> **Note:** Esta lista abrange apenas a PCB do amplificador. Os valores dos componentes e as suas respectivas *footprints* baseiam-se em um projeto obtido por engenharia reversa e podem diferir do projeto original de fábrica.

## Capacitores

| Referência | Quantidade  | Valor | Footprint |
|---|---:|---|---|
| C79 | 1 | 33pF | `Capacitor_THT:C_Disc_D7.5mm_W5.0mm_P7.50mm` |
| C80, C81 | 2 | 33pF | `Capacitor_THT:C_Disc_D4.3mm_W1.9mm_P5.00mm` |
| C82 | 1 | 10uF 50V | `Capacitor_THT:C_Radial_D6.3mm_H11.0mm_P2.50mm` |
| C83, C86, C88, C99 | 4 | 100nF 100V | `Capacitor_THT:C_Rect_L10.0mm_W4.0mm_P7.50mm_MKS4` |
| C84, C85 | 2 | 47uF 25V | `Capacitor_THT:CP_Radial_D5.0mm_P2.50mm` |
| C87 | 1 | 220pF | `Capacitor_THT:C_Disc_D6.0mm_W2.5mm_P5.00mm` |
| C89 | 1 | 100uF 16V | `Capacitor_THT:CP_Radial_D5.0mm_P2.50mm` |
| C90, C92 | 2 | 4700uF 50V | `Capacitor_THT:CP_Radial_D18.0mm_P7.50mm` |
| C91 | 1 | 100uF 16V | `Capacitor_THT:CP_Radial_D10.0mm_P5.00mm` |

## Diodos

| Referência | Quantidade  | Valor | Footprint
|---|---:|---|---|
| D1, D2 | 2 | D | `Diode_THT:D_T-1_P5.08mm_Horizontal` |
| D3 | 1 | 1N4001 | `Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal` |
| D4, D5, D6, D7 | 4 | 1N5408 | `Diode_THT:D_DO-201AE_P5.08mm_Vertical_KathodeUp` |
| Z1, Z2 | 2 | D_Zener | `Diode_THT:D_DO-34_SOD68_P7.62mm_Horizontal` |

## fusíveis

| Referência | Quantidade  | Valor | Footprint |
|---|---:|---|---|
| F1, F2 | 2 | Fuse 250V 3A | `Fuse:Fuseholder_Cylinder-5x20mm_Schurter_0031_8201_Horizontal_Open` |

## Circuitos integrados

| Referência | Quantidade  | Valor | Footprint |
|---|---:|---|---|
| IC10 | 1 | TL071 | `Package_TO_SOT_THT:TO-3P-3_Vertical` |

## Transistores

| Referência | Quantidade  | Valor | Footprint |
|---|---:|---|---|
| Q1 | 1 | a1962 | `Package_TO_SOT_THT:TO-3P-3_Vertical` |
| Q2, Q6 | 2 | BC640 | `Package_TO_SOT_THT:TO-92_Inline_Wide` |
| Q3, Q5 | 2 | bc639 | `Package_TO_SOT_THT:TO-92_Inline_Wide` |
| Q4 | 1 | c5242 | `Package_TO_SOT_THT:TO-3P-3_Vertical` |

## Resistores

| Referência | Quantidade | Valor | Footprint |
|---|---:|---|---|
| R79, R84 | 2 | 22kR 1/8W | `Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal` |
| R80 | 1 | 2.2R 1/8W | `Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal` |
| R81 | 1 | 6.8kR 1/8W | `Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal` |
| R82 | 1 | 390R 1/8W | `Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal` |
| R83, R85, R87, R90 | 4 | 1kR 1/8W | `Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal` |
| R86, R89 | 2 | 610R 0.5W | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal` |
| R88, R91 | 2 | 330R 1/8W | `Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal` |
| R92 | 1 | 10R 0.5W | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal` |
| R93, R94 | 2 | 0.47R 5W | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P15.24mm_Horizontal` |
| R95, R96 | 2 | 680R 0.5W | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal` |
| R97 | 1 | 4.1kR 1/8W | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal` |