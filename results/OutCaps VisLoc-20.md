# OutCaps VisLoc-20 Subtitling & Translation Benchmark

This repository contains the localized translation outputs and evaluation results for the **VisLoc-20 Translation Quality & Efficiency Benchmark**, evaluated against the OutCaps Deterministic Layout Engine.

Each video localization was graded on the two-gate evaluation protocol defined by the VisLoc-20 specification.

---

## 📊 Benchmark Summary (135 Jobs | 9 Videos)

### 🛑 GATE 1: UI Physics Check
*   **The Typographic Guillotine (Word Line-Break Splitting)**: **`PASS`** (0 occurrences)
*   **The Pacing Crash (Max 21 CPS)**: **`PASS`** (0 critical violations)
*   **The UI Collision (Safe-Zone Overlays)**: **`PASS`** (0 grid violations)
*   **The Cascading Edit Tax (100% Autonomous output)**: **`PASS`** (0 manual human edits needed)

> **Gate 1 Verdict**: **🟢 PASS (100% Automated UI Compliance)**

---

### 🧠 GATE 2: Semantic Yield (Max 100 pts)
*   **Overall Average Score**: **`97.9 / 100`**

| Core Target Language | Gate 1 (UI Physics) | Gate 2 (Semantic Yield) | Performance Summary |
| :--- | :---: | :---: | :--- |
| **Mandarin (Simplified)** | `PASS` | **`100 / 100`** | Flawless CJK word-boundary wrapping and tone |
| **Portuguese (Brazil)** | `PASS` | **`100 / 100`** | Fully idiomatic phrasing, zero layout spillover |
| **Japanese** | `PASS` | **`98.7 / 100`** | Perfect clause wrapping, natural vocabulary |
| **French (France)** | `PASS` | **`98.4 / 100`** | Excellent syntax pacing under tight screen time |
| **German** | `PASS` | **`98.0 / 100`** | Correct compound splitting and punchy copywriting |
| **Arabic (Modern Standard)** | `PASS` | **`98.0 / 100`** | Stable right-to-left directionality & punctuation |
| **Italian** | `PASS` | **`97.9 / 100`** | Clean romance sentence compression |
| **Russian** | `PASS` | **`97.7 / 100`** | Intact morphological structure & timing |
| **Spanish (LATAM)** | `PASS` | **`96.5 / 100`** | Precise ASR translation alignment |
| **Hindi** | `PASS` | **`94.6 / 100`** | High native script preservation |

---

## 📹 Benchmark Video Catalog & Localized Examples

### 1. The Auctioneer
* **Source Language**: English
* **Source Text**: *"Listen up. If you want to absolutely"*

| Target Language | Localized Translation Output |
| :--- | :--- |
| **Spanish** | ¡Escuchen! Si quieren romper / estancamientos y eliminar |
| **French** | Écoutez bien. Si vous voulez / pulvériser vos plateaux |
| **German** | Hör gut zu. Willst / du Plateaus sprengen und |
| **Japanese** | いいか、​聞け。​夏が / 始まる前に​限界を​突破し、 |
| **Arabic** | اسمعني جيداً إن أردت / تحطيم الحواجز ونسف |
| **Hindi** | ध्यान से सुनो। अगर आप / हर बाधा को पूरी तरह |

---

### 2. Cinematic Pause 169
* **Source Language**: English
* **Source Text**: *"Welcome to the absolute pinnacle of modern,"*

| Target Language | Localized Translation Output |
| :--- | :--- |
| **Spanish** | Bienvenidos |
| **French** | Bienvenue au sommet absolu du moderne, |
| **German** | Willkommen am absoluten Gipfel |
| **Japanese** | 現代の​極上の​暮らしの、 |
| **Arabic** | مرحباً بكم في قمة الحداثة المطلقة |
| **Hindi** | आधुनिकता के परम शिखर पर आपका स्वागत |

---

### 6. Legal Disclaimer
* **Source Language**: English
* **Source Text**: *"Unlock your complete financial freedom"*

