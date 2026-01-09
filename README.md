# epoch-ai-evidence-tracking
Research-oriented workflow for tracking AI trends, benchmarks, and infrastructure inputs 

**Purpose**

This repository demonstrates a research-oriented workflow for **tracking AI trends, benchmarks, and infrastructure inputs** through careful extraction and synthesis of public technical evidence. It is designed to reflect the type of analytical support work required in AI research institutes: parsing machine learning papers, evaluating benchmark claims, estimating infrastructure inputs from partial disclosures, and documenting uncertainty and source reliability.

The emphasis is on **methodological rigor and clarity**, not model training or deployment.

**What This Repository Shows**

**1.	Technical Literature Parsing**

A structured approach to reading machine learning papers and technical reports, focusing on: - Model architectures and training setup - Datasets and evaluation protocols - Reported benchmark results and limitations - Implicit assumptions and missing details

Outputs are captured in standardized tables suitable for comparison across sources.

**2.	Benchmark & Leaderboard Tracking**

Examples of how benchmark claims are: - Extracted into spreadsheets - Normalized where possible for cross-source comparison - Annotated with confidence levels and methodological caveats

This reflects real-world conditions where benchmark reporting is heterogeneous and incomplete.

**3.	Infrastructure & Compute Estimation**

Notes and examples illustrating how hardware and compute inputs can be inferred from: - Model descriptions - Training time disclosures - Hardware references (e.g., GPU class, interconnects) - Financial or operational context

Estimates are treated as ranges, not point values, with assumptions explicitly documented.

**4.	Source Reliability & Uncertainty Handling**

Each extracted data point is accompanied by: - Source attribution - Reliability assessment (primary, secondary, speculative) - Notes on uncertainty and sensitivity to assumptions

This is critical when data is later used for trend analysis or policy-relevant research.

**Repository Structure**

├── README.md                       # Overview and methodology
├── methodology.md                  # Evidence extraction and evaluation approach
├── paper_parsing_template.xlsx     # Template for parsing ML papers
├── benchmark_tracking_example.csv  # Example benchmark comparison table
└── infrastructure_notes.md         # Compute and hardware estimation notes

All files are designed to be readable, auditable, and easy to extend.

**Intended Use**

This repository is intended as:
-	A demonstration of analytical judgment and research discipline
-	A template for scalable evidence-tracking work
-	A foundation for contributing to AI trend analysis and governance-relevant research

It is **not** intended as a production ML system or model implementation.

**About**

George Abuya
Applied Data Scientist – AI Trends & Technical Evidence Analysis
LinkedIn: linkedin.com/in/george-abuya 
GitHub: github.com/gwabuya


_This repository prioritizes transparency, restraint, and careful reasoning under uncertainty—core requirements for high-quality AI research support._

