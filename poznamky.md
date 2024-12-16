### **Podrobné poznámky k tématu: Vyzařování teplotního zdroje, černé těleso, Stefan-Boltzmannův zákon, Planckův zákon, Wienův posouvací zákon**

---

## **1. Vyzařování teplotního zdroje**
- **Vyzařování teplotního zdroje** vzniká přeměnou **tepelné energie** na elektromagnetické záření.
- Atomy a molekuly teplotního zdroje obsahují **nabité částice** (elektrony, protony), které při vzájemných **kinetických interakcích** oscilují.
- **Oscilace dipólů** způsobují vznik elektrických (E) a magnetických (H) polí, která vedou k emisi **fotonů**.
- Záření teplotního zdroje je tedy funkcí jeho **teploty** a je distribuováno v různých **vlnových délkách**.

**Typy vyzařování**:
1. **Absolutně černé těleso** – ideální model s maximální emisivitou (\( \varepsilon = 1 \)).
2. **Reálná tělesa** – mají nižší emisivitu (\( \varepsilon < 1 \)) a závisí na povrchu a materiálu tělesa.

---

## **2. Absolutně černé těleso**
- **Definice**: Těleso, které **pohltí** všechno dopadající záření, bez ohledu na vlnovou délku.
  - Ideální model v termodynamice a optice.
- **Spektrální pohltivost** \( \alpha_\lambda \): Pro absolutně černé těleso \( \alpha_\lambda = 1 \) pro všechny vlnové délky.
- **Realizace**: V praxi lze přiblížit „černou dutinou“ s malým otvorem (ztracené záření uvnitř se prakticky neodrazí ven).

---

## **3. Stefan-Boltzmannův zákon**
- Tento zákon určuje **celkovou intenzitu záření** teplotního zdroje:
  \[
  H_{0e} = \sigma T^4
  \]
  - **\(\sigma\)**: Stefan-Boltzmannova konstanta, \( 5,670 \times 10^{-8} \, W \cdot m^{-2} \cdot K^{-4} \).
  - **T**: Absolutní teplota tělesa (v Kelvinech).
- **Význam**: 
  - Popisuje, že celková energie vyzařovaná povrchem tělesa **roste s mocninou čtvrté teploty**.
  - Platí pro **absolutně černé těleso**, ale lze jej upravit pro **nečerná tělesa** zavedením emisivity \( \varepsilon \):
    \[
    H_e = \varepsilon \sigma T^4, \quad \varepsilon \in (0, 1)
    \]

---

## **4. Wienův posouvací zákon**
- Tento zákon popisuje **posun maxima intenzity záření** k **kratším vlnovým délkám** s rostoucí teplotou:
  \[
  \lambda_{\text{max}} T = b
  \]
  - **\(\lambda_{\text{max}}\)**: Vlnová délka, při které je intenzita vyzařování největší.
  - **b**: Wienova konstanta, \( 2,898 \times 10^{-3} \, m \cdot K \).
- **Význam**:
  - S rostoucí teplotou se **maximum vyzařování posouvá** do oblasti **krátkých vlnových délek** (např. viditelné světlo → ultrafialové záření).
  - Použití: Měření teploty hvězd a dalších zářivých objektů.

---

## **5. Planckův zákon**
- Planckův zákon popisuje **spektrální rozložení záření** absolutně černého tělesa:
  \[
  H_{0\lambda} = \frac{c_1}{\lambda^5} \frac{1}{e^{c_2 / \lambda T} - 1}
  \]
  - **\(c_1\)**: První radiační konstanta.
  - **\(c_2\)**: Druhá radiační konstanta.
  - **\(\lambda\)**: Vlnová délka záření.
  - **\(T\)**: Absolutní teplota tělesa.
- **Fyzikální význam**:
  - Zákon spojil **Rayleigh-Jeansův** a **Wienův zákon** a překonal problém **ultrafialové katastrofy**.
  - Předpokládá, že energie záření je **kvantována**:
    \[
    E = h \nu
    \]
    - **\(h\)**: Planckova konstanta, \( 6,626 \times 10^{-34} \, J \cdot s \).
    - **\(\nu\)**: Frekvence záření.
- **Důsledek**:
  - Planckův zákon umožnil rozvoj **kvantové fyziky**.
  - Popisuje celé spektrum záření absolutně černého tělesa.

---

## **6. Porovnání zákonů a shrnutí**
| **Zákon**                 | **Rovnice**                                        | **Význam**                              |
|---------------------------|---------------------------------------------------|----------------------------------------|
| **Stefan-Boltzmannův**    | \( H_{0e} = \sigma T^4 \)                         | Celková intenzita záření.              |
| **Wienův posouvací**      | \( \lambda_{\text{max}} T = b \)                  | Maximum záření závisí na teplotě.      |
| **Planckův zákon**        | \( H_{0\lambda} = \frac{c_1}{\lambda^5} \frac{1}{e^{c_2 / \lambda T} - 1} \) | Spektrální rozložení vyzařování.       |

---

## **7. Praktické aplikace**
1. **Termografie**: Měření teploty objektů na základě vyzařovaného tepelného záření.
2. **Astrofyzika**: Studium hvězd a kosmických objektů díky Wienovu zákonu.
3. **Žárovky a světelné zdroje**: Charakterizace teplotních a neteplotních zdrojů.
4. **Průmyslová měření**: Kalibrace teploty v metalurgii, sklárnách apod.
