# Antiplagiat & Plagiat-Improve AI Skills

A pair of specialized AI agent skills for detecting AI-generated writing and uncredited plagiarism, and rewriting flagged text into natural, authentic human prose.

Bu repozitoriya mətnləri süni intellekt (AI) izləri və plagiat üçün yoxlayan (`antiplagiat`) və problemli hissələri təbii, axıcı insan dilinə uyğunlaşdırıb yenidən yazan (`plagiat-improve`) iki AI bacarığını (skill) özündə birləşdirir.

## Included Skills / Daxil Olan Bacarıqlar

| Skill Name | Purpose (EN) | Məqsəd (AZ) |
| :--- | :--- | :--- |
| `antiplagiat` | Screens text for AI markers and verbatim web matches, generates a diagnostic report, and provides an improved rewrite. | Mətni AI qəlibləri və veb-plagiat üçün yoxlayır, diaqnostik hesabat çıxarır və dərhal təkmilləşdirilmiş variantını verir. |
| `plagiat-improve` | Dedicated humanizer and rewriter that removes synthetic phrasing and monotonous rhythms while keeping core facts intact. | Yalnız mətni təbiiləşdirmək, monotonluğu qırmaq və faktları saxlamaqla orijinal formada yenidən yazmaq üçün istifadə olunur. |

## Repository Structure / Qovluq Quruluşu

```text
.
├── skills/
│   ├── antiplagiat/
│   │   └── SKILL.md
│   └── plagiat-improve/
│       └── SKILL.md
├── LICENSE
└── README.md
```

## Key Features / Əsas Xüsusiyyətlər

### 1. `antiplagiat`
- **Structural & Stylistic AI Profiling:** Evaluates sentence burstiness, uniform clause lengths, passive hedging, and overused LLM transition markers.
- **Verbatim Web Matching:** Extracts distinctive 6-10 word phrases and runs exact-match searches across public web sources.
- **Diagnostic Authenticity Report:** Categorizes content (`Likely Human`, `Mixed / Edited AI`, `Highly Likely AI Generated`) and links directly to matched sources.
- **Automatic Rewrite:** Immediately follows the diagnostic report with a polished, humanized version of the flagged passages.

### 2. `plagiat-improve`
- **Cadence Diversification:** Alternates short, direct statements with complex multi-clause sentences to establish natural human flow.
- **Cliché Elimination:** Strips out mechanical connectors and synthetic corporate filler.
- **Factual Integrity:** Preserves all original arguments, statistics, citations, and domain-specific terminology.

## Usage Examples / İstifadə Nümunələri

**Using `antiplagiat`:**
> "Bu mətni antiplagiat ilə yoxla və problemli hissələri düzəlt."
> 
> "Check this essay for AI generation and plagiarism."

**Using `plagiat-improve`:**
> "Bu mətndəki süni intellekt qəliblərini təmizlə və daha axıcı, orijinal variantını hazırla."
> 
> "Humanize this draft and remove repetitive AI phrasing while keeping all data points intact."

## Installation / Quraşdırılma

1. Clone this repository or download the `SKILL.md` files from the `skills/` directory.
2. Upload each `SKILL.md` file (or the skill folder) via your AI platform's **Skills Manager** UI, or import directly from the repository path.

## License / Lisenziya

Distributed under the **MIT License**. See the `LICENSE` file for full details.