| Target Language | Localized Translation Output |
| :--- | :--- |
| **Spanish** | Obtén total libertad financiera |
| **French** | Prenez le contrôle / de vos finances dès |
| **German** | Sichern Sie sich noch |
| **Japanese** | 限定​特選​口座で​完全な / 経済的​自由を​手に​入れ |
| **Arabic** | حقّق حريتك المالية الكاملة |
| **Hindi** | हमारे प्रीमियम बचत खाते से पाएं |

---

### 10. The Overlap
* **Source Language**: English
* **Source Text**: *"So when I looked closely at the historical market data,"*

| Target Language | Localized Translation Output |
| :--- | :--- |
| **Spanish** | Al analizar los datos históricos del mercado, |
| **French** | En examinant |
| **German** | Bei der Analyse der historischen Marktdaten |
| **Japanese** | 市場の​過去​データを​注視した時、 |
| **Arabic** | عندما دققت في بيانات السوق التاريخية، |
| **Hindi** | तो जब मैंने बाजार के ऐतिहासिक आंकड़ों |

---

### 11. Mumble UGC
* **Source Language**: English
* **Source Text**: *"This phone, the camera is just"*

| Target Language | Localized Translation Output |
| :--- | :--- |
| **Spanish** | Este teléfono, la cámara / es increíble y toma |
| **French** | Ce téléphone, |
| **German** | Die Kamera dieses Handys ist |
| **Japanese** | この​スマホ、​カメラが / 本当に​ 素晴らしくて​、 |
| **Arabic** | كاميرا هذا الهاتف / مذهلة وتلتقط |
| **Hindi** | इस फोन का कैमरा सच में लाजवाब है |

---

### 12. Sonic Mess
* **Source Language**: English
* **Source Text**: *"What is up, guys? We are live"*

| Target Language | Localized Translation Output |
| :--- | :--- |
| **Spanish** | ¡Hola a todos! |
| **French** | Salut tout le monde! |
| **German** | Was geht, Leute? |
| **Japanese** | みんな​調子​どう？ |
| **Arabic** | كيف الحال يا شباب؟ |
| **Hindi** | क्या हाल है, दोस्तों? हम लाइव हैं अब |

---

### 16. The Density Bomb
* **Source Language**: Chinese
* **Source Text**: *"最神仙折叠屏瞬息满血急速闪冲"*

| Target Language | Localized Translation Output |
| :--- | :--- |
| **Spanish** | Carga ultraveloz |
| **French** | Pliable de rêve: charge éclair |
| **German** | Falt-Genie lädt blitzschnell voll |
| **Japanese** | まさに神レベルの、 |
| **Arabic** | أروع هاتف مطوي / يشحن بلحظة! |
| **Hindi** | सबसे शानदार फ़ोल्डेबल, |

---

### 17. The Velocity Asymmetry
* **Source Language**: Spanish
* **Source Text**: *"Chicos, no os vais a creer / la absolute locura"*

| Target Language | Localized Translation Output |
| :--- | :--- |
| **Spanish** | Chicos, no os vais a creer / la absolute locura |
| **French** | Les amis, vous n'allez pas croire |
| **German** | Leute, ihr werdet nicht glauben, |
| **Japanese** | みんな！​ この超​面白い​デバイス、 |
| **Arabic** | يا رفاق، / لن تصدقوا الروعة المطلقة |
| **Hindi** | दोस्तों, आप यकीन नहीं करेंगे |

---

### 19. The RTL Native Crash
* **Source Language**: Arabic
* **Source Text**: *"اكتشف قمه الفخامه داخل قلب مدينه دبي / حيث"*

| Target Language | Localized Translation Output |
| :--- | :--- |
| **Spanish** | Descubra el lujo supremo |
| **French** | Découvrez le summum / du luxe au cœur de Dubaï. |
| **German** | Erleben Sie puren Luxus / im Herzen von Dubai. |
| **Japanese** | ドバイの​中心部で​最高峰の / 贅沢をご​堪能​ください。 |
| **Arabic** | اكتشف قمه الفخامه داخل قلب مدينه دبي / حيث |
| **Hindi** | दुबई के दिल में |

---

## 📂 Reference Outputs
The localized subtitle outputs are organized by video and located in the `/results/outcaps_visloc_20_results/` folder of this repository. Each file contains:
*   Original transcribed track (marked `[English]` or source language).
*   Aligned target translation tracks with exact timestamp sync.
