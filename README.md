# Loan Application Form

Multi-step loan application form (Personal, Home, Business) in pure HTML, CSS and JavaScript. Single file, no dependencies.

**Live demo:** https://Asim19xd.github.io/loan-application/

## Features
- 9 steps: Loan, Personal, Identity, Address, Employment, Details, Obligations, Documents, Review and sign
- Personal, Home and Business loans with different fields and limits
- Real-time validation and conditional fields
- Cross-step rules: age plus tenure up to 70, home loan up to 90% of property value, business loan up to 50% of turnover, obligations up to 60% of income
- PAN and Aadhaar verification (simulated; Aadhaar uses the real checksum; demo OTP is 123456)
- Address autocomplete from a small built-in list
- Document upload with preview and image compression
- E-signature pad
- Auto-save and resume (saved in the browser)
- Pre-approval summary with EMI, rate and eligibility
- 18 built-in E2E tests (click "Run E2E tests" at the bottom of the page)

## Run locally
Open `index.html` in a browser.

## Notes
All verification, rates and eligibility are simulated and for demonstration only. A real deployment needs a backend.

## License
MIT
