# AICTE WorkflowOS Demo

Frontend-only demo based on the original AICTE WorkflowOS UI. Original layout and styles are retained; API calls are replaced by browser-local demo data stored in localStorage. No backend or database is required.

## Run locally
1. Install Node.js 20.19+ or 22.12+.
2. Open a terminal in `frontend`.
3. Run `npm install`.
4. Run `npm run dev` and open the URL printed by Vite.

Demo accounts: `admin@demo.local`, `officer@demo.local`, `reviewer@demo.local`, `auditor@demo.local`. Password: `Demo@12345`.

Presentation prototype only. Changes are saved in this browser and do not sync between devices. Document uploads and CSV export require a backend and are not active in this offline demo.