# Soppia Framework

**A Structured Prompting Framework for the Proportional Assessment of Non-Pecuniary Damages in Personal Injury Cases**

[![arXiv](https://img.shields.io/badge/arXiv-pending-b31b1b.svg)](https://arxiv.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

Soppia (System of Proportionally and Ponderously Intelligently Applied Guidance) is a structured prompting framework designed to enhance consistency, transparency, and auditability in the quantification of non-pecuniary damages. By integrating weighted legal criteria with Large Language Models (LLMs), Soppia reduces judicial noise and cognitive biases while maintaining human oversight and explainability.

## Key Features

- **Transparent Methodology**: Every decision is traceable and auditable through explicit criteria
- **Dual-Logic Scoring System**: Correctly models both aggravating and mitigating circumstances
- **Weighted Criteria**: Reflects the relative importance of different legal factors
- **Adaptable Framework**: Can be customized for different jurisdictions and areas of law
- **AI-Augmented**: Leverages LLMs while maintaining interpretability and human control

## Case Study

The framework is demonstrated using the 12 criteria for non-pecuniary damages established in Brazilian Labor Law (Art. 223-G, CLT), but the methodology is applicable to any legal system.

## Repository Contents

```
soppia-framework/
├── README.md                    # This file
├── paper/
│   ├── soppia_paper.pdf        # Full academic paper
│   └── main.tex                # LaTeX source for arXiv submission
├── prompts/
│   ├── soppia_full_prompt.md   # Complete prompt template
│   └── soppia_simple_prompt.md # Simplified version
├── examples/
│   ├── example_case_1.md       # Sample case analysis
│   └── example_case_2.md       # Sample case analysis
└── LICENSE                      # MIT License
```

## Quick Start

### Using the Framework

1. **Choose your LLM**: Soppia works with GPT-4, Claude, Gemini, or other advanced LLMs
2. **Load the prompt**: Use the full prompt from `prompts/soppia_full_prompt.md`
3. **Provide case facts**: Input medical reports, testimonies, and evidence
4. **Review the analysis**: The AI will generate a detailed, step-by-step assessment

### Example Usage

```
User: [Provides case facts about a workplace injury]

Soppia: 
1. CASE SUMMARY
[Analysis of the provided facts]

2. CRITERIA ANALYSIS
Criterion I - Nature of protected legal interest: [Score: 4/5]
[Detailed justification]
...

3. FINAL CALCULATION
- Total weighted score: 58.5 points
- Classification: SEVERE
- Suggested compensation: 15-20× monthly salary

4. CONCLUSION
[Summary and recommendation]
```

## Methodology

The framework consists of four main components:

1. **Defined Criteria**: Legally relevant factors derived from statutes, case law, or doctrine
2. **Calibrated Scoring**: 1-5 point scale with dual logic (direct/inverse)
3. **Weighting System**: Reflects relative importance of each criterion (0.5× to 2.5×)
4. **Classification Structure**: Maps scores to severity levels and compensation ranges

## Applications

- **Judges**: Structure and justify judicial decisions
- **Lawyers**: Assess case strength and manage client expectations
- **Companies**: Proactive risk management and liability assessment
- **Academics**: Legal analysis and research

## Adaptability

The framework can be adapted for:

- **Different jurisdictions**: Replace criteria with local legal factors
- **Other areas of law**: Consumer protection, environmental law, tort law
- **Custom weighting**: Calibrate weights based on local precedents

## Academic Paper

The full academic paper is available in the `paper/` directory and has been submitted to arXiv. The paper provides:

- Theoretical foundations (noise reduction, XAI, prompt engineering)
- Detailed methodology
- Complete weighting justifications
- Discussion of applications and limitations

## Citation

If you use this framework in your research or practice, please cite:

```bibtex
@article{araujo2025soppia,
  title={Soppia: A Structured Prompting Framework for the Proportional Assessment of Non-Pecuniary Damages in Personal Injury Cases},
  author={Araujo, Jorge Alberto},
  journal={arXiv preprint arXiv:XXXX.XXXXX},
  year={2025}
}
```

## Author

**Jorge Alberto Araujo**  
Magistrate and Legal AI Researcher

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit issues, suggestions, or pull requests to improve the framework.

## Acknowledgments

This work builds upon the foundational research of:
- Kahneman, Sibony, and Sunstein on noise in human judgment
- Cynthia Rudin on interpretable machine learning
- The broader XAI and legal AI research communities

## Disclaimer

This framework is designed as a decision support tool and does not replace professional legal judgment. All outputs should be reviewed and validated by qualified legal professionals.

---

**Version**: 1.0.0  
**Last Updated**: October 2025  
**Status**: Active Development

