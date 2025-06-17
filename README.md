# 🛡️ Cross-Site Request Forgery (CSRF) Labs

My personal lab notes and learning journey through PortSwigger’s **Web Security Academy — CSRF chapter**.

This repository is a curated collection of hands-on labs I completed to explore CSRF vulnerabilities: how they work, how to exploit them, bypass weak defenses, and understand their real-world business impact.

🔗 [Web Security Academy - CSRF](https://portswigger.net/web-security/csrf)

---

## ⚙️ Environment Setup

All labs were completed in a virtual testing setup using:

- Kali Linux (VirtualBox VM)
- Burp Suite Community Edition
- Firefox Developer Edition + FoxyProxy
- Local HTTP server (`python3 -m http.server`)
- GitHub Pages (optional for PoC hosting)

---

## 📚 What I Learned

### 🔸 What is CSRF?

CSRF (Cross-Site Request Forgery) is an attack that forces an authenticated user to unknowingly perform actions on a web app using their active session.

### 🔸 Techniques & Topics Covered

- CSRF fundamentals and real-world use cases
- Hidden form auto-submission techniques
- Understanding CSRF tokens and their weaknesses
- Using cookies, Referer headers, and SameSite attributes
- Bypassing broken or misused token implementations
- Business impact: account takeover, privilege abuse

### 🔸 Tools Used

- Burp Suite (Repeater, Proxy)
- Firefox DevTools
- HTML Form Exploits
- GitHub Pages for PoC hosting

### 🎥 Sources

YouTube tutorials (LiveOverflow, STÖK), OWASP CSRF cheat sheet, PortSwigger blog posts, and Academy labs.

---

## 🧪 Lab Progress

> ✅ = Completed with working PoC and documented
> 💡 = Includes analysis, screenshots, and ethical discussion

🔹 **Basic CSRF Attacks**
- ✅ Lab 01: CSRF vulnerability with no defenses
- ✅ Lab 02: CSRF where token is not validated
- ✅ Lab 03: CSRF where token is duplicated in cookie

🔹 **Token & Header Bypass**
- ✅ Lab 04: CSRF with broken Referer validation
- ✅ Lab 05: CSRF with token in Referer header

---

## 🛠️ Automation & Future Plans (Coming Soon)

I'm planning to:

- Write JS/Python helpers to automate CSRF payload generation
- Generate browser-compatible CSRF pages dynamically
- Explore token brute-force automation and bypass strategies

---

## 📸 Documentation (Ongoing)

Each lab includes:

- ✔️ Exploitation steps (markdown)
- ✔️ Screenshots from Burp and browser
- ✔️ Security impact summary
- ✔️ Fix & prevention recommendations

---

## 📌 Notes

- 🧠 This project is for **educational purposes only**.
- ✅ All labs were conducted in a safe and legal environment provided by **PortSwigger Web Security Academy**.
- 💬 For questions or collabs, feel free to [DM me on LinkedIn](https://www.linkedin.com/in/kaouthar-belkebir/).

---

## 🧠 Next Steps

- Add real-world case studies of CSRF breaches
- Translate write-ups in French 🇫🇷
- Post weekly breakdowns on LinkedIn #PentestChallenge
- Expand to other categories (e.g. XSS, Authentication, Access Control)

---

**Made with 💻 Burp, ☕ focus, and 🧠 curiosity**  
by *Kaouthar Belkebir*
