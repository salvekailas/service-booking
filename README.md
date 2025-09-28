# Service Booking Website

## Steps to Deploy

1. **Google Sheets Setup**
- Create a sheet with tabs: Requests, Engineers, Config
- Fill Config with services (AC Repair, Plumbing, Electrical)
- Fill Engineers tab with preassigned engineers if desired

2. **Google Apps Script**
- Open Extensions → Apps Script in Google Sheet
- Paste apps-script.txt code
- Deploy as Web App → Anyone, even anonymous
- Copy Web App URL → Replace "YOUR_SCRIPT_WEBAPP_URL" in HTML files

3. **Frontend Hosting**
- Create GitHub Repository
- Upload HTML/CSS files
- GitHub Pages → main branch → Publish

4. **Payment Setup**
- Use Razorpay Test Mode → Replace test key in track.html

5. **Admin Login**
- Username: admin
- Password: admin
