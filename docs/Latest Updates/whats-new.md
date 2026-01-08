# Latest Updates

Stay up to date with the newest features, improvements, and fixes in the **Whistle Drywall App**.

This page highlights what’s changed over time as we continue improving performance, usability, and reliability across the app. Each update includes a brief summary of the areas impacted, followed by detailed changes by month.

---

---
## November–December 2025 Updates – Whistle Drywall App

These updates focus on improving performance, simplifying workflows, and making everyday tasks easier—especially when working with reports, tasks, billing, and mobile navigation.

---

### 📊 Reporting Module Redesign

We’ve redesigned the **Reporting module** to deliver faster performance, clearer hour tracking, and more accurate billing.

This update improves how reports load, how hours are calculated, and how paid time is handled when generating Bills.

---

#### ⚡ Faster Performance

- **Much Faster Loading and Updates**  
  The Reporting page now loads significantly faster. Filters, approvals, new entries, and updates respond quickly, eliminating long wait times and allowing you to work without interruptions.

---

#### ⏱️ Simplified Hours & Approvals

- **Extra Hours Combined into Hours**  
  Extra Hours are now included directly in **Hours**, giving you one clear and accurate total for worked time.

- **Extra Hours Approval Removed**  
  The separate approval step for Extra Hours has been removed, simplifying the reporting and approval process.

- **Improved Column Order**  
  The **Extra Hours** column has been moved before **Hours** to improve readability and make reports easier to review.

---

#### 🧮 New “Paid Hours” Column

- **Paid Hours Input Added**  
  A new **Paid Hours** column has been added to the Reporting table. This field allows you to manually enter the number of hours that will be paid.

- **Paid Hours Used for Billing**  
  When creating Bills from selected report entries, Whistle now uses the **Paid Hours** value—even if it is set to zero or left blank—ensuring billing is always based on the intended paid amount.

---

#### 📄 Improved Report Generation

- **Updated Generate Report Output**  
  The **Generate Report** feature now includes the new columns and updated calculations.

- **Accurate Hours and Cost Calculations**  
  Fixed inconsistencies between hours and cost calculations to ensure reports and billing totals are accurate and reliable.

---

### ✅ Task Creation from Service Master List (SML)

- **Create Tasks Directly from the SML**  
  You can now create Tasks directly from the **Service Master List (SML)**. While viewing services, select one or more items and choose **Create Task**.

  Whistle automatically creates a separate task for each selected service, making it easier to turn planned services into actionable work without manual setup.

---

### 🧭 Mobile Navigation Improvements

- **Account Settings and Logout Added to Mobile Navigation**  
  When using the Whistle Drywall App on a mobile browser, **Account Settings** and **Logout** are now available directly in the navigation bar.

  This ensures essential account actions are always accessible and provides a more complete and consistent experience across devices.

---

### 🐛 Bug Fixes

- **Editing Bill Items with Apostrophes**  
  Fixed an issue where Bill items could not be edited if the service name contained an apostrophe (’), such as *McCoy’s Building Supply*.  
  Bill items with special characters in their names can now be edited normally without errors.

---

---

---

## October 2025 Updates – Whistle Drywall App

### 🚀 New Features

- **Smarter Search in Dropdowns**  
  Finding Jobs and Vendors is now faster when creating a Purchase Order. Instead of scrolling through long lists, you can simply start typing to quickly find exactly what you need.

- **Create Bills Directly from Purchase Orders**  
  You can now create a Bill directly from a Purchase Order using the new **“Create Bill from PO”** option. Whistle automatically brings in all product items from the PO, helping reduce manual entry, save time, and avoid mistakes.

---

### 🧠 Improvements & Enhancements

- **Better Search Across the App**  
  We’ve expanded searchable dropdown filters across key areas of the app, making it easier to find records wherever you’re working, including:  
  - Invoices  
  - Worker Contracts  
  - Bills  
  - Payments  
  - Teams  
  - Tasks  

- **Cleaner, More Organized Sidebar**  
  Sidebar menu items are now sorted alphabetically. This makes navigation more predictable and helps you find sections faster.

