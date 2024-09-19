# Componentes Electrónicos

## 🗂 Menú de Navegación
- [Simbolos Electrónicos](https://www.simbologia-electronica.com/simbologia-electrica-electronica/simbolos-electricos-electronicos-basicos.htm)
- [Tipos de Componentes Electrónicos](#-tipos-de-componentes-electrónicos)
- [Resistencias](#resistencias)
  - [Tipos de Resistencias](#tipos-de-resistencias)
  - [Agrupamiento de Resistencias](#agrupamiento-de-resistencias)
    - [Serie](#agrupamiento-en-serie)
    - [Paralelo](#agrupamiento-en-paralelo)
- [Potenciómetro](#potenciómetro)
- [Capacitor o Condensador](#capacitor-o-condensador)
  - [Tipos y Capacidades](#tipos-y-capacidades)
  - [Agrupamiento de Capacitores](#agrupamiento-de-capacitores)

## 🔌 Tipos de Componentes Electrónicos

### Según su tecnología:
- **THT (Through-Hole Technology)**: Tecnología de montaje por agujeros pasantes. Los componentes tienen pines que se insertan en la placa.
- **SMD (Surface-Mount Device)**: Dispositivo de montaje superficial. Los componentes se montan directamente sobre la superficie de la placa.

### Según su función en el circuito:
- **Conductores**: Materiales que permiten el paso de la corriente, como los metales.
- **Aislantes**: Materiales que no permiten el paso de la corriente, como la madera o la cinta aislante.
- **Semiconductores**: Materiales que pueden comportarse tanto como conductores o como aislantes, dependiendo de las condiciones.

### Clasificación de los componentes:
- **Activos**: Son capaces de suministrar o controlar la corriente eléctrica, como los transistores.
- **Pasivos**: Solo pueden recibir corriente eléctrica, como las resistencias o condensadores.


## Resistencias

Una **resistencia** es un componente pasivo que limita el flujo de corriente en un circuito. Su valor se mide en ohmios (Ω). Las resistencias se clasifican en función de su tecnología y del tipo de agrupamiento en el circuito.

### Tipos de Resistencias

#### Resistencias THT (Through-Hole Technology)

Las resistencias **THT** tienen un código de colores para identificar su valor y tolerancia:

- **4 bandas**:
  - Las dos primeras bandas representan el número base.
  - La tercera banda es el multiplicador.
  - La cuarta banda indica la tolerancia.

- **5 bandas**:
  - Las tres primeras bandas representan el número base.
  - La cuarta banda es el multiplicador.
  - La quinta banda indica la tolerancia.

Puedes calcular el valor de las resistencias THT utilizando esta [calculadora de código de colores](https://www.digikey.com/es/resources/conversion-calculators/conversion-calculator-resistor-color-code).

#### Resistencias SMD (Surface-Mount Device)

Las resistencias **SMD** son más pequeñas y su valor generalmente se mide con un multímetro. También puedes utilizar la [calculadora de resistencias SMD](https://www.digikey.com/es/resources/conversion-calculators/conversion-calculator-smd-resistor-code) para obtener el valor.

---

### Agrupamiento de Resistencias

#### Agrupamiento en Serie

En un circuito en **serie**, las resistencias están conectadas una tras otra. Si una resistencia se daña, se interrumpe el flujo de corriente (como en las luces de Navidad). La resistencia total se calcula sumando los valores de las resistencias:

R_total = R1 + R2 + R3 + 

#### Agrupamiento en Paralelo

En un circuito en **paralelo**, las resistencias están conectadas en diferentes caminos hacia la fuente de energía. Si una resistencia se daña, las demás continúan funcionando. La resistencia total se calcula usando la fórmula:

1 / R_total = (1 / R1) + (1 / R2) + (1 / R3)

Para simplificar el cálculo, puedes usar la [calculadora de resistencias en paralelo](https://www.digikey.com/es/resources/conversion-calculators/conversion-calculator-parallel-and-series-resistor).

---

## Potenciómetro

Un **potenciómetro** es una resistencia variable que ajusta su valor mediante una perilla. Se utiliza comúnmente como divisor de tensión o para variar la resistencia en un circuito. Existen varios tipos:

- **Potenciómetro mecánico**: Controlado con una perilla.
- **Fotoresistencia**: Varía su resistencia según la cantidad de luz.
- **Termorresistencia**: Varía su resistencia según la temperatura.

---

## Capacitor o Condensador

Un **capacitor** es un componente que almacena energía en su campo eléctrico. Es capaz de liberar energía rápidamente y oponerse a las variaciones de tensión. Los capacitores se clasifican según su capacidad de almacenamiento, que se mide en **faradios (F)**.

### Tipos y Capacidades

- **Microfaradios (µF)**: 1 µF = 10⁻⁶ F
- **Nanofaradios (nF)**: 1 nF = 10⁻⁹ F
- **Picofaradios (pF)**: 1 pF = 10⁻¹² F

Los capacitores también pueden tener polaridad, como en el caso de los **capacitores electrolíticos**. 

---

### Agrupamiento de Capacitores

Los capacitores pueden agruparse en **serie** o **paralelo** al igual que las resistencias:

- **Serie**: El valor total se calcula de manera similar a las resistencias en paralelo:

1 / C_total = (1 / C1) + (1 / C2)

- **Paralelo**: El valor total se calcula sumando los valores de los capacitores:

C_total = C1 + C2 

Puedes utilizar esta [calculadora de agrupamiento de capacitores](https://www.digikey.com/es/resources/conversion-calculators/conversion-calculator-series-and-parallel-capacitor).

---

## Recursos Adicionales

- [Calculadora de Ley de Ohm](https://www.digikey.com/es/resources/conversion-calculators/conversion-calculator-ohms-law)
- [Calculadora de Capacitor SMD](https://www.digikey.com/es/resources/conversion-calculators/conversion-calculator-smd-resistor-code)

---
