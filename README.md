# **Vyzařování teplotního zdroje, černé těleso, Stefan-Boltzmannův zákon, Planckův zákon, Wienův posouvací zákon**

## **1. Vyzařování teplotního zdroje**

- **Vyzařování teplotního zdroje** vzniká přeměnou **tepelné energie** na elektromagnetické záření.
- Atomy a molekuly teplotního zdroje obsahují **nabité částice** (elektrony, protony), které při vzájemných **kinetických interakcích** oscilují.
- **Oscilace dipólů** způsobují vznik elektrických (E) a magnetických (H) polí, která vedou k emisi **fotonů**.
- Záření teplotního zdroje je tedy funkcí jeho **teploty** a je distribuováno v různých **vlnových délkách**.

**Typy vyzařování**:

1. **Absolutně černé těleso** – ideální model s maximální emisivitou ( $\varepsilon = 1 $).
2. **Reálná tělesa** – mají nižší emisivitu ( $\varepsilon < 1 $) a závisí na povrchu a materiálu tělesa.

## **2. Absolutně černé těleso**

- **Definice**: Těleso, které **pohltí** všechno dopadající záření, bez ohledu na vlnovou délku.
  - Ideální model v termodynamice a optice.
- **Spektrální pohltivost** $\alpha*\lambda $: Pro absolutně černé těleso $\alpha*\lambda = 1 $pro všechny vlnové délky.
- **Realizace**: V praxi lze přiblížit „černou dutinou“ s malým otvorem (ztracené záření uvnitř se prakticky neodrazí ven).

## **3. Stefan-Boltzmannův zákon**

- Tento zákon určuje **celkovou intenzitu záření** teplotního zdroje:
  $$
  H_{0e} = \sigma T^4
  $$
  - ** $\sigma $**: Stefan-Boltzmannova konstanta, $5,670 \times 10^{-8} \, W \cdot m^{-2} \cdot K^{-4} $.
  - **T**: Absolutní teplota tělesa (v Kelvinech).
- **Význam**:
  - Popisuje, že celková energie vyzařovaná povrchem tělesa **roste s mocninou čtvrté teploty**.
  - Platí pro **absolutně černé těleso**, ale lze jej upravit pro **nečerná tělesa** zavedením emisivity $\varepsilon $:
    $$
    H_e = \varepsilon \sigma T^4, \quad \varepsilon \in (0, 1)
    $$

## **4. Wienův posouvací zákon**

- Tento zákon popisuje **posun maxima intenzity záření** k **kratším vlnovým délkám** s rostoucí teplotou:
  $$
  \lambda_{\text{max}} T = b
  $$
  - ** $\lambda\_{\text{max}} $**: Vlnová délka, při které je intenzita vyzařování největší.
  - **b**: Wienova konstanta, $2,898 \times 10^{-3} \, m \cdot K $.
- **Význam**:
  - S rostoucí teplotou se **maximum vyzařování posouvá** do oblasti **krátkých vlnových délek** (např. viditelné světlo → ultrafialové záření).
  - Použití: Měření teploty hvězd a dalších zářivých objektů.

## **5. Planckův zákon**

- Planckův zákon popisuje **spektrální rozložení záření** absolutně černého tělesa:
  $$
  H_{0\lambda} = \frac{c_1}{\lambda^5} \frac{1}{e^{c_2 / \lambda T} - 1}
  $$
  - ** $c_1 $**: První radiační konstanta.
  - ** $c_2 $**: Druhá radiační konstanta.
  - ** $\lambda $**: Vlnová délka záření.
  - ** $T $**: Absolutní teplota tělesa.
- **Fyzikální význam**:
  - Zákon spojil **Rayleigh-Jeansův** a **Wienův zákon** a překonal problém **ultrafialové katastrofy**.
  - Předpokládá, že energie záření je **kvantována**:
    $$
    E = h \nu
    $$
        - ** $h $**: Planckova konstanta, $6,626 \times 10^{-34} \, J \cdot s $.
        - ** $\nu $**: Frekvence záření.
- **Důsledek**:
  - Planckův zákon umožnil rozvoj **kvantové fyziky**.
  - Popisuje celé spektrum záření absolutně černého tělesa.

## **6. Porovnání zákonů a shrnutí**

| **Zákon**              | **Rovnice**                                                                | **Význam**                        |
| ---------------------- | -------------------------------------------------------------------------- | --------------------------------- |
| **Stefan-Boltzmannův** | $H\_{0e} = \sigma T^4 $                                                    | Celková intenzita záření.         |
| **Wienův posouvací**   | $\lambda\_{\text{max}} T = b $                                             | Maximum záření závisí na teplotě. |
| **Planckův zákon**     | $H\_{0\lambda} = \frac{c_1}{\lambda^5} \frac{1}{e^{c_2 / \lambda T} - 1} $ | Spektrální rozložení vyzařování.  |

## **7. Praktické aplikace**

1. **Termografie**: Měření teploty objektů na základě vyzařovaného tepelného záření.
2. **Astrofyzika**: Studium hvězd a kosmických objektů díky Wienovu zákonu.
3. **Žárovky a světelné zdroje**: Charakterizace teplotních a neteplotních zdrojů.
4. **Průmyslová měření**: Kalibrace teploty v metalurgii, sklárnách apod.

# **Fotometrické a radiometrické veličiny a jednotky, šedé těleso, emisivita, citlivost lidského oka**

## **1. Radiometrické veličiny a jednotky**

Radiometrie se zabývá měřením **elektromagnetického záření** v celém spektru (UV, viditelné světlo, IR). Popisuje fyzikální vlastnosti záření bez ohledu na citlivost lidského oka.

### **Hlavní radiometrické veličiny**:

1. **Zářivý tok** ( $\Phi $)

   - Celkový výkon záření emitovaný zdrojem (integrální veličina).
   - Jednotka: **watt (W)**.
   - $\Phi = \int H*{\lambda} \, d\lambda $, kde $H*{\lambda} $je spektrální hustota zářivého toku.

2. **Zářivost** ( $I_e $)

   - Množství zářivého toku na jednotku **prostorového úhlu** ve směru vyzařování:
     $$
     I_e = \frac{\mathrm{d}\Phi}{\mathrm{d}\Omega} \quad [\mathrm{W \cdot sr^{-1}}].
     $$

