# YoungDevInterns_Cyber-Security_Tasks

# ✅ Task 1: Set Up Basic Firewall Rules
## 🎯 Objective:

Configure Windows Defender Firewall to control access based on application or port.

🔧 Steps:
1. Open Windows Defender Firewall
     - Press Win + R, type control, press Enter.
     -  Go to System and Security > Windows Defender Firewall.

2. Turn on Firewall

    - Click on “Turn Windows Defender Firewall on or off.”
    - Make sure both Private and Public are turned ON.

3. Create Inbound/Outbound Rules

      - Click on “Advanced settings.”
      - Go to “Inbound Rules” > “New Rule…”
        
        - Choose Program or Port
        - Example: Block Port 21 (FTP):

                  - Select “Port” → “TCP” → “Specific local ports: 21”

                  - Choose “Block the connection”

                   - Apply to all profiles and give a name like Block FTP.

4. Allow an Application

   - Go back to main Firewall panel.

   - Click “Allow an app or feature through Windows Defender Firewall.”

5. Click “Change settings” → Enable or disable apps as needed.

     - Test the Rules

     - Use command: telnet <ip> <port> or try accessing apps.

# ✅ Task 2: Use a Password Manager
## 🎯 Objective:

Securely store and generate passwords using Bitwarden or LastPass.

🔧 Steps:

1. Install Bitwarden (Recommended)

     - Visit: https://bitwarden.com

     - Create a free account.

2. Download and Setup

     - Install the browser extension or desktop app.

     - Log in with your credentials.

3. Add Entries

      - Click + to add new logins.

      - Example: Add email and GitHub credentials.

4. Use Generator

      - Use password generator to create strong passwords.

       - Set length ≥16, include numbers/symbols.

5. Auto-Fill & Save

      - Enable auto-fill on login pages via browser plugin.

6. Security Tips

       - Use 2FA (Two-Factor Authentication).

       - Don't store master password in the manager.




# ✅ Task 3: Identify Phishing Emails

## 🎯 Objective:

Detect phishing indicators and report them.

🔧 Steps:
1. Review Common Signs

     - Suspicious sender address (e.g., paypal-security@gmail.com)

     - Spelling mistakes and urgency (e.g., "Your account will be blocked!")

     - Mismatched URLs

2. Identify 3 Examples

      - Use inbox or online examples (search "phishing email samples")

      - Take 3 screenshots of different phishing types:

           - Fake bank alert

           - Fake delivery notice

           - Fake job offer

3. Report Phishing in Gmail

     - Open the email → Click on the three dots (⋮) next to reply button (top-right of the email).

     - Select “Report phishing