- **Improved User Activity Tracking**  
  Admin users can now see activity from both web and mobile apps (iOS and Android). The **Last Active** column now reflects real usage across all platforms.

- **Mobile Web Navigation Improvements**  
  Account Settings and Logout options have been added to the mobile navigation bar, making it easier to manage your account and sign out from any device.

---

### 🐛 Bug Fixes

- **Purchase Order Pagination Display**  
  Fixed an issue where page numbers could overflow when viewing many pages. Pagination now stays neatly within view.

- **Bill PDF Payee Labeling**  
  Resolved an issue where Bills were incorrectly labeling the Payee as “Worker.” Bills now correctly display **Payee** for both Vendors and Workers.

- **Vendor Contact Editing**  
  Fixed an issue that prevented editing vendor contacts when a Job name included an apostrophe (’). Vendor contact details can now be updated without issues.

---

## September 2025 Updates – Whistle Drywall App

### 🚀 New Features

- **Duplicate Billing Warning in Service Lists**  
  A new warning message now appears when attempting to create a Bill for services that are already linked to an existing Bill in the Service Master List (SML).  
  Whistle clearly shows which services are already billed, helping prevent duplicate charges.

---

### 🧠 Improvements & Enhancements

- **More Accurate Progress Tracking**  
  The **Percent Completed** field for invoices created from an SOV now supports decimal values, allowing for more precise progress reporting.

- **Easier Navigation Back to Filtered Bills**  
  A new **“Back to Filtered Bills”** link has been added to the Payments section, making it easier to return to your previously filtered list.

- **Simplified Payee Information**  
  Vendor and Worker columns have been combined into a single **Payee** column, making tables cleaner and easier to understand.

- **Consistent Action Buttons**  
  Action buttons across all modules have been standardized for a more consistent and predictable experience.

---

### 🐛 Bug Fixes

- **Correct Bill PDF Titles**  
  Fixed an issue where Bill PDF browser tabs were incorrectly labeled as “Purchase Order.” Tabs now correctly display **Bill**.

- **Teams Search Fix**  
  Resolved an issue where pressing Enter in the Teams search field caused an error.

- **Invoice Payment Errors Resolved**  
  Fixed an issue where adding multiple payments to an invoice could cause errors. You can now add multiple payments without problems.

- **Payment Editing Alignment**  
  Resolved a display issue where payment details could become misaligned while editing. Payment information now stays properly aligned.

---

## July/August 2025 Updates – Whistle Drywall App

### 🚀 New Features

- **Invoice Search Bar**  
  Added a search bar to the Invoice module, allowing you to quickly locate invoices.

- **Searchable Invoice Filters**  
  Dropdown filters in the Invoice module are now searchable, making filtering faster and easier.

- **Return to Filtered Bills**  
  When editing a Bill from a filtered list, you can now return directly to that same filtered view.

- **Clearer Invoice Numbers**  
  Invoice numbers are now clearly displayed at the top when editing an invoice.

- **Improved Invoice Navigation**  
  When editing invoices from a filtered list, you can now return to your previous filtered view without losing context.

---

### 🧠 Improvements & Enhancements

- **Better Invoice Readability**
  - The memo field now displays the full text.
  - Invoice numbers and values are shown in a larger, easier-to-read format.

- **Clearer Client & Job Information**
  - Client Contact fields now display only the company name.
  - Invoice tables now show full job names.

- **Smoother Editing Experience**
  - After saving changes to an invoice, you remain in the editing screen instead of being redirected.

- **More Complete Exports**
  - Invoice exports (Excel and CSV) now include all data from the selected invoices.

- **Improved Payments Visibility**
  - The Payments page now includes a Job column and Job filter.
  - The Bills page now includes a **Created By** filter to help locate bills more easily.

---

### 🐛 Bug Fixes

- **Correct Invoice Totals in Exports**  
  Fixed an issue where Excel and CSV exports showed incorrect invoice totals.

- **Bill Creation from Time Entries**  
  Fixed an issue where the Total Amount was not displaying correctly when creating Bills from time entries.

---
