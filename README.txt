QUICKBUY — FREE STARTER WEBSITE

WHAT THIS IS
A mobile-friendly storefront prototype for QuickBuy. It includes product browsing, search, category filters, a demo cart, seller information and a demo referral area.

OPEN IT
1. Extract the ZIP file.
2. Open the quickbuy folder.
3. Tap index.html and choose Chrome.
4. To publish it free, create a GitHub account with help from a parent/guardian if needed, create a public repository named quickbuy, upload index.html, style.css and app.js, then enable GitHub Pages in the repository Settings > Pages. GitHub will show the public website address.

IMPORTANT LIMITATIONS
This is a front-end starter/demo. The products are sample data. Cart, seller action and referral display are demonstrations only. There is no real account registration, database, order management, secure admin login, referral attribution, payment processing, payment verification, payout, or earnings tracking yet. Do not collect real customer information or accept payment based on this demo.

NEXT BACKEND STEP
Connect a Supabase project for persistent data and authentication. Keep database access protected with Row Level Security. Admin privileges must be assigned and checked server-side; never add a public admin toggle or hardcode an admin password. The Supabase public anon key may be used in a browser only with properly configured RLS policies. Never expose a service-role key. Payment provider credentials belong only in secure server-side environment settings, and a parent/guardian should handle provider account setup and compliance.

MONETIZATION
Legitimate future revenue can come from clearly disclosed seller commissions or referral rewards on verified completed orders. Advertising requires approval from an ad provider. Visitor mobile data charges go to their network provider, not to QuickBuy.


REAL USER ACCOUNTS: This package now includes Supabase email/password authentication. Follow SETUP.txt and run supabase-schema.sql before publishing. Accounts will not work until the Supabase project URL and anon/public key are added to supabase-config.js.