3. **Zářivá hustota** ( $L_e $)

   - Zářivý tok vyzařovaný z jednotkové plochy do jednotkového prostorového úhlu:
     $$
     L_e = \frac{\mathrm{d}^2\Phi}{\mathrm{d}A \cdot \mathrm{d}\Omega \cdot \cos\theta} \quad [\mathrm{W \cdot m^{-2} \cdot sr^{-1}}].
     $$
   - Zohledňuje **úhel dopadu záření** ( $\theta $) na plochu $A $.

4. **Osvětlení** ( $E $)
   - Zářivý tok dopadající na jednotku plochy:
     $$
     E = \frac{\mathrm{d}\Phi}{\mathrm{d}A} \quad [\mathrm{W \cdot m^{-2}}].
     $$

## **2. Fotometrické veličiny a jednotky**

Fotometrie je podmnožinou radiometrie, která bere v úvahu **citlivost lidského oka** na různé vlnové délky záření (360–780 nm). Měření je přizpůsobeno viditelnému světlu.

### **Hlavní fotometrické veličiny**:

1. **Světelný tok** ( $\Phi_v $)

   - Celkové množství světla vyzařované zdrojem. Vypočítává se pomocí **světelné účinnosti**:
     $$
     \Phi_v = \int_{360 \, \mathrm{nm}}^{780 \, \mathrm{nm}} K(\lambda) H_{\lambda} \, d\lambda.
     $$
   - $K(\lambda) $: Světelná účinnost.
   - Jednotka: **lumen (lm)**.

2. **Svítivost** ( $I $)

   - Světelný tok na jednotku prostorového úhlu:
     $$
     I = \frac{\Phi_v}{\Omega} \quad [\mathrm{cd = lm \cdot sr^{-1}}].
     $$
   - Jednotka: **kandela (cd)**.

3. **Osvětlení** ( $E $)

   - Světelný tok dopadající na jednotkovou plochu:
     $$
     E = \frac{\Phi_v}{A} \quad [\mathrm{lx = lm \cdot m^{-2}}].
     $$
   - Jednotka: **lux (lx)**.

4. **Jas** ( $L $)
   - Svítivost vyzařovaná z jednotkové plochy v daném směru:
     $$
     L = \frac{\mathrm{d}I}{\mathrm{d}A \cdot \cos\theta} \quad [\mathrm{cd \cdot m^{-2}}].
     $$

## **3. Šedé těleso**

Šedé těleso je **reálné těleso**, které nevyzařuje maximální možný výkon (jako absolutně černé těleso). Má konstantní **emisivitu** ( $\varepsilon $) menší než 1 pro všechny vlnové délky.

- **Emisivita** je poměr skutečného záření tělesa k záření absolutně černého tělesa:
  $$
  \varepsilon = \frac{H_e}{H_0}, \quad \varepsilon \in (0, 1).
  $$

### **Typy emisivity**:

1. **Integrální emisivita** – celkové vyzařování.
2. **Spektrální emisivita** – emisivita závislá na vlnové délce.

**Reálné povrchy**:

- Matný černý lak má vysokou emisivitu ( $\varepsilon \approx 0,98 $),
- Leštěné kovy mají nízkou emisivitu ( $\varepsilon \approx 0,1-0,3 $).

## **4. Citlivost lidského oka**

Citlivost lidského oka na záření není rovnoměrná v celém spektru:

- **Maximální citlivost**: $\lambda = 555 \, \mathrm{nm} $(zelená oblast) za denního světla – **fotopické vidění**.
- Při nízké úrovni osvětlení (noční vidění) je citlivost posunuta k **modré oblasti** ( $\lambda \approx 507 \, \mathrm{nm} $) – **skotopické vidění**.

### **Světelná účinnost**:

- **Fotopická účinnost**: Zrakový vjem je nejefektivnější při 555 nm. Maximální účinnost $K_v = 683 \, \mathrm{lm \cdot W^{-1}} $.
- **Relativní světelná účinnost** $K(\lambda) $vyjadřuje schopnost oka vnímat světlo na různých vlnových délkách.

## **5. Shrnutí veličin a jejich jednotek**

| **Typ veličiny**         | **Radiometrická jednotka** | **Fotometrická jednotka** |
| ------------------------ | -------------------------- | ------------------------- |
| Zářivý tok ( $\Phi $)    | W (watt)                   | lm (lumen)                |
| Zářivost ( $I_e $)       | W·sr $^{-1} $              | cd (kandela)              |
| Zářivá hustota ( $L_e $) | W·m $^{-2} $·sr $^{-1} $   | cd·m $^{-2} $             |
| Osvětlení ( $E $)        | W·m $^{-2} $               | lx (lux)                  |

## **6. Praktické aplikace**

1. **Průmyslová měření**:

   - Měření osvětlení pracovních ploch (luxmetry).
   - Vyhodnocování emisivity materiálů v **tepelné technice**.

2. **Osvětlení**:

   - Navrhování umělého osvětlení (kanceláře, továrny, ulice).

3. **Tepelné ztráty**:

   - Identifikace míst s vysokou emisivitou pro úniky tepla.

4. **Fotografické a optické systémy**:

   - Správné nastavení expozice a měření intenzity světla.

5. **Citlivost oka**:
   - Design displejů a obrazovek s ohledem na citlivost lidského oka.

# **Teplotní zdroje záření – žárovky, halogenové žárovky, výbojové zdroje záření**

## **1. Teplotní zdroje záření – žárovky**

### **1.1 Vakuové žárovky**

- **Princip**: Vlákno ze **wolframu (W)** je zahříváno elektrickým proudem, až začne vyzařovat viditelné světlo (**tepelné záření**).
- **Konstrukce**:
  - Vlákno: **průměr 0,05–0,2 mm**.
  - Baňka: Vyrobena ze **sodno-vápenatého skla**.
  - Prostup baňkou: **kovarové dráty** (Fe-Ni-Co s nízkým koeficientem teplotní roztažnosti).
  - Patice: Edisonův závit (E14, E27) nebo **bajonetové patice**.
