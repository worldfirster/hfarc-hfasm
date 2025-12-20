HFA理論（Hierarchical Framework Architecture）とは、
階層構造を前提に、
ソフトウェアやハードウェアの設計を
極端に簡潔な表現で扱おうとする
個人発想（作成者：大野実）のフレームワークである。

定義初出：2025年

---

# HFA Documentation

This directory contains formal specifications and design documents for the HFA language.

## Contents

- **spec-v0.1.md**  
  Official language specification

- **kaomoji-instructions.md**  
  Definition of kaomoji as first-class instructions

## Design Note

HFA intentionally avoids complex templates.
Minimal definitions are preferred over exhaustive specifications.

## Overview

HFA (Hybrid Face Assembly) is an experimental programming language specification
that treats kaomoji and symbols as first-class instructions.
The language is state-driven and explicitly defines a ZERO state,
where capability exists but is intentionally not exercised.

HFA focuses on semantics, state transitions, and minimal expressive units,
rather than implementation complexity.

HFA（Hierarchical Framework Architecture）
