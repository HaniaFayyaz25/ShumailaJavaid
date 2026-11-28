SHUMAILA JAVED PORTFOLIO

Live website: https://shumailajavaid.vercel.app

PORTFOLIO MANAGER
1. Open https://shumailajavaid.vercel.app/#admin
2. Sign in with the authorized admin email shown in the form and its password.
3. For first-time setup or a forgotten password, select “Set / reset password”.
4. Open the password setup email and follow its link. The authentication callback should return to the Portfolio Manager, including when Supabase adds callback parameters to the URL.
5. Set the password, then sign in to manage the portfolio.
6. Use the Projects form to add a title, category, description and image. Existing projects can be edited or deleted.

Changes are saved directly to the Supabase database and appear on the public portfolio. No GitHub edits or manual redeployment are needed.

The manager also supports profile updates and backup export/import. Access is restricted to the authorized admin email in the portfolio_admins table. The live website must be included in the Supabase Authentication URL Configuration redirect allowlist.
