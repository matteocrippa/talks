autoscale: true
footer: © Matteo Crippa / boostco.de, 2016
slidenumbers: true

# iOS App Development
### you are doing it
# Wrong

# :no_good:

---

# [fit] :five:
## tips to improve your (app)
# [fit] **security**

---

> **Hacking & Phishing** is done by professional :sunglasses:.
-- mr. Obvious

---

> :bow: are the biggest security issue in your App
-- ~~Chinese~~ Developer proverb

---

# 1. Alert :speech_balloon: them if **VPN** is required

A lot of :bow: forget to activate their **VPN** tunnel before using your app.

Be smart, provide them a feedback about this and also guide them on how to activate it.

----

# 2. Passwords are user's worst nightmares :japanese_goblin:

:bow: hate to manage and deal with passwords, this make them vulnerable 'cuz they are using **stupid common** passwords.

If you are working with devices with **finger printing** detector sensors, makes use of this technology (eg. **TouchID**) in order to improve security vs password laziness.

---

# 3. :horse: Tame your logs

During app development, **logs** save you a lot of :hourglass:.

But, please, **disable** them when you turn your app in production.

Looking at logs someone can discover easily issues or flows and use them.

---

# 4. Jailbreaking, hurts :cop:

> iOS apps are secure, are sandboxed, etc etc.

This works fine till a device is **jailbreaked**. Since that very moment you can start having fun looking inside your app directory, code and going on.

Avoid to add sensitive data inside **plists** files and encrypt as much as you can storing the sensitive data inside the keychain.


---

# 5. RTFM :books:

There are really interesting (& free) resources about app security:

- [iOS Developer cheatsheet by OWASP](https://www.owasp.org/index.php/IOS_Developer_Cheat_Sheet)
- [OSX Secure Coding](https://developer.apple.com/library/mac/documentation/Security/Conceptual/SecureCodingGuide/Introduction.html)

---

## ![inline 40%](boostco.de.png)
### boostco.de
