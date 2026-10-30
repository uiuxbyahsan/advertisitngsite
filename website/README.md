# Billboard Connection
Run `npm run build` and `npm run dev`. Source: build.py for shared templates and page content; src/style.css for design tokens and responsive layouts; src/app.js for interactions. Output: dist. No dependencies required.

## Submission integration boundary
The planner validates and downloads a local text brief. It does not transmit data or claim submission success. Before enabling online submission, configure a server endpoint with server-side validation, spam protection, rate limits and confirmed delivery. Add pending, failure and success handling against actual responses; redirect to a submission receipt only after confirmed delivery. The thank-you route currently explains that nothing was sent.

## Content required before launch
Supply approved email, company history, current credentials, original FAQ and articles, approved legal policies, confirmed production domain and original URL inventory. Current legal text describes site behavior; business approval is needed. Insights has an honest empty state. No client list or invented articles are included. See ASSET-INVENTORY.md.
