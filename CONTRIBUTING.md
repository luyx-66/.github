# Contributing

Contributions are welcome when they improve reproducibility, correctness, portability, or documentation.

## Before submitting

1. Use a minimal, focused change.
2. Add or update tests for code changes.
3. Run the repository's documented test command.
4. Keep API keys in environment variables and remove credentials from logs and fixtures.
5. Attach a public source and checked date to pricing data.
6. Include model ID, region, request count, and raw output for benchmark claims.
7. Preserve disclosures when APIMART or another provider has a commercial relationship with the content.

Do not submit fabricated measurements, copied proprietary material, referral spam, or requests to exchange rewards for stars, forks, or reviews.

## Submit benchmark data

Open the **Benchmark or pricing update** issue form in the relevant repository. A reviewable submission includes:

- provider and exact model ID;
- test window, runner region, request count, and concurrency;
- benchmark tool name and version or commit;
- a permanent link to sanitized raw results;
- dated pricing or product documentation used for comparison;
- retries, exclusions, timeouts, and failed requests;
- commercial, affiliate, or sponsorship disclosure.

Maintainers may reproduce a sample before accepting a result. Never paste an API key, authorization header, account identifier, or unredacted response log into an issue.