- **Vlastnosti**:
  - Fungují při **nižších teplotách**.
  - Relativně **nízká účinnost** (většina energie je přeměněna na teplo, ne na světlo).

### **1.2 Halogenové žárovky**

- **Vylepšená verze žárovek** s delší životností a vyšší účinností.
- **Princip**:
  - Halogenový cyklus: Halogenové plyny (např. $\text{WI}\_2, \text{WBr}\_2 $) reagují s odpařeným wolframem a vracejí ho zpět na vlákno.
  - Vlákno může dosahovat **vyšší teploty** → více světla a delší životnost.
- **Konstrukce**:
  - Vlákno: **wolframové**.
  - Baňka: Vyrobena z **křemenného skla**, které odolává vyšším teplotám.
  - Provozní podmínky: **tlak** 1,2 MPa a teplota až **400 °C**.
  - Prostup baňkou: Stejně jako u vakuových žárovek – **Fe-Ni-Co dráty**.
  - Patice: Kolíkové (např. G4, G6.35).
- **Výhody**:
  - Vyšší účinnost a delší životnost než vakuové žárovky.
  - Kompaktnější rozměry.

## **2. Výbojové zdroje záření**

Výbojky jsou založeny na emisi světla při **průchodu elektrického proudu plynem** nebo párou.

### **2.1 Rtuťové výbojky (Hg)**

- Obsahují rtuť, která při elektrickém výboji vyzařuje **ultrafialové záření**.
- Typy:
  1. **Nízkotlaké** ( $< 100 \, \text{kPa} $) – používají se ve fluorescenčních lampách.
  2. **Středotlaké** ( $100 \, \text{kPa} - 1 \, \text{MPa} $).
  3. **Vysokotlaké** ( $> 1 \, \text{MPa} $) – vysoký výkon a jas.

### **2.2 Sodíkové výbojky (Na)**

- Používají **sodíkové páry** pro tvorbu světla.
- Typy:
  1. **Nízkotlaké sodíkové výbojky** – velmi vysoká účinnost, emitují **žluté monochromatické světlo**.
  2. **Vysokotlaké sodíkové výbojky** – širší spektrum světla, **oranžovo-žluté světlo**, často využívané pro veřejné osvětlení.

### **2.3 Halogenidové výbojky**

- **Vysokotlaké** výbojky obsahující směs **halogenidů kovů** (např. sodíku, skandia, india).
- Výhody:
  - Vysoká účinnost a **lepší barevné podání** než rtuťové a sodíkové výbojky.
- Použití:
  - Osvětlení stadionů, průmyslových hal, výstavní osvětlení.

### **2.4 Zářivky (fluorescenční lampy)**

- Jsou kombinací **primárního a sekundárního zdroje světla**.

1. **Primární zdroj**: **Nízkotlaký rtuťový výboj** produkuje ultrafialové záření.
2. **Sekundární zdroj**: **Luminofory** na vnitřní straně baňky přeměňují UV záření na viditelné světlo (Stokesův posun).

- **Princip**: Elektrony v luminoforech absorbují UV záření (excitační energie $E_1 $) a emitují světlo při návratu do základního stavu ( $E_2 $).
- **Výhody**:
  - Vysoká účinnost.
  - Stabilní světelný výstup při vysokých frekvencích (40–50 kHz).

## **Shrnutí vlastností teplotních a výbojových zdrojů**

| **Typ zdroje**           | **Princip**                      | **Výhody**                       | **Nevýhody**                        |
| ------------------------ | -------------------------------- | -------------------------------- | ----------------------------------- |
| **Vakuové žárovky**      | Zahřátí wolframového vlákna      | Jednoduchá konstrukce            | Nízká účinnost, krátká životnost    |
| **Halogenové žárovky**   | Halogenový cyklus, vyšší teploty | Vyšší účinnost, delší životnost  | Vyšší teplota povrchu               |
| **Rtuťové výbojky**      | Výboj v rtuťových parách         | Vysoký výkon                     | Škodlivé pro životní prostředí (Hg) |
| **Sodíkové výbojky**     | Výboj v sodíkových parách        | Vysoká účinnost                  | Monochromatické světlo (nízkotlaké) |
| **Halogenidové výbojky** | Výboj s příměsí halogenidů kovů  | Dobré barevné podání             | Vyšší pořizovací náklady            |
| **Zářivky**              | UV záření přeměněné luminofory   | Vysoká účinnost, stabilní světlo | Nutnost elektronického předřadníku  |

### **Praktické aplikace:**

1. **Vakuové a halogenové žárovky** – domácí osvětlení, dekorativní účely.
2. **Rtuťové a sodíkové výbojky** – veřejné osvětlení, průmyslové haly.
3. **Halogenidové výbojky** – stadiony, výstavní prostory.
4. **Zářivky** – kanceláře, školy, obchody.

# **Zdroje záření LED**

## **1. Základní princip fungování LED**

**LED (Light Emitting Diode)** je polovodičová součástka, která vyzařuje světlo na základě **elektroluminiscence** – procesu, při kterém dochází k **radiativní rekombinaci elektronů a děr** v polovodičovém materiálu.

### **Princip činnosti**:

1.  **Rekombinace nosičů náboje**:
    - Při aplikaci napětí v propustném směru se elektrony přesouvají z vodivostního pásu do valenčního pásu.
    - Při rekombinaci s dírami dochází k uvolnění **energie ve formě fotonu**.
2.  **Barva světla** závisí na **šířce zakázaného pásu** polovodiče (band gap).
    - Energie fotonu ( $E $) je dána vztahem:
      $$
      E = h \cdot f = \frac{h \cdot c}{\lambda}
      $$
           kde $h $je Planckova konstanta, $f $frekvence, $c $rychlost světla a $\lambda $vlnová délka.

## **2. Materiály pro výrobu LED**

Barva světla závisí na použitém polovodičovém materiálu:

| **Materiál**              | **Barva**    | **Vlnová délka (nm)** | **Napětí (V)** |
| ------------------------- | ------------ | --------------------- | -------------- |
| **SiC, GaN**              | Modrá        | 450                   | 3,6            |
| **GaP**                   | Zelená       | 565                   | 2,2            |
| **GaAsPN**                | Žlutá        | 580                   | 2,1            |
| **GaAsP, GaP:ZnO**        | Červená      | 635                   | 2,0            |
| **GaAsSi**                | Infračervená | 800–950               | 1,5            |
| **SiC, GaN + luminofory** | Bílá         | 420–700               | 3,6            |

