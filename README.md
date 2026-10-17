# Behind the Shroud — Cytech CTF Write-Up

| Challenge | Category | Final Flag |
| :--- | :--- | :--- |
| **Behind the Shroud** | OSINT / Cyber Threat Intelligence | `Cryptix{OperationShroudedHorizon_12_M1rr0r}` |

---

## 📌 Challenge Overview

The challenge presents an investigative puzzle based on a viral internet cybercrime myth and the real-world investigation behind it:

> *"There's a viral story about a smiling hacker who was 'executed' for robbing 217 banks. He wasn't.*  
> *His partner didn't sell his creation on the open internet. He sold it in a private, invite-only marketplace, where only trusted members could enter, and the smiling hacker helped vouch for him there.*  
> *That marketplace was believed to be impenetrable. It wasn't."*

**Goal:** Answer three specific investigative questions based on real-world DOJ indictments and law enforcement disclosures to assemble the flag.

**Flag Format:**
```text
Cryptix{<Answer1>_<Answer2>_<Answer3>}
```

---

## 🔍 Context & Threat Intelligence Background

1. **The "Smiling Hacker":**
   * **Hamza Bendelladj** (alias **"Bx1"**), an Algerian cybercriminal photographed smiling broadly upon his arrest by Thai police in Bangkok in 2013.
   * Viral rumors falsely claimed he was executed for stealing from 217 banks and donating millions to Palestinian charities. In reality, he was extradited to the United States and sentenced to 15 years in federal prison.
2. **The Partner & Creation:**
   * Bendelladj partnered with Russian developer **Aleksandr Andreevich Panin** (aliases **"Gribodemon"** / **"Harderman"**).
   * Panin was the primary author and seller of the notorious **SpyEye** banking Trojan.
3. **The Private Marketplace:**
   * SpyEye was marketed and traded exclusively on **Darkode**, an elite, invite-only English-language cybercrime forum guarded by vetting processes where trusted actors vouched for new entrants.

---

## 🕵️‍♂️ Questions & Step-by-Step Investigation

### Question 1: The Takedown Operation

> **Prompt:** *Someone got inside and tore it down. What was the name of that operation? (without spaces)*

#### Investigation:
* In July 2015, the FBI, Europol, and law enforcement agencies across 20 countries coordinated a takedown targeting Darkode’s infrastructure, administrators, and prominent vendors.
* The operation was named **"Operation Shrouded Horizon"**.
* Removing spaces per challenge instructions: `OperationShroudedHorizon`.

**Answer 1:**
```text
OperationShroudedHorizon
```

---

### Question 2: Indictments on Leading Country Soil

> **Prompt:** *Dozens were targeted around the world, but how many were charged on the soil of the country that led it?*

#### Investigation:
* The multinational operation was led by the United States (FBI and U.S. Attorney's Office for the Western District of Pennsylvania).
* While around 70 individuals were arrested, searched, or charged globally, the U.S. Department of Justice press release explicitly unsealed indictments charging **12 individuals** under U.S. federal jurisdiction.

**Answer 2:**
```text
12
```

---

### Question 3: The Creator's Alias

> **Prompt:** *The man accused of building that marketplace hid behind many names. One of them looks back at you when you look at it. Bring it exactly as he wrote it.*

#### Investigation:
* In the federal indictment, **Daniel Placek** of Glendale, Wisconsin was charged with conspiracy to commit computer fraud for creating and maintaining Darkode.
* Placek used multiple handles: `Nocen`, `Loki`, `Juggernaut`, and `M1rr0r`.
* The alias that "looks back at you when you look at it" is **M1rr0r** (mirror).
* Retaining exact capitalization and leetspeak characters: `M1rr0r`.

**Answer 3:**
```text
M1rr0r
```

---

## 🚩 Final Flag Construction

Combine all three answers with underscores:
* **Answer 1:** `OperationShroudedHorizon`
* **Answer 2:** `12`
* **Answer 3:** `M1rr0r`

```text
Cryptix{OperationShroudedHorizon_12_M1rr0r}
```

---

## 📚 Primary Sources & Official Disclosures

* [U.S. Department of Justice — Major Computer Hacking Forum Dismantled](https://www.justice.gov/opa/pr/major-computer-hacking-forum-dismantled)
* [FBI News — Cyber Criminal Forum Taken Down (Operation Shrouded Horizon)](https://www.fbi.gov/news/stories/cyber-criminal-forum-taken-down)
* [DOJ Press Release — SpyEye Malware Developers Sentenced to 24+ Years](https://www.justice.gov/usao-ndga/pr/two-major-international-hackers-who-developed-spyeye-malware-get-over-24-years-combined)
* [Krebs on Security — The Darkode Cybercrime Forum Up Close](https://krebsonsecurity.com/2015/07/the-darkode-cybercrime-forum-up-close/)
* [Reuters — U.S. says computer hacking forum Darkode dismantled, 12 charged](https://www.reuters.com/article/markets/commodities/us-says-computer-hacking-forum-darkode-dismantled-12-charged-idUSL2N0ZV12P/)
* [Ars Technica — Criminal hacking bazaar Darkode is dismantled](https://arstechnica.com/tech-policy/2015/07/criminal-hacking-bazaar-darkode-is-dismantled-and-70-members-are-busted/)
* [Wikipedia — Hamza Bendelladj](https://en.wikipedia.org/wiki/Hamza_Bendelladj)
* [Wikipedia — Darkode](https://en.wikipedia.org/wiki/Dark0de)
