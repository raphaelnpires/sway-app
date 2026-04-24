# Sway - Project Info

## App Store

- **App Name:** Sway - Discover What Moves You
- **Bundle ID:** PiresFamily.Sway
- **Apple Developer Team ID:** LQJ8LFMFQD
- **Apple Developer Program:** Individual (Raphael Pires Nogueira)
- **Annual Fee:** $99/year (Renewal: April 7, 2027)

## Domain & Email

- **Domain:** swaytheapp.net (Namecheap, $12.48/year, expires Apr 9, 2027)
- **Email:** support@swaytheapp.net (Zoho Mail, $1/month)
- **Domain Privacy:** ON (WhoisGuard)
- **DNS:** Namecheap (MX records pointing to Zoho, A records pointing to GitHub Pages)

## Website (GitHub Pages + Custom Domain)

- **Repository:** https://github.com/raphaelnpires/sway-app
- **Homepage:** https://swaytheapp.net
- **Privacy Policy:** https://swaytheapp.net/privacy-policy.html
- **Terms of Service:** https://swaytheapp.net/terms-of-service.html
- **Support & FAQ:** https://swaytheapp.net/support.html

## Payments (Stripe)

- **Payment methods enabled:** Cards, Apple Pay, Amazon Pay, Cash App Pay, MB WAY, Pix, Samsung Pay, Google Pay, Klarna, Afterpay
- **Revenue split:** 80% creator / 20% platform
- **Backend API:** https://api-eaqw3eiukq-uc.a.run.app

## Firebase

- **Auth:** Email/Password + Sign in with Apple
- **Firestore:** Database
- **Storage:** Media files
- **Crashlytics:** Enabled (alerts go to both emails below)
- **Alerts:** Enabled for all events (email notifications)
- **Alert Recipients:** raphaelnpires@gmail.com + support@swaytheapp.net

## Cloud Functions

- **Monthly Summary:** Runs 1st of every month at 9 AM ET — sends email with users, revenue, subscriptions, tips, content, bug reports
- **Weekly Summary:** Runs every Monday at 9 AM ET — quick summary of the week
- **Bug Report Alert:** Instant email when a user submits a problem report in-app
- **Email via:** Zoho SMTP (support@swaytheapp.net)

## Platforms & Tools

| Platform | What it does | URL |
|----------|-------------|-----|
| **Stripe** | Processa pagamentos (assinaturas VIP, tips, custom requests) | dashboard.stripe.com |
| **Firebase Console** | Backend do app (banco de dados, autenticacao, crash reports, storage) | console.firebase.google.com |
| **Apple Developer** | Conta de desenvolvedor pra publicar na App Store | developer.apple.com/account |
| **App Store Connect** | Gerencia o app na App Store (submissao, reviews, analytics) | appstoreconnect.apple.com |
| **GitHub** | Hospeda o codigo do site (privacy policy, terms, support) via GitHub Pages | github.com/raphaelnpires |
| **Namecheap** | Registrador do dominio swaytheapp.net + configuracao DNS | namecheap.com |
| **Zoho Mail** | Email profissional (support@swaytheapp.net) | mail.zoho.com |
| **Xcode** | IDE pra desenvolver e compilar o app iOS (USAMOS - ferramenta principal) | Instalado no Mac |
| **Visual Studio Code** | Editor de codigo (NAO USAMOS - o projeto usa Xcode + Claude Code) | - |
| **Claude Code** | AI assistant que ajudou a construir o app (terminal) | Instalado no Mac |

## Accounts