## **3. Vlastnosti LED**

### **Výhody LED**:

1. **Vysoká účinnost**: Přeměna elektrické energie na světelnou energii dosahuje desítek procent.
2. **Barevná čistota**: Spektrální barva závisí pouze na polovodičovém materiálu → není potřeba barevný filtr.
3. **Miniaturizace**: Malé rozměry a nízké zástavbové nároky.
4. **Rychlá odezva**: LED diody se rozsvěcují velmi rychle (vhodné pro frekvenční aplikace).
5. **Regulace intenzity**: Jednoduché stmívání pomocí **pulzně-šířkové modulace** (PWM) nebo změnou proudu.
6. **Dlouhá životnost**: 30 000–50 000 hodin provozu.
7. **Mechanická odolnost**: Nemají pohyblivé části → vysoká odolnost vůči otřesům a vibracím.

### **Nevýhody LED**:

1. **Závislost na teplotě**: Při vysokých teplotách klesá účinnost.
2. **Citlivost na napětí**: Překročení maximálního napětí vede k poškození LED.
3. **Nutnost chlazení**: Vysokovýkonné LED vyžadují účinné chlazení pro zabránění tepelného poškození.

## **4. Spektrální charakteristika LED**

- LED diody mají relativně úzké spektrum vyzařovaného světla, jehož šířka je definována jako **FWHM (Full Width at Half Maximum)**.
- Barva záření se přímo odvíjí od použitého materiálu a odpovídající energetické mezery.

## **5. Směrová charakteristika LED**

- **Směrovost** LED záření je dána konstrukcí čipu a optickými členy (např. čočky, reflektory).
- LED diody lze vyrobit s různou směrovostí, od úzkých kuželů (bodové osvětlení) až po široké vyzařovací charakteristiky (difuzní světlo).

## **6. Aplikace LED**

1. **Indikátory** – kontrolky na přístrojích, elektronice.
2. **Vnitřní osvětlení** – domácnosti, kanceláře, průmyslové objekty.
3. **Veřejné osvětlení** – pouliční lampy, parkovací osvětlení.
4. **LED pásky** – dekorativní a funkční osvětlení.
5. **Světla vozidel** – světlomety, brzdová a směrová světla.
6. **Datová komunikace** – optické sítě využívající infračervené LED diody.

## **7. Elektro-optické charakteristiky LED**

LED diody mají specifickou závislost **světelného výkonu** a **dopředného proudu**.

- **Zvýšení proudu** zvyšuje světelný výkon, ale pouze do určitého limitu.
- Vyšší proud vede k **zahřívání čipu**, což snižuje účinnost.

## **8. Praktické výhody a budoucnost LED**

- LED technologie se stala dominantní v osvětlení díky:
  - Energetické úspornosti.
  - Možnosti regulace intenzity a barvy.
  - Dlouhé životnosti a spolehlivosti.
- Budoucí vývoj směřuje k:
  - Zvýšení účinnosti na úrovně přes 60–70 %.
  - Zlepšení odvodu tepla a chlazení.
  - Rozšíření aplikací v **biologickém osvětlení** (fytotrony, světla pro rostliny).

## **Shrnutí**

| **Vlastnost**        | **LED**                                           |
| -------------------- | ------------------------------------------------- |
| **Princip činnosti** | Elektroluminiscence – rekombinace elektronů a děr |
| **Účinnost**         | Desítky procent                                   |
| **Barva světla**     | Závisí na materiálu (spektrální barva)            |
| **Životnost**        | 30 000–50 000 hodin                               |
| **Regulace**         | Snadné stmívání (PWM, změna proudu)               |
| **Aplikace**         | Indikátory, osvětlení, komunikace, automobily     |

# **Lasery a laserové diody**

## **1. Základní princip laserů**

- **Laser** = _Light Amplification by Stimulated Emission of Radiation_
- Princip fungování spočívá ve **stimulované emisi záření**, kdy foton iniciuje emisi dalšího fotonu se stejnou energií, fází a směrem.
- **Hlavní kroky**:
  1.  **Absorpce**: Elektrony absorbují energii a přecházejí do excitovaného stavu.
  2.  **Spontánní emise**: Návrat do základního stavu uvolní foton náhodného směru.
  3.  **Stimulovaná emise**: Excitovaný elektron je „donucen“ uvolnit foton při návratu do základního stavu. Výsledný foton je **koherentní** (stejná fáze, směr a frekvence).

## **2. Typy laserů podle aktivního prostředí**

1. **Pevnolátkové lasery**:

   - Aktivní prostředí tvořeno krystaly nebo sklem dopovaným ionty.
   - Příklady:
     - **Rubínový laser**: Aktivní prostředí **Cr $^3+ $** v safírové matrici ( $\lambda = 0,6943 \, \mu m $).
     - **Neodymový YAG laser**: Aktivní prostředí **Nd $^3+ $** v yttrium-aluminium-granátu ( $\lambda = 1,062 \, \mu m $).

2. **Plynové lasery**:

   - Aktivní prostředí tvořeno plyny.
   - Příklady:
     - **CO $\_2 $laser**: Aktivní plyn CO $\_2 $, N $\_2 $a He ( $\lambda = 10,6 \, \mu m $).
     - **He-Ne laser**: Helium-neon směs ( $\lambda = 0,6328 \, \mu m $).

3. **Polovodičové lasery (Laserové diody)**:

   - Založeny na P-N přechodu polovodiče, kde dochází k **elektroluminiscenci**.
   - Příklady materiálů a aplikací:  
     | **Materiál** | **Vlnová délka (nm)** | **Aplikace** |  
     |---------------|----------------------|----------------------------------|  
     | **GaAs** | 635 | Ukazovátka, zaměřovače |  
     | **GaN** | 375–473 | Biomedicína, fluorescence |  
     | **InP** | 940–1555 | Telekomunikace, optické čerpání |

4. **Kapalinové lasery**:
   - Aktivní médium tvořeno **organickými barvivy** (tunovatelné lasery).
