# HFA/ASMrc

本リポジトリでは、HFA/ASMrc を設計思想・理論体系および実験的言語仕様として扱います。

HFA/ASMrc（Hierarchical Framework Architecture / ASMrc）は、  
顔文字や記号を第一級命令として扱う状態駆動型の実験的言語仕様と、  
階層構造と最小定義を重視する設計思想を包含する総称です。  

HFA/ASMrc は、階層構造を前提に、ソフトウェアやハードウェアの設計を  
極端に簡潔な表現で扱おうとする個人発想（作成者：大野実）のフレームワークであり、  
定義初出：2025年。

---

## Documentation

This directory contains formal specifications and design documents for the HFA/ASMrc language.

### Contents

- **spec-hfasm-v0.1.md** : Official language specification  
- **kaomoji-instructions.md** : Definition of kaomoji as first-class instructions

### Design Note

HFA/ASMrc intentionally avoids complex templates. Minimal definitions are preferred over exhaustive specifications.

### Overview

HFA/ASMrc is an experimental programming language specification that treats kaomoji and symbols as first-class instructions.  
The language is state-driven and explicitly defines a ZERO state, where capability exists but is intentionally not exercised.  
HFA/ASMrc focuses on semantics, state transitions, and minimal expressive units, rather than implementation complexity.

---

## Notes

- ZERO state is the initial state where abilities exist but are not exercised.  
- Hierarchical structure allows short commands to convey complete meaning.  
- All programs start from ZERO state.  
- Complex templates and exhaustive specifications are intentionally avoided.  

---

**Author:** 大野実  
**GitHub Account:** worldfirster  
**Specification Version:** v0.1
