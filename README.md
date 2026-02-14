# CbetaZenTexts

An effort to make the **CBETA canon** accessible to English speakers, with a focus on **Zen / Chan texts**.

This repository hosts a **collaborative translation project** built on top of the official CBETA XML corpus.  
It is designed to support large-scale translation while preserving the original TEI/XML structure and attribution.

---

## 📂 Repository Structure

### `xml-p5` — Original Chinese Texts

Contains **unmodified CBETA XML TEI P5 files**, mirrored from:

https://github.com/cbeta-org/xml-p5

**Source baseline snapshot:** January 2026

- Files are redistributed **unchanged**
- All original CBETA headers are preserved
- These files should not be edited

---

### `xml-p5t` — English Translations (Work in Progress)

Contains copies of the same XML files, with **English translations added**.

Not all files are translated yet. Coverage varies widely.

**Example translated text:**

- **T 1987A — The Record of Caoshan**  
  Location: `xml-p5t/T/T47/T47n1987A.xml`

Translated files **preserve the full original CBETA header**, with translation content added below it.

---

## ⚠️ Important: CBETA Non-Commercial Requirement

The CBETA texts are provided under a **non-commercial use requirement**.

In short:

- CBETA retains ownership of the original texts  
- Redistribution is allowed **only for non-commercial use**  
- The **full CBETA header must remain intact** in every file  
- Translations are subject to the same non-commercial condition  

Please don’t sell this material, and don’t remove or alter the CBETA headers.

---

## 📜 License & Attribution

The original XML texts are provided by:

**CBETA — Chinese Buddhist Electronic Text Association**  
財團法人佛教電子佛典基金會

Each file includes the official CBETA header, which contains the authoritative license and attribution language.

This repository **does not modify or override** CBETA’s license terms.

---

## 📝 About the Translations

English translations in `xml-p5t` are **collaborative derivative works** based on CBETA’s XML.

They aim to:

- Preserve TEI/XML structure compatibility
- Stay aligned with the original Chinese text
- Allow transparent collaboration and review

Translations are shared under the **same non-commercial condition** as the original CBETA texts.

---

## 🎯 Purpose of This Project

The goals of this repository are:

- To make Zen texts accessible to English readers  
- To preserve TEI/XML structural compatibility  
- To support transparent, Git-based collaboration  

If CBETA has any concerns regarding redistribution, attribution, or presentation, this project will comply with their requirements.

---

## 🤝 Contributing (Easy Mode)

You **do not need to know Git** to contribute.

The easiest way to help translate is to use the official desktop app:

👉 **CBETA Translator**  
https://github.com/Fabulu/CBETA-Translator

---

### 🪜 Step-by-Step Workflow

1. Download and open **CBETA Translator**
2. Clone this repository using the built-in **Git tab**
3. Open a text from `xml-p5t`
4. Translate or improve a section
5. Press **Save** in the Translation view
6. Go to the **Git tab**
7. Enter a **commit message**
8. Press **Create local commit**
9. Press **Authorize GitHub** and complete authorization
10. Press **Push + Create PR**

That’s it.

The app will:

- Create a local commit  
- Fork the repository (if needed)  
- Push your change  
- Open a Pull Request automatically  

To you, it feels like:

**Translate → Save → Commit → Submit**

---

## 🧠 Translation Philosophy

This project is designed to support **high-quality machine translation workflows**.

You do not need to produce literary perfection.

Good machine translation is:

- Acceptable  
- Encouraged  
- Often preferred as a baseline  

The structure is built to allow iterative improvement over time.

---

## 📝 Please Add a Translator Annotation

At the top of the file (in Readable mode), please add a short annotation indicating:

- Who you are  
- What you did  
- Whether you used machine translation  

Example:
resp: dota2nub
annotation: Machine translation using ChatGPT 5.2


This helps:

- Track translation methods  
- Maintain transparency  
- Credit contributors  

You do not need to write an essay. One short line is enough.

---

## 📌 A Few Guidelines

- Preserve all XML structure  
- Do not remove CBETA headers  
- Keep translations non-commercial  
- Small improvements are welcome  

You do not need to translate an entire text at once. Even a small improvement helps.

---

If you are comfortable with Git, you can contribute manually via pull requests.

If not — the app handles everything for you.
