# LLM Privileged Script Risk

Technical report on risks of LLM-generated administrative scripts in privileged environments, with mitigations for “code vibing.”

## What this is
This repository contains a versioned technical report analyzing failure modes that occur when LLM-generated administrative scripts are executed in privileged environments, and proposes practical mitigations that reduce risk.

## What this is not
This work does not claim to eliminate hallucinations, prompt injection, or automation errors. It aims to reduce the likelihood and impact of high-regret failures in privileged execution contexts.

## Contents
- `paper.pdf` — the current release PDF
- `src/` — LaTeX source, references, and figures used to build the PDF

## License
CC BY-SA 4.0. See `LICENSE.md`.

## How to cite
A Zenodo DOI will be added once the first release is archived. Until then, cite the GitHub release tag and year.

## Contributing
Issues and pull requests are welcome, especially:
- missing failure modes and edge cases
- mitigation controls and enforcement mechanisms
- references to prior work and related standards
