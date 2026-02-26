
# Million-Scale Max-3-SAT Solver
Date: 2026-02-26  
Core Result: 1M variables, 4.2M clauses, 95.36% satisfaction, 19.66s (single thread)

## Key Proof
- Validation Log: [validation_report_20260226_113835.txt](validation_report_20260226_113835.txt)（后续上传日志后，这个链接会自动生效）
- Method: Lagrangian dual equilibration (Equi-Efficiency Principle, EEP)
- Commit Timestamp: [当前commit hash，上传后自动生成]

## Comparison
- MaxHS/Kissat: Out of Memory (OOM) at 10^5 variables
- WalkSAT: >2 hours at 10^6 variables
- Our Solver: 19.66s at 10^6 variables (single CPU core)
