# IDOR demos Walkthroughs

# Overview

This repository contains **three detailed walkthroughs** of vulnerable demo applications, that I sent you, designed to demonstrate **Insecure Direct Object Reference (IDOR)** vulnerabilities.
Each walkthrough explains how to:

* run the webapp
* identify, exploit, and understand IDOR flaws in a hands-on manner.

---

## Repository Structure

* **[IDOR](./IDOR/walkthrough.md)** → Walkthrough of the first IDOR demo
* **[IDOR2](./IDOR2/walkthrough.md)** → Walkthrough of the second IDOR demo
* **[IDOR3](./IDOR3/walkthrough.md)** → Walkthrough of the third IDOR demo

---

## More IDOR

Below are live/interactive exercises (CTF challenges) I recommend for practicing IDOR / broken access control.
Make sure to create accounts on the platforms beforehand (PortSwigger, picoCTF, TryHackMe) so you can jump right in!

### PortSwigger — Insecure Direct Object References (Web Security Academy)

[https://portswigger.net/web-security/access-control/lab-insecure-direct-object-references](https://portswigger.net/web-security/access-control/lab-insecure-direct-object-references)

A solution is provided in the lab by PortSwigger; you can follow it if you get lost or give up.

---

### picoCTF — Cookies challenge (practice)

[https://play.picoctf.org/practice/challenge/173](https://play.picoctf.org/practice/challenge/173)
**Note:** *Make a picoCTF account beforehand.*
Writeup: [https://tomsitcafe.com/2024/03/08/picoctf-cookies-ctf-write-up/](https://tomsitcafe.com/2024/03/08/picoctf-cookies-ctf-write-up/)

---

### TryHackMe — Neighbour (room)

[https://tryhackme.com/room/neighbour](https://tryhackme.com/room/neighbour)
Writeup : [https://github.com/riyyoo/TryHackMe-Neighbour-Walkthrough?tab=readme-ov-file](https://github.com/riyyoo/TryHackMe-Neighbour-Walkthrough?tab=readme-ov-file)

**How to join & run :**

1. Log in to TryHackMe and open the **Neighbour** room URL above.
2. Click **“Join Room”** (if required) to add it to your list.
3. On the room page click **“Start Machine”** (green button).
4. Wait for the machine to boot (the room will show the target IP when ready).
5. Launch the AttackBox and browse to `http://<TARGET_IP>` and start hacking.
6. When finished, **Stop** the machine to free resources.

**Tip:** consult the linked writeup only after trying yourself — it’s good for hints or verification.

---

### TryHackMe — Corridor (room)

[https://tryhackme.com/room/corridor](https://tryhackme.com/room/corridor)
Writeup: [https://medium.com/@jamesjarviscyber/corridor-tryhackme-ctf-write-up-6ca3f2a09bca](https://medium.com/@jamesjarviscyber/corridor-tryhackme-ctf-write-up-6ca3f2a09bca)

**How to join & run :**
Same steps as the previous TryHackMe challenge.

---