- **Apple Developer:** raphaelnpires@gmail.com — publica o app na App Store
- **GitHub:** raphaelnpires (https://github.com/raphaelnpires) — hospeda o site
- **GitHub Token:** expires in 30 days (regenerate at github.com/settings/tokens)
- **Stripe:** (existing account) — recebe pagamentos dos usuarios
- **Firebase:** raphaelnpires@gmail.com (owner) + support@swaytheapp.net (viewer) — backend do app
- **Namecheap:** swaytheapp.net — dominio e DNS
- **Zoho Mail:** support@swaytheapp.net — email de suporte

## Monthly/Annual Costs

| Service                 | Cost                   |
|-------------------------|------------------------|
| Apple Developer Program | $99/year               |
| Domain (swaytheapp.net) | $12.48/year            |
| Zoho Mail               | $15/year               |
| Firebase                | Free tier (Spark plan) |
| GitHub Pages            | Free                   |
| **Total**               | **~$126.48/year + Stripe fees per transaction** |

## App Store Submission Checklist

- [x] Apple Developer Account active
- [x] Bundle ID registered (PiresFamily.Sway)
- [x] App created in App Store Connect
- [x] Privacy Policy hosted (swaytheapp.net)
- [x] Terms of Service hosted (swaytheapp.net)
- [x] Support page hosted (swaytheapp.net)
- [x] Screenshots taken (6)
- [x] Custom domain configured (swaytheapp.net)
- [x] Support email configured (support@swaytheapp.net)
- [x] DNS configured (Namecheap -> GitHub Pages + Zoho Mail)
- [x] Firebase Crashlytics enabled
- [x] Firebase alerts configured (both emails)
- [x] Cloud Functions created (monthly/weekly summary + bug alerts)
- [x] Email signature created
- [ ] Deploy Cloud Functions (firebase deploy --only functions)
- [ ] Set Zoho SMTP password in Firebase config
- [ ] Enforce HTTPS on GitHub Pages (wait for cert)
- [ ] App description & keywords
- [ ] Age rating questionnaire
- [ ] Upload build via Xcode
- [ ] Submit for review

## Total Money Spent (Development Phase)

| Item                           | Cost       |
|--------------------------------|------------|
| Apple Developer Program (1yr)  | $99.00     |
| Claude Pro - Month 1           | $20.00     |
| Claude Pro - Month 2           | $25.00     |
| Claude Pro - Month 3           | $20.00     |
| Claude Pro - Month 4           | $25.00     |
| Claude Pro - Month 5           | $45.00     |
| Domain swaytheapp.net (1yr)    | $12.48     |
| Zoho Mail (1 year)             | $15.00     |
| Firebase                       | $0 (free)  |
| GitHub Pages                   | $0 (free)  |
| Stripe                         | $0 (free until transactions) |
| **TOTAL SPENT**                | **$261.48** |

## Ongoing Monthly/Annual Costs

| Service                 | Cost                   |
|-------------------------|------------------------|
| Apple Developer Program | $99/year               |
| Domain (swaytheapp.net) | $12.48/year            |
| Zoho Mail               | $15/year               |
| Firebase                | Free tier (Spark plan) |
| GitHub Pages            | Free                   |
| **Total**               | **~$126.48/year + Stripe fees per transaction** |

## App Store Submission Checklist

- [x] Apple Developer Account active
- [x] Bundle ID registered (PiresFamily.Sway)
- [x] App created in App Store Connect
- [x] Privacy Policy hosted (swaytheapp.net)
- [x] Terms of Service hosted (swaytheapp.net)
- [x] Support page hosted (swaytheapp.net)
- [x] Screenshots taken (6 iPhone + 6 iPad)
- [x] Custom domain configured (swaytheapp.net)
- [x] Support email configured (support@swaytheapp.net)
- [x] DNS configured (Namecheap -> GitHub Pages + Zoho Mail)
- [x] Firebase Crashlytics enabled
- [x] Firebase alerts configured (both emails)
- [x] Cloud Functions created (monthly/weekly summary + bug alerts)
- [x] Email signature created
- [x] App description & keywords
- [x] Age rating questionnaire
- [x] Upload build via Xcode (Build 1.0 (1))
- [x] Submit for review (Submitted Apr 9, 2026)
- [x] TestFlight internal testing configured
- [ ] Deploy Cloud Functions (firebase deploy --only functions)
- [ ] Set Zoho SMTP password in Firebase config
- [ ] Enforce HTTPS on GitHub Pages (wait for cert)
- [ ] Activate Crashlytics email alerts at launch

## Pending Tasks (Pre-Launch)

- Customize Firebase password reset email template (Firebase Console → Authentication → Templates)
  - Change sender name to "Sway" 
  - Change reply-to to support@swaytheapp.net
  - For full custom SMTP (send from support@swaytheapp.net with signature), upgrade to Firebase Blaze plan
- Clean up test data from Firebase before going live (posts, test accounts, etc.)
- Deploy Cloud Functions (firebase deploy --only functions)
- Set Zoho SMTP password in Firebase config
- Final build submission to App Store review

## Pending Tasks (Post-Launch)

- Configure Apple Pay merchant ID (merchant.PiresFamily.Sway)
- Set up Stripe webhooks
- Move Stripe secret key to environment variable
- AI photo content filter (server-side)
- Activate Crashlytics email alerts at launch
