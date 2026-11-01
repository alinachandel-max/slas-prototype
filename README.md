# SLAS mobile prototype

https://alinachandel-max.github.io/slas-prototype/

Updated 1 November 2026 from Figma Application, section 194:4446; verification states 210:16274 / 210:16472; email flow 194:5051.

The application now uses separate mobile screens: introduction → citizenship → institution/session availability → account and email → student verification and confirmation → contact details → loan options → bank verification and confirmation → supporting document → review and agreements → Application submitted / Pending.

Use fictional details. This is a frontend demonstration: account, email, identity, bank and submission checks are simulated. Any six digits confirm the email. Tuition is ₦250,000; optional upkeep adds ₦180,000 (₦20,000 × 9 months). These are demonstration amounts and the agreement dialogs contain summaries, not approved legal text.

Save to drafts stores answers only in this browser on this device. Passwords, codes, BVN, account numbers and uploaded file contents are not stored. After reloading a draft, bank details and the admission letter must be added again. No data is sent to NELFUND or another service. Submitted receipts are demonstration state for the current tab.

Admission Letter accepts nonempty PDF/JPEG up to 2 MB. Document policy, loan terms and GSI agreements are required. The portrait and returned identity remain fictional. Native input, browser Back, reduced motion and widths from 320px are supported. Lists of institutions, banks and local government areas are demonstration subsets.

Manrope is included under the SIL Open Font License; see LICENSE-Manrope.txt. The separate /v2/ concept remains available.

Verification results use the original green letter wave and progressive record appearance. The updated email flow uses six code cells: the sixth digit starts a local check, the cells turn green on the same form, and Continue opens the next task. There is no separate email-success screen or automatic advance. Student and bank checks keep entered fields readonly while the original spinner and dot wave run. Headers and bottom action groups stay pinned while the page content scrolls. Buttons are 48px high with 16px Manrope Semibold text; headings and secondary actions follow the latest Figma typography. Bottom action groups have a 12px gap above the device safe area. System status bars, browser toolbars and keyboards remain native. Motion respects reduced-motion preferences.

The native keyboard covers the bottom actions at their normal position. Only the content scroll area gains space to keep the focused field visible. Text-field and active OTP focus use a 2px brand-green border; confirmed OTP cells use a 1px light-green border from Figma200:15969. Page titles and the gap from the heading group to content remain24px.

Choose Loan Options keeps the two funding cards on the page. Learn more opens details for each option without changing the selection. View repayment terms opens the current total, interest rate and repayment information in a modal. The Continue button reflects the selected total.