5. **Plazmatické lasery**:
   - Aktivní prostředí tvoří ionizované plazma.

## **3. Typy laserů podle činnosti**

- **Kontinuální (CW – Continuous Wave)**: Stabilní výstupní výkon.
- **Pulzní (P)**: Emise světla v krátkých, intenzivních pulsech.

## **4. Laserové diody**

**Laserové diody** jsou polovodičové lasery, které emitují koherentní světlo pomocí **P-N přechodu**.

### **Typy laserových diod**:

1. **Hranově vyzařující lasery (EEL)**:
   - Světlo emituje z hrany polovodičového čipu.
   - Vysoká účinnost, velký rozsah výkonů (od mW až po kW).
   - Nesymetrická divergence svazku (např. 30 × 20°).
2. **Plošně vyzařující lasery (VCSEL)**:
   - Světlo emituje kolmo k povrchu čipu.
   - Nižší výkony, ale homogennější svazek.

### **Vlastnosti laserových diod**:

- **Široký rozsah vlnových délek** (od UV po IR).
- **Vysoká účinnost**: Přeměna elektrické energie na světlo.
- **Nutnost chlazení**: Vysokovýkonné diody vyžadují aktivní chlazení.

### **Aplikace laserových diod**:

- **Optické čtečky**: CD, DVD.
- **Telekomunikace**: Vysílání signálů přes optická vlákna.
- **Biomedicína**: Laserová terapie, chirurgické nástroje.
- **Ukazovátka a zaměřovače**: Přenosné lasery.

## **5. Parametry laserového svazku**

1. **Profil svazku**:
   - **Gaussovský svazek**: Nejčastější profil intenzity.
2. **Divergence svazku**:
   - Udává rozbíhavost svazku.
3. **Rezonátory**:
   - Optické dutiny, které udržují světlo mezi zrcadly a umožňují zesílení.
   - Typy: **stabilní rezonátory** (zrcadla b, c, d, e).

## **6. Vláknové lasery**

- Aktivní prostředí tvořeno optickým vláknem dopovaným ionty vzácných zemin (např. Nd, Yb).
- **Výhody**:
  - Vysoká účinnost.
  - Možnost přenosu svazku na dlouhé vzdálenosti.
  - Kompaktní provedení.
- **Aplikace**: Průmyslové řezání, sváření, telekomunikace.

## **7. Shrnutí vlastností laserů**

| **Typ laseru**             | **Aktivní médium**      | **Vlnová délka**  | **Aplikace**                    |
| -------------------------- | ----------------------- | ----------------- | ------------------------------- |
| **Pevnolátkový**           | Nd:YAG, rubín           | 694–1064 nm       | Řezání, značení, medicína       |
| **Plynový**                | CO $\_2 $, He-Ne        | 10,6 µm, 632,8 nm | Průmysl, laboratoře, metrologie |
| **Polovodičový (diodový)** | GaAs, GaN, InP          | 375–1555 nm       | Telekomunikace, optické disky   |
| **Kapalinový (barvivový)** | Organická barviva       | 400–1000 nm       | Spektroskopie, věda             |
| **Vláknový**               | Dopované optické vlákno | 1064 nm           | Řezání, telekomunikace, sváření |

## **8. Praktické aplikace laserů**

1. **Průmyslové zpracování materiálů**: Řezání, svařování, značení.
2. **Optické komunikace**: Přenos dat přes optická vlákna.
3. **Medicína**: Laserová chirurgie, terapie, dermatologie.
4. **Věda a výzkum**: Spektroskopie, optické experimenty.
5. **Spotřební elektronika**: CD/DVD čtečky, laserové projektory.

# **Vláknová optika, typy vláken, parametry, disperze, ohnuté a kuželové vlákno, svazky vláken**

## **1. Základní princip vláknové optiky**

- Vláknová optika využívá **světlovody** pro přenos světla pomocí **totálního odrazu** na rozhraní mezi jádrem a obálkou vlákna.
- Využití: **datová komunikace**, osvětlení, zobrazovací aplikace.

## **2. Typy optických vláken**

### **2.1 Podle indexu lomu**:

1. **Diskrétní vlákna (step-index)**:

   - Jádro má **konstantní index lomu**, obálka nižší index lomu.
   - Typické pro **jednomodová** vlákna.

2. **Gradientní vlákna (GRIN)**:
   - Index lomu jádra se **plynule mění** směrem k obálce.
   - Redukuje modovou disperzi a umožňuje lepší přenos dat.

### **2.2 Podle počtu módů**:

1. **Jednomodová vlákna (SMF – Single Mode Fiber)**:

   - Světlo se šíří pouze **jedním módem**.
   - Průměr jádra: **8 µm**.
   - Pracovní vlnová délka: **1300 nm** nebo **1550 nm**.
   - Parametry:
     - Útlum: **1,5 dB/km** při 1300 nm.
     - Numerická apertura (NA): **0,15**.
   - **Výhody**: Vysoká šířka pásma, nízká disperze → vhodné pro **dlouhé vzdálenosti**.

2. **Vícemodová vlákna (MMF – Multimode Fiber)**:
   - Světlo se šíří **více módy**.
   - Průměr jádra: **50 µm**.
   - Pracovní vlnová délka: **850 nm** a **1300 nm**.
   - Parametry:
     - Útlum: **3 dB/km** při 850 nm.
     - Numerická apertura (NA): **0,23**.
   - **Výhody**: Nižší náklady, vhodné pro **krátké vzdálenosti**.

### **2.3 Speciální vlákna**:

1. **Kapalinová vlákna**:

   - Jádro vyplněno kapalinou.
   - Použití: **osvětlovací aplikace**.

2. **Celoplastová vlákna (POF – Plastic Optical Fiber)**:

   - Jádro i obálka z plastu.
   - Vysoký útlum, levné, vhodné pro **krátké spoje**.

3. **PCS vlákna (Plastic-Cladded Silica)**:
   - Jádro: **tavený křemen**, obálka: plast.
   - Vyšší útlum než skleněná vlákna.

## **3. Parametry optických vláken**

### **3.1 Útlum**:

- Ztráta energie při průchodu světla vláknem.
- Definice:
  $$
  A = 10 \cdot \log \left( \frac{P_{\text{in}}}{P_{\text{out}}} \right) \, \text{[dB]}
  $$
