# Automated Documentation Drift Detection

**An AI-powered tool to detect outdated documentation when source code changes.**

## Overview

Documentation Drift Detection helps developers identify when project documentation no longer matches the actual source code.

When developers modify functions, APIs, configurations, or application behaviour, the related documentation may remain unchanged. This creates documentation drift.

Our tool automates the detection process using code analysis, semantic search, and AI verification.

## How It Works

1. **Detect Changes:** Monitor GitHub Pull Requests.
2. **Extract Facts:** Identify important changes in the source code.
3. **Search Documentation:** Find related documentation sentences.
4. **AI Verification:** Compare documentation with the updated code using an LLM.
5. **Report Issues:** Post possible documentation mismatches as GitHub PR comments.

## Key Features

- Automatic documentation drift detection.
- GitHub Pull Request integration.
- AI-powered code and documentation comparison.
- Semantic documentation search.
- Reduced false-positive warnings.
- Local CLI support.

## Access Methods

- **GitHub App:** Automatically checks Pull Requests.
- **GitHub Actions:** Runs inside your own CI/CD workflow.
- **CLI:** Checks documentation locally before submitting a PR.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core development |
| GitHub API | Repository integration |
| GitHub Actions | Automation |
| LLM (Gemma / OpenAI) | AI verification |
| Embeddings | Semantic search |

## Development Estimates

- **Development Time:** 14–20 person-days (one developer).
- **Two Developers:** Approximately 8–10 person-days.
- **Running Cost:** Approximately $0.01–$0.06 per PR.
- **Monthly Cost:** Approximately $1–$13 for 50 PRs.

*These are estimated figures based on the project proposal.*

## Project Goal

To make software documentation more accurate, reliable, and easier to maintain by automatically identifying mismatches between code and documentation.

**Keep documentation in sync with code.**

## References

- [GitHub Octoverse 2024](https://github.blog/news-insights/octoverse/octoverse-2024/)
- [GitHub Actions](https://docs.github.com/en/actions)
- [OpenAI API](https://platform.openai.com/docs)
