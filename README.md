# grimoire

> Curated primary sources for low-level systems. Intel SDM, AMD manuals, Windows Internals, etc.—converted to clean markdown via [Docling](https://github.com/docling-project/docling).

Internal reference corpus for [RestrictedWTF](https://github.com/RestrictedWTF). We take massive vendor PDFs and convert them to structured markdown so we're not parsing 5,000-page PDFs at inference time.

## Structure

```
grimoire/
├── intel/
│   └── sdm/
│       └── sdm-combined.md
├── amd/
│   ├── svm/
│   └── apm/
├── microsoft/
│   └── windows-internals/
├── uefi/
└── .docling/
    └── docling_aio.py    # conversion script
```

Dump processed markdowns in the relevant folder. That's it.

## License & Attribution

The **markdown conversions** in this repository are provided as-is for research and educational purposes. The **original content** remains the intellectual property of its respective vendors (Intel Corporation, AMD, Microsoft Corporation, UEFI Forum, etc.).

We do not claim ownership of the underlying specifications. If you are a vendor representative and have concerns about the distribution of converted text, please open an issue.

> **Note:** This repository does not carry a blanket open-source license (e.g., MIT) because the corpus consists of derivative works of copyrighted vendor documentation.

---

*Nil Satis Optimum.*
