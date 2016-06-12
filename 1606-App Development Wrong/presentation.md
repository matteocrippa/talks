footer: © Matteo Crippa / boostco.de, 2016
slidenumbers: true

# App Development
### you are doing it
# **Wrong**

---

# [fit] **5**
## tips to improve your (app)
# [fit] **security**

---

> **Hacking & Phishing** is done by professionals.
-- mr. Obvious

---

> :family: are the biggest security issue in your App
-- ~~Chinese~~ Developer proverb

---

# 1. Alert them if **VPN** is required

A lot of :family: forget to activate their **VPN** tunnel before using your app.

Be smart, provide them a feedback about this and also guide them on how to activate it.

----

# 2. Passwords are user's worst nightmares

:family: hates to manage and deal with passwords, this make them vulnerable using **stupid common** passwords.

If you are working with devices with **finger printing** detector sensors, makes use of this technology (eg. **TouchID**) in order to improve security vs password laziness.

---

# 3. Tame your logs

During app development, **logs** save you a lot of :hourglass:.

But, please, **disable** them when you turn your app in production.

Looking at logs someone can discover easily issues or flows and use them.

---

# 4. Jailbreaking, hurts

> iOS apps are secure, are sandboxed, etc etc.

This works fine till a device is **jailbreaked**. Since that very moment you can start having fun looking inside your app directory, code and going on.

Avoid to add sensitive data inside **plists** files and encrypt as much as you can storing the sensitive data inside the keychain.


---

# 5.
