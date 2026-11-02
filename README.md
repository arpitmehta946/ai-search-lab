# AI Search Lab

Public experiments by **Arpit Sharma** (engineer who writes; SEO & Content at Aqlix IT Solutions; Amb, Himachal Pradesh, India) on how ChatGPT, Gemini, Perplexity and Google AI Mode find, cite and recommend people and brands.

- Website: https://arpitmehta946.github.io/
- LinkedIn: https://www.linkedin.com/in/arpitsharmaoff

## Experiment 2: Google's top 10 vs ChatGPT's sources (1 Nov 2026)

10 everyday Indian searches. Each asked to free ChatGPT 5 times, in a new temporary chat every run, and compared with Google's top 10 organic results (google.co.in, hl=en, gl=in) for the same search.

| Result | Value |
|---|---|
| Different pages ChatGPT linked to (50 answers) | 134 |
| Of those, in Google's top 10 for the same search | 6 (4%) |
| Pages that came back in 3 or more of 5 runs | 69 |
| Pages in all 5 runs | 30 |
| Brand or institution pages | 69 |
| Government or regulator sites | 16 |
| Comparison, review or guide articles | 49 |

Files:
- `exp2-by-search.csv`: unique pages, pages in 3+ runs and pages in Google's top 10, per search.
- `exp2-link-types.csv`: every unique link ChatGPT gave, by search, with its type (sorted by hand).

Full results log (every link, every run, with chat IDs), summary formulas and method: [public Google Sheet](https://docs.google.com/spreadsheets/d/18_l27lQDdaP6FNfbxsW-m0qJTv2RDOffcJNaiYuog2g/edit?usp=sharing)

Write-up: https://arpitmehta946.github.io/lab/google-vs-chatgpt.html

### Limits
Small test: 10 searches, one account, one location, one afternoon. Runs were executed by an AI assistant in Arpit's ChatGPT account following a fixed script; Google was searched while logged in. One run of search 1 was lost to a timeout, not counted, and re-run.

## Licence
Data: CC BY 4.0. Credit "Arpit Sharma, AI Search Lab".