- Hlavní příčiny:
  - **Absorpce**: Pohlcení světla materiálem.
  - **Rozptyl**: V důsledku nerovnoměrnosti materiálu.

### **3.2 Disperze**:

- Rozptyl optického signálu v časové doméně. Omezuje šířku pásma a rychlost přenosu dat.

#### **Typy disperze**:

1. **Modová disperze** (intermodální):

   - Vícemodová vlákna – různé módy mají odlišné dráhy.

2. **Materiálová disperze** (intramodální):

   - Závislost rychlosti světla na vlnové délce v materiálu.

3. **Chromatická disperze**:

   - Kombinace materiálové disperze a vlivů zdroje světla.

4. **Polarizační disperze**:
   - Různé polarizační složky světla se šíří různou rychlostí.

## **4. Ohnuté a kuželové vlákno**

### **Ohnuté vlákno**:

- Ohnutí optického vlákna způsobuje **ztráty světla** v důsledku **úniku světla** mimo vlákno.
- Důsledky:
  - Zvýšený útlum.
  - Omezení použitelnosti na krátké vzdálenosti.

### **Kuželové vlákno**:

- Optické vlákno s **proměnným průměrem jádra**.
- Použití:
  - Lepší propojení vláken s různými parametry.
  - Redukce disperze v určitých aplikacích.

## **5. Svazky vláken**

Optická vlákna lze uspořádat do **svazků** pro přenos světla nebo obrazu.

### **Typy svazků**:

1. **Uspořádané svazky**:

   - Vlákna jsou **pevně uspořádána**.
   - Použití: Přenos obrazu (endoskopy, optické senzory).

2. **Neuspořádané svazky**:
   - Vlákna jsou **náhodně uspořádána**.
   - Použití: **Osvětlovací aplikace** (světelná distribuce).

### **Pohyblivé a pevné svazky**:

- **Pohyblivé svazky** umožňují ohyb a přizpůsobení.
- **Pevné svazky** mají stabilní geometrii.

## **6. Shrnutí hlavních parametrů vláken**

| **Parametr**          | **Jednomodové**          | **Vícemodové (GRIN)**    |
| --------------------- | ------------------------ | ------------------------ |
| Průměr jádra          | 8 µm                     | 50 µm                    |
| Numerická apertura NA | 0,15                     | 0,23                     |
| Útlum @ 1300 nm       | 1,5 dB/km                | 1,5 dB/km                |
| Šířka pásma           | Nekonečná (teoreticky)   | 600–1300 MHz/km          |
| Použití               | Dlouhé vzdálenosti, data | Krátké vzdálenosti, sítě |

## **7. Praktické aplikace vláknové optiky**

1. **Telekomunikace**: Přenos dat na dlouhé vzdálenosti (internet, telefonie).
2. **Senzory**: Měření tlaku, teploty, vibrací (vláknové senzory).
3. **Zobrazování**: Endoskopy a mikroskopy.
4. **Osvětlení**: Světelná vlákna pro dekorativní a průmyslové účely.

# **Detektory s vnějším fotoefektem**

## **1. Základní princip vnějšího fotoefektu**

- **Vnější fotoefekt** je jev, při kterém **dopadající fotony** uvolní elektrony z povrchu materiálu (nejčastěji kovu).
- Energie fotonu $E_f $je dána vztahem:

  $$
  E_f = h \cdot f = \frac{h \cdot c}{\lambda},
  $$

  kde:

  - $h $– Planckova konstanta,
  - $f $– frekvence záření,
  - $c $– rychlost světla,
  - $\lambda $– vlnová délka.

- Aby došlo k uvolnění elektronu, musí být energie fotonu větší než **výstupní práce** $W_v $daného materiálu:
  $$
  E_f > W_v.
  $$
- Uvolněné elektrony se nazývají **fotoelektrony** a mohou být detekovány a zesilovány.

## **2. Hlavní typy detektorů s vnějším fotoefektem**

### **2.1 Fotonka (Phototube)**

- **Princip**:
  - Foton dopadá na fotokatodu, která emituje fotoelektrony.
  - Fotoelektrony jsou **ur accelerated (urychleny)** k anodě elektrickým polem a detekovány jako proud.
- **Vlastnosti**:
  - Vysoká citlivost.
  - Stabilní výkon při změnách teploty.
  - Široký **dynamický rozsah**.
  - Velká citlivá plocha pro dopadající záření.
- **Aplikace**:
  - Chemická a lékařská analýza.
  - Laserová měření.

### **2.2 Fotonásobič (Photomultiplier Tube – PMT)**

- **Princip**:
  1.  Foton dopadne na **fotokatodu**, která uvolní fotoelektron.
  2.  Fotoelektron je **urychlen** k dynodám pod vysokým napětím.
  3.  Při nárazu na dynodu dochází k **sekundární emisi elektronů** → násobení proudu.
  4.  Výsledkem je **zesílený proud elektronů** na anodě.
- **Typy fotonásobičů**:
  - **Head-on type**: Optická osa je kolmá na povrch katody.
  - **Side-on type**: Světlo dopadá z boku na katodu.
- **Vlastnosti**:
  - Extrémně vysoká citlivost (zesílení až $10^6 $).
  - Široký spektrální rozsah (UV až viditelné světlo).
  - Rychlá odezva.
- **Nevýhody**:
  - Vyžadují vysoké napětí (1000 V).
  - Citlivé na vnější elektromagnetické rušení.
- **Aplikace**:
  - Detekce slabého světla (např. hvězdná pozorování, scintilační detektory).
  - Spektroskopie.

### **2.3 Mikrokanálová destička (Microchannel Plate – MCP)**

- **Princip**:
  - Destička obsahuje velké množství **mikrokanálků** s vodivými stěnami.
  - Foton uvolní fotoelektron, který je urychlen **elektrickým polem** podél mikrokanálků.
  - Nárazy elektronu na stěny kanálků způsobují **sekundární emisi elektronů** → zesílení signálu.
- **Vlastnosti**:
  - Kompaktní provedení.
  - Vysoké zesílení signálu (až $10^5 $).
  - Rychlá odezva – vhodné pro detekci **rychlých pulzů**.
