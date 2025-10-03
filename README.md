# ElevateLabs_CS_Task06
Create a Strong Password and Evaluate Its Strength
# Password Strength Evaluation Report

## Test passwords
- password123
- Summer2023!
- Tr0ub4dor&3
- correct horse battery staple
- G7!vR8#kPq2$T9

## Observations
- Weakest: `password123` — score 0, found in breaches via HIBP.
- Strongest: `G7!vR8#kPq2$T9` — score 4, estimated entropy ~78 bits.
- Passphrases with sufficient words (4+) provide strong security and are easier to remember.

## Best practices learned
- Prefer length (≥ 12 characters) and uniqueness over arbitrary complexity.
- Use passphrases (4+ random words) or high-entropy random strings.
- Do not reuse passwords across sites.
- Use a reputable password manager to generate/store unique passwords.
- Enable 2-factor authentication (2FA) wherever possible.

## Attacks overview
- **Brute force:** attacker tries all combinations; complexity grows exponentially with entropy.
- **Dictionary attack:** uses common words/phrases; mitigated by avoiding dictionary words.
- **Credential stuffing:** reused passwords from breaches; mitigated by unique passwords & 2FA.
- **Rainbow tables:** precomputed hashes; mitigated by salting and strong hashing.

## Files produced
- `reports/password_strength.csv` — scores and crack-time estimates
- `reports/password_strength_report.md` — this report
- `screenshots/` — screenshots of results
