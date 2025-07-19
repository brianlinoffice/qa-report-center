# qa-report-center
Centralized HTML report hosting for automated QA test results across multiple projects.

```
Branch: report-pages/
index.html <– 自訂首頁，放報告清單

路徑規則：
├── ProjectA/
│   └── prod
│       └── 20250101_000001
│           └── index.html <– Pytest HTML 報告
│   └── stage
│       └── 20250101_000002
│           └── index.html <– Pytest HTML 報告
├── ProjectB/
│   └── prod
│       └── 20250101_000003
│           └── index.html <– Pytest HTML 報告
│   └── stage
│       └── 20250101_000004
│           └── index.html <– Pytest HTML 報告
```