- **Aplikace**:
  - Noční vidění.
  - Detekce ultrafialového záření (UV spektroskopie).
  - Systémy pro zobrazování slabého světla.

## **3. Obecné charakteristiky detektorů záření**

1. **Spektrální citlivost**: Citlivost detektoru na různé vlnové délky záření.
2. **Relativní spektrální citlivost**: Poměr citlivosti k maximální hodnotě citlivosti.
3. **Integrální citlivost**: Celková citlivost detektoru v širokém spektru záření.
4. **Prahová citlivost**: Minimální intenzita záření, kterou detektor dokáže zaznamenat.
5. **Směrová charakteristika**: Závislost citlivosti detektoru na úhlu dopadajícího záření.

## **4. Srovnání detektorů s vnějším fotoefektem**

| **Typ detektoru**          | **Citlivost**   | **Zesílení**          | **Aplikace**                          |
| -------------------------- | --------------- | --------------------- | ------------------------------------- |
| **Fotonka**                | Vysoká          | Žádné (přímá detekce) | Chemie, lékařská měření               |
| **Fotonásobič (PMT)**      | Extrémně vysoká | Až $10^6 $            | Detekce slabého světla, spektroskopie |
| **Mikrokanálová destička** | Vysoká          | Až $10^5 $            | Noční vidění, UV detekce              |

## **5. Praktické aplikace detektorů s vnějším fotoefektem**

1. **Spektroskopie**: Analýza světelného spektra ve vědeckém výzkumu.
2. **Astronomie**: Detekce slabého světla z vesmírných objektů.
3. **Noční vidění**: Použití mikrokanálových destiček pro zesílení slabého světla.
4. **Laserová měření**: Precizní detekce a měření laserového záření.
5. **Analytická chemie**: Fotometrické analýzy v laboratořích.

# **Detektory s vnitřním fotoefektem**

## **1. Základní princip vnitřního fotoefektu**

- **Vnitřní fotoefekt** je jev, při kterém foton dopadající na materiál dodá dostatek energie elektronu ve valenčním pásu, aby překonal **zakázaný pás** a přešel do vodivostního pásu.
- Vytvářejí se **elektron-děrové páry**, které jsou následně detekovány jako změna elektrických vlastností (odpor, proud, napětí).
- Základní materiály: polovodiče jako **Si (křemík), Ge (germanium), GaAs (gallium arsenid), InGaAs**.

## **2. Typy detektorů s vnitřním fotoefektem**

### **2.1 Fotorezistor (Fotoodpor)**

- **Princip**: Po absorpci fotonu dojde ke **snížení elektrického odporu** materiálu.
- **Rovnice odporu**:
  $$
  R = \rho \frac{l}{S},
  $$
  kde $\rho $je měrný odpor, $l $délka dráhy, $S $průřez kontaktu.
- **Materiály**:
  - **CdS (sulfid kadmia)**: citlivost kolem **520 nm** (podobná lidskému oku).
  - **CdSe (selenid kadmia)**: citlivost na **690 nm**.
  - Pro IR oblast: **CdTe (830 nm), InSb (1,6 µm)**.
- **Nevýhody**:
  - Vysoká teplotní závislost.
  - Nelinearita změny odporu.
  - Pomalá odezva (v desítkách ms).
- **Použití**: Starší aplikace, dnes nahrazovány fotodiodami a fototranzistory.

### **2.2 Fotodioda**

- **Princip**: Dopadající foton vytvoří **elektron-děrový pár** v oblasti **PN přechodu**.
- **Režimy zapojení**:
  1.  **Fotovoltaický režim** (bez vnějšího napětí):
      - Fotodioda funguje jako **zdroj napětí** (fotočlánek).
      - Pracuje ve 4. kvadrantu voltampérové charakteristiky.
  2.  **Fotovodivostní režim** (s vnějším napětím):
      - Zvýšení **závěrného proudu** úměrně osvětlení.
      - Vhodné pro měření s **rychlou odezvou** a vysokým dynamickým rozsahem.
- **Materiály**:
  - **Si (křemík)**: UV, viditelné světlo, IR do 900 nm.
  - **Ge (germanium)**: IR do **1,5 µm**.
  - **InGaAs**: širší IR oblast.
- **Výhody**:
  - Vysoká rychlost (až stovky GHz).
  - Lineární odezva na intenzitu záření.
- **Aplikace**: Snímače světla, měřicí přístroje, optické komunikace.

### **2.3 Segmentové diody**

- **Popis**: Fotodiody rozdělené na více nezávislých citlivých oblastí v jednom pouzdře.
- **Princip**: Rozložení signálů (proudů) z jednotlivých segmentů umožňuje určení pozice osvětlené oblasti.
- **Použití**:
  - **Kvadrantové diody**: Pro určování **středu osvětlení** v osách X a Y.
  - Měření pozice světelného bodu.

### **2.4 Fototranzistor**

- **Princip**: Záření dopadající na **bázi** tranzistoru řídí propustnost **PN přechodu** → ovlivňuje kolektorový proud.
- **Vlastnosti**:
  - Citlivější než fotodiody díky **zesilovacímu efektu**.
  - Delší doba odezvy (v desítkách µs).
- **Použití**:
  - **Spínací prvky**: Optočleny (kombinace LED a fototranzistoru).
  - Snímače záření.

### **2.5 PSD detektor (Position Sensitive Detector)**

- **Popis**: Velkoplošná fotodioda s nanesenou odporovou vrstvou.
- **Princip**: Rozložení **fotoproudu** do vývodů umožňuje určit pozici ozářeného místa.
- **Použití**:
  - **Optická triangulace**: Bezdotykové měření vzdálenosti.
  - Přesné určování polohy pomocí laserových diod.

## **3. Šum v detektorech s vnitřním fotoefektem**

1. **Fotonový šum**: Fluktuace v toku dopadajících fotonů.
2. **Fotoelektrický šum**: Náhodnost generování nosičů náboje.
3. **Zesilovací šum**: Fluktuace zesíleného signálu.
4. **Elektrický šum obvodů**: Šum součástek detektoru.
5. **Šum temného proudu**: Proud způsobený tepelnou excitací bez osvětlení.

