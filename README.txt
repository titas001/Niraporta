BRAC NIRAPATTA - INTERACTIVE PROTOTYPE
BRAC IT

HOW TO OPEN
1. Unzip this folder.
2. Double-click BRAC_Nirapatta_Prototype.html (Chrome or Edge recommended).
3. Click anywhere once so the browser allows the SOS sound.
4. Before each presentation: dashboard top-right, Kollol Nag menu > Reset demo data (click twice).
Dates always follow today's date and time. Works offline. No installation, server or internet needed (Bengali font is built in).

DEMO LOGINS (any 6-digit OTP)
- Md. Rahim Uddin: Continue with SSO, or PIN 102934
- Sharmin Akter: PIN 874022
- Abdul Karim: PIN 556010 (shows the health & family form)
- Karim Hossain (self-registered): verify him in Users first, then Mobile tab 01812345678

TWO-MINUTE DEMO SCRIPT
1. Reset demo data, click once to enable sound.
2. Phone: Continue with SSO, fill Emergency Health & Family Contact, Save.
3. Tap SOS, let the 3-second countdown run: dashboard sound + toast, alert jumps to top (x2 badge).
4. Dashboard: open the alert, Acknowledge & Respond - phone shows "responding".
5. Add closure note, Mark Resolved - phone shows resolved.
6. Click Simulate SOS - a new alert from another branch arrives live.
7. Phone: Report > tick "on behalf", add colleague, record voice note, submit - reference number,
   new row on Incidents page, Open Incidents count rises.
8. Broadcast: send a Weather Alert - phone bell badge, Security Alerts and Latest Advisory update.
9. Switch phone to Bengali; Settings > Require Emergency Health & Family Contact removes "Skip".

AUTOMATED TESTS (optional, for developers)
pip install playwright && playwright install chromium
python nirapatta_qa_tests.py      (73 tests; keep it in the same folder as the HTML file)
