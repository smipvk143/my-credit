# MY CREDIT - React + Vite App

## VS Code lo run cheyadaniki

1. Ee ZIP ni extract cheyyandi.
2. VS Code lo `my-credit-vite-app` folder open cheyyandi.
3. Terminal open cheyyandi.
4. Run:
   npm install
5. Tarvata:
   npm run dev
6. Browser lo Vite ichina local URL open cheyyandi (usually http://localhost:5173).

## Features

- Dashboard
- Daily / Home / Hospital sections
- Credit / Debit / Total
- Month filter
- Category filter
- Instrument filter
- Search
- Add / Edit / Delete transactions
- CSV export
- INR formatting
- Responsive mobile layout
- Data automatically saved in browser localStorage

## Important

Idi frontend-only version. Data Google Sheets/Supabase lo save cheyyadu; browser localStorage lo save chestundi.

Supabase or Google Sheets backend kavali ante next version lo login, database tables, cloud sync, admin users, PDF bills and reports add cheyyavachu.

### Daily filter update
Daily page now has **Money Sent / Money Received** and **UPI / Bank / Credit Card** filters in the requested order, plus month/category/search.


### Category Tree / 3-dot Filter
Category filter now opens a tree-style options menu with 3-dot markers, parent categories, child categories, and existing categories. Selecting a child applies the filter.
\n### Custom Hospital Category\nHospital entry Category now has Hospital-specific options plus an **Other — Type Category** input so you can type any custom hospital category.\n
### Inline Editable Category
Category in Add/Edit Entry is now a single editable text box with section-specific suggestions. No extra textbox is used. Hospital includes `Other Hospital` as a suggestion, and the category name can be typed or edited directly in the same box.