## **4. Srovnání detektorů s vnitřním fotoefektem**

| **Typ detektoru**  | **Rychlost** | **Citlivost**       | **Aplikace**                       |
| ------------------ | ------------ | ------------------- | ---------------------------------- |
| **Fotorezistor**   | Pomalejší    | Nižší               | Starší měřicí a světelné snímače   |
| **Fotodioda**      | Velmi rychlá | Vysoká              | Měření světla, optické komunikace  |
| **Fototranzistor** | Střední      | Vyšší než fotodioda | Optočleny, spínací aplikace        |
| **PSD detektor**   | Rychlá       | Velká plocha        | Optická triangulace, měření polohy |

## **5. Praktické aplikace detektorů s vnitřním fotoefektem**

1. **Optické komunikace**: Přenos dat pomocí světelných signálů (fotodiody).
2. **Měření vzdálenosti**: Laserové triangulační senzory s PSD detektory.
3. **Bezkontaktní spínače**: Optočleny s fototranzistory.
4. **Osvětlení a senzory světla**: Automatické stmívání, měření intenzity světla.
5. **Průmyslová kontrola**: Systémy detekce světelných značek.

# **Aplikace v měření – vzdálenosti, rozměru, teploty**

## **1. Měření vzdálenosti**

Optická měření vzdálenosti využívají principy **laserové triangulace** a optických metod.

### **1.1 Laserová triangulace**

- **Princip**:
  - Laserový paprsek je zaměřen na povrch objektu.
  - Odražené světlo je zachyceno **senzorem** (např. CCD nebo PSD detektorem).
  - Z **polohy odraženého bodu** na senzoru se geometricky určí vzdálenost objektu (optická osa senzoru je skloněna k laserovému paprsku).
- **Metody triangulace**:
  - **Bodové měření** – měření jednotlivého bodu.
  - **Profilové měření** – skenování profilu objektu pomocí 2D snímače.
  - **Rozmítání** – promítání vzoru pro zjištění povrchových nerovností.

**Použití**:

- Kontrola kvality výrobků.
- Měření vzdáleností v průmyslu a logistice.

### **1.2 Optické mikrometry**

- Optické mikrometry využívají stínový nebo **závěrkový efekt** k měření rozměrů objektů.
- **Typy mikrometrů**:
  1.  **Analogové optické mikrometry** – výstupem je analogový signál.
  2.  **Digitální optické mikrometry** – poskytují digitální hodnoty pro vyšší přesnost.
- **Princip měření**:
  - Světelný paprsek je vysílán a zachycen detektorem. Překážka (měřený objekt) částečně blokuje paprsek a vytváří stín.
  - Míra blokace světla odpovídá velikosti měřeného objektu.

**Použití**:

- Měření průměrů, tlouštěk a pozic součástek.
- Rychlá a přesná měření v průmyslových aplikacích.

## **2. Měření rozměru**

Optické metody umožňují bezkontaktní a přesné měření rozměrů různých objektů.

### **2.1 Laserové profilometry**

- Použití laserových paprsků k měření **3D profilu** objektu.
- **Princip**:
  - Laser skenuje povrch objektu a vytváří **výškový profil**.
  - Odražené světlo je detekováno senzory (např. CCD kamery).

**Použití**:

- Kontrola plochých nebo válcových povrchů.
- Detekce vad na povrchu materiálů.

### **2.2 Optické závory**

- **Princip**:
  - Světelný zdroj a detektor jsou umístěny proti sobě.
  - Přerušení světelného paprsku objektům způsobí změnu signálu detektoru.
- **Použití**:
  - Detekce přítomnosti objektů.
  - Kontrola průchozích rozměrů (např. průměr tyčí, rychlost pohybu).

## **3. Měření teploty**

Pro měření teploty se používají bezkontaktní **pyrometry** a **termokamery**, které detekují tepelnou radiaci.

### **3.1 Pyrometrie**

- **Pyrometr**: Přístroj pro **bezkontaktní měření teploty** na základě záření objektu.
- **Typy pyrometrů**:
  1.  **Monochromatické pyrometry** – měří intenzitu záření na jedné vlnové délce.
  2.  **Pásmové pyrometry** – měří intenzitu v určitém spektrálním pásmu.
  3.  **Celkové (úhrnné) pyrometry** – měří celkové tepelné záření objektu.

**Princip**:

- Intenzita vyzařování je úměrná teplotě podle **Stefan-Boltzmannova zákona**.
- Teplota se určí porovnáním s referenční hodnotou nebo kalibrovaným zářením.

**Použití**:

- Měření teploty tavenin v hutnictví.
- Kontrola teploty povrchů ve výrobě.

### **3.2 Termokamery**

- Termokamery snímají **infračervené záření** emitované objekty a převádějí ho na **teplotní mapu**.
- **Senzory**:
  - **Mikrobolometry** – detektory citlivé na změnu teploty.
  - **Ge optika** – čočky pro infračervené záření.

**Použití**:

- Diagnostika tepelných ztrát budov.
- Kontrola přehřívání elektrických zařízení.
- Lékařské zobrazování (detekce zánětů).

## **4. Praktické aplikace v průmyslu**

1. **Kontrola kvality**:
   - Laserová triangulace pro měření povrchových vad a rozměrů součástek.
2. **Monitorování teploty**:
   - Termokamery a pyrometry pro zajištění bezpečnosti výrobních procesů.
3. **Automatizace výrobních linek**:
   - Optické závory a mikrometry pro rychlou detekci a kontrolu součástek.
4. **Bezkontaktní měření vzdálenosti**:
   - Laserové senzory pro logistiku a skladování.

## **Shrnutí hlavních aplikací a metod**

| **Měřená veličina** | **Metoda**             | **Technologie**               | **Aplikace**                             |
| ------------------- | ---------------------- | ----------------------------- | ---------------------------------------- |
| **Vzdálenost**      | Laserová triangulace   | Laserové diody, PSD detektory | Robotika, kontrola pozic, měření profilů |
| **Rozměr**          | Optické mikrometry     | Optické závory, CCD snímače   | Kontrola součástek, měření průměrů       |
| **Teplota**         | Pyrometry, termokamery | IR senzory, mikrobolometry    | Hutnictví, stavebnictví, medicína        |
