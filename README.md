# Review-Safe Artifacts (Phase 1–2)

This package contains **review-safe artifacts** for evaluation.  
Core algorithms, elevation logic, and optimizer code are **intentionally excluded**.

---

## 📦 Included

### 1) `notebooks/01_data_audit_and_family_mapping.ipynb`
- **Review version** – outputs-only / minimal code exposure
- Summaries: data range, basic integrity checks, high-level family mapping views

### 2) `artifacts/bond_stats.csv`
- Pair statistics: **frequency / PMI / Lift** (aggregated)
- For inspection only; generation methodology withheld

### 3) `artifacts/dna_map.json`
- **Truncated/sample** DNA family mapping
- Enough to verify structure; full disclosure intentionally withheld

### 4) `outputs/next_draw_75.csv` *(if present)*
- Current **75-set** selection exported from the internal pipeline

### 5) `outputs/backtest_summary.md` *(if present)*
- Backtest performance summary (tables & highlights)

---

## 🔎 What’s **not** included (by design)

- Core generation algorithms (base → elevate → select)
- Optimizer/selector implementation details
- Training/elevation heuristics and weighting schedules
- Production code, configs, and deployment scripts

---

## 🧭 How to review

1. Open the notebook `01_data_audit_and_family_mapping.ipynb` to view audit & mapping summaries.  
2. Inspect `artifacts/bond_stats.csv` and `artifacts/dna_map.json` for structural sanity.  
3. (Optional) Check `outputs/next_draw_75.csv` and `outputs/backtest_summary.md` if provided.

> **Tip:** This package is display-only; it is not intended to reproduce the pipeline.

---

## 📝 Notes

- Artifacts are sufficient for **evaluation and discussion** only.
- Any numeric/statistical summaries are **snapshot views** for review; they do not reveal internal logic.
- For usage restrictions and disclosures, see **[NOTICE.md](NOTICE.md)**.

---

## ⚖️ Legal / IP

This package is provided **for evaluation purposes only**.  
No transfer of intellectual property, license, or commercialization rights is granted or implied.  
Core algorithms, optimization strategies, and production code remain **proprietary to the author**.

---

**Version:** Phase 1–2 (review-safe)  
**Maintainer:** Juno  
