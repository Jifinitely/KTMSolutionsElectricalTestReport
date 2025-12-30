# KTM Solutions — Electrical Test Report App

A SwiftUI iOS app for creating, previewing, and exporting electrical test reports to support compliance workflows aligned with Australian/New Zealand standards (e.g. AS/NZS 3000, AS/NZS 3017, AS/NZS 3008).

---

## Features
- Easy entry of test results (up to 8 per report)
- PDF export with KTM Solutions branding and signature capture
- Standards reference library with in-app PDF viewer, search, and bookmarking
- Live preview of the test results table (as it will appear in the PDF)
- Edit and delete test results before export
- Settings for company and tester information
- Data backup/restore (JSON export/import)
- In-app help and FAQ

---

## Screenshots
Add screenshots to a folder named `Screenshots/` and update the paths below.

| Form | Preview | PDF Export | Settings |
|---|---|---|---|
| `Screenshots/form.png` | `Screenshots/preview.png` | `Screenshots/pdf.png` | `Screenshots/settings.png` |

> Tip: On iPhone, take screenshots in light mode and dark mode if you want both.

---

## About
The KTM Solutions Electrical Test Report App is designed to streamline the creation and management of electrical test reports for electricians and electrical contractors. It helps produce consistent documentation and supports verification workflows while keeping the process fast and simple.

### Key Benefits
- **Time-saving:** Generate professional PDF test reports quickly
- **Consistency:** Built-in validation helps reduce missing fields
- **Reference-friendly:** Quick access to standards PDFs inside the app
- **Professional output:** Branded PDFs with company details and digital signatures
- **Portable records:** Export and restore saved reports using JSON backups

---

## Standards References
The app includes optional in-app references to standards PDFs, for example:
- AS/NZS 3000 (Wiring Rules)
- AS/NZS 3017 (Verification Guidelines / Testing)
- AS/NZS 3008 (Selection of Cables)

> Note: You must supply your own legally obtained copies of the standards PDFs. This repository does not include copyrighted standards content.

---

## Requirements
- Xcode 15+ (recommended)
- iOS 15+ (recommended)
- SwiftUI

---

## Setup
1. Clone this repository.
2. Open the project in Xcode.
3. Add your standards PDFs (e.g. `AS3000.pdf`, `AS3017.pdf`, `AS3008.pdf`) to the main app bundle:
   - Drag PDFs into Xcode
   - Ensure **Target Membership** is enabled for the app target
4. Build and run on a simulator or device.

---

## Usage
- Fill out the form with customer, site, and test details.
- Add up to 8 test results per report.
- Use the Preview tab to confirm the table output before exporting.
- Export to PDF for job documentation and record keeping.
- Use the Standards section to search and bookmark key clauses/tables (if PDFs are included).

---

## Backup / Restore
- **Export:** Settings → Export/Backup → Export All Reports (exports JSON data)
- **Import:** Settings → Export/Backup → Import/Restore Backup (imports JSON data)

---

## Support
For KTM Solutions support:
- Email: `service@ktmsolutions.com.au`
- Phone: `(07) 3813 0067`

---

## Roadmap (Optional)
Planned improvements may include:
- Customisable PDF layouts / headers
- Additional test fields and templates
- Multiple company profiles (for subcontractors)
- Cloud sync (optional)

---

## Contributing
This repository is intended as a KTM Solutions internal/test project.

If contributions are enabled:
1. Fork the repo
2. Create a feature branch: `feature/your-change`
3. Commit with a clear message
4. Open a Pull Request

Please avoid committing:
- `DerivedData/`
- `*.xcuserdata/`
- `build/`
- Standards PDFs (copyrighted)

---

## License
**Proprietary / Internal Use (Default)**

Copyright (c) KTM Solutions. All rights reserved.

This source code is provided for internal evaluation and development purposes only.  
No permission is granted to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of the software without explicit written permission from KTM Solutions.

> If you want this to be MIT/Apache/other, tell me which license and I’ll rewrite this section properly.

---

## Disclaimer
This app assists with electrical test report documentation. It is not an official standards publication and does not replace professional judgement. Always consult the latest AS/NZS standards and applicable legislation/regulations for compliance requirements.
