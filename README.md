# Local Area App – V1 Demo

Green mobile-first HTML prototype.

## Demo Login
- Enter any 10-digit mobile number.
- OTP: `123456`
- To show the demo Admin screen, use a mobile number ending in `0000`.

## Important
This version is a frontend prototype. Data is stored only in browser memory/localStorage for login.
For production, connect Supabase for:
- Mobile OTP authentication
- Users and roles
- Shop owner ownership/RLS
- Shop/news/job approval
- Photo storage
- Comments/reports
- Notifications

## Vercel
Upload this folder to GitHub, import the repository into Vercel, and deploy as a static site. No build command is required.

## Production database tables
profiles, shops, shop_photos, jobs, news, comments, reports, favorites, notifications, admin_actions
