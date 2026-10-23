# Session 2 - Expanded Speaker Script (English)

Expanded version: you can read it almost word-for-word if you get stuck, or read it a couple of times and say it in your own voice.
Per slide:
- **Open** - how to enter the slide (a line or two).
- **Say** - the full body, written to be spoken out loud.
- **If asked / Emphasis** - a ready answer to a common question (where relevant).
- **Land** - the one line to leave the slide on.

Pace: slow, sentence by sentence. Main slides: 16. Appendix A1-A4 is backup, only if asked.

---

## 1 - Hero: "Keep the 9800, four times the reach"

**Open:**
"Thanks for making the time. I promise to be focused - I have one idea and one ask today, and that is it."

**Say:**
"You already run one of the best boxes in its class - the Quantum 9800. I am not here to re-sell it to you, and I am not here to replace it. I am here to show you how to get four times the encrypted reach out of it, without changing anything. Same prevention you already know, same management console, same support contract. The only difference is one card that drops into a slot you already have in the box."

**Land:**
"No new chassis, no migration - just more reach from the box already in your rack."

---

## 2 - Where you are today: "Best-in-class today, almost no room left"

**Open:**
"First, let me reflect back what you run, so we start from the same place."

**Say:**
"You have a 9800 pair in High Availability - one active, one on standby. Together they inspect about eight gigabits per second of encrypted traffic today, at a 99-percent-plus block rate. That is excellent - genuinely best-in-class prevention. But here is the quiet problem: you only have about two gigabits of headroom left before the ceiling. You are already close to the edge of what the box can do - exactly as traffic keeps climbing."

**If asked "why eight gigabits?":**
"That is an illustrative profile for a customer your size - we measure the real number together in the PoC. The principle holds: you are near the ceiling."

**Land:**
"Best-in-class prevention, but near the ceiling. Wait, and the choice becomes a blind spot or a forklift."

---

## 3 - The 9000 line you run on: "Top of the line, already on AI"

**Open:**
"A quick reminder about the platform itself - because everything I propose builds on it, not instead of it."

**Say:**
"The 9000 is one family that serves everything, from the small branch to the large headquarters. One operating system - GAiA. One management console - SmartConsole. And the same threat-intelligence engine, ThreatCloud AI, runs on every model. So you are already on best-in-class, AI-driven prevention - that is not something I need to sell you, it is already yours."

**Land:**
"You are already running best-in-class, AI-driven prevention - that is the foundation to keep in mind."

---

## 4 - Why now: "More to decrypt, more hiding inside"

**Open:**
"The fair question is 'why now, and not a year from now?'. Let me show you the curve."

**Say:**
"Three numbers tell the whole story. First - about 95 percent of traffic today is encrypted. What you do not decrypt, you simply do not inspect. Second - the load you have to inspect roughly doubles every three years, and GenAI tools and AI agents are pushing that curve even higher. Third - encrypted traffic is now the number-one hiding place for attacks, precisely because inspecting it is expensive. Look at the chart: the curve of what you must inspect keeps rising, and it is about to cross the ceiling line of the box you own."

**If asked "is this chart exact?":**
"It is an illustrative index, anchored to the deck's numbers - not a forecast of your traffic. The trend is what matters."

**Land:**
"The curve only climbs - and it is about to cross the box you already own."

---

## 5 - The squeeze on your pair: "One failover, and the headroom is gone"

**Open:**
"Let me show you what 'near the ceiling' actually means when you have a pair. This one is interactive - let me illustrate a failure."
*(Click 'Illustrate a gateway failure'.)*

**Say:**
"In High Availability, the moment one box fails, the other has to carry the entire load alone. At today's eight gigabits that is already tight. In two years, with the growing load, it simply does not fit. And that leaves you with three options - all of them bad. One: inspect everything and hit the ceiling - users feel it, and a failover has nowhere to land. Two: stay fast and turn inspection off - but then you go blind to most of your traffic, exactly where the attacks hide. Three: buy your way out - either idle iron now, or a forklift later."

**Land:**
"The tax here is not only throughput. It is visibility, rack space, and the next project."

---

## 6 - Why Quantum, differentiator 1: "Fewer tools, fewer blind spots"

**Open:**
"The first reason: this is one platform, not a pile of tools you have to stitch together."

**Say:**
"One console, one policy, one team. Think of it this way: every hand-off between two point products is a seam - and at every seam a policy can be missed, or a log never gets correlated with another. When everything sits on one platform, those seams simply disappear - across network, cloud, and users. And there is a bonus: Infinity AI Copilot helps draft and audit rules, so the same team manages more gateways without adding people. So this consolidation is not only cheaper - above all, it is fewer places for an attack to hide."

**Land:**
"Fewer seams between tools is fewer places for an attack to hide."

---

## 7 - What we solve: "All your encrypted traffic, in the box you own"

**Open:**
"So before I show the product - here is the promise, in one line."

**Say:**
"Four times the reach, none of the project. Same prevention, same console, same contract. How? We move the TLS work and the prevention onto a dedicated card - and that frees your CPU back up for policy and apps. Four things happen at once: prevention is not touched, the CPU is freed, nothing operational moves - same GAiA, same SmartConsole, same HA pair - and you get capacity exactly when traffic asks for it, not four idle boxes and not a forklift next year. Every other path to this capacity ends in a new chassis."

**Land:**
"More inspection, a freer CPU, no migration. That is the sale - not just a bigger throughput number."

---

## 8 - What we are selling: "One card, one spare slot"

**Open:**
"Here is the whole product, on one table. One card, into the spare I/O slot you already have."

**Say:**
"The card is an NVIDIA BlueField-3 DPU, and it drops into the spare I/O slot you already have - nothing else in the box changes. Why a card and not a new box? Because when prevention sits on flexible hardware, the next engine arrives as an update. With the competitors, prevention is burned into a fixed ASIC, or needs a bigger chassis - and then every new engine becomes a forklift. A card does not do that. On the next slide I will show you exactly what moves onto the card, and the throughput it buys."

**If asked "isn't this just a NIC?":**
"No. BlueField-3 has its own Arm cores, so it can run IPS - and later an AI engine - on the card, not just accelerate crypto like an ordinary network card."

**Land:**
"One card, into a slot you already own. You gain reach and a free CPU - and you skip the forklift."

---

## 9 - Same box, before and after: "Same 9800, ~10 to ~40 Gbps"

**Open:**
"Let me show you side by side, on the exact same box. There is a toggle here - 'Today' versus 'With the card'."
*(Toggle 'Today' and 'With the card'.)*

**Say:**
"Today, TLS, prevention and policy all share one CPU. And that is what pins you at around ten gigabits. Now add the card: TLS decrypt and re-encrypt, plus the IPS, antivirus and anti-bot engines, all move off the Xeon and onto the DPU's dedicated silicon - and the Xeon is freed back up for policy and apps. The target is about forty gigabits of full inspection - four times. And notice what does not change: same NIC, same Firewall ASIC, same chassis. The grey on screen is everything that stays exactly as it is."

**Land:**
"Grey is what you keep. About four times the reach - same box, same console, same contract."

---

## 10 - Installing it: "No outage, your usual change window"

**Open:**
"I know the real question is 'how painful is this to install'. The answer: it is exactly the maintenance window you already run."

**Say:**
"Four steps. One - fail over to the standby, just like any maintenance. Two - seat the card in the spare slot of the first box, and bring it back up with the offload on. Three - move traffic to it, and repeat the same thing on the second box. The pair is never both down, and the policy never moves. And the rollback is the simplest there is: turn the offload off, and the CPU keeps enforcing the exact same policy. You only pull the card physically if you truly have to."

**If asked "what if the card fails?":**
"Inspection falls back automatically to the CPU path, at lower throughput - but prevention stays, the exact same policy."

**Land:**
"Turn offload off, and nothing changes but speed. You pull the card only if you must."

---

## 11 - Why it pays: "Three paths to ~40, one keeps the platform"

**Open:**
"There are three ways to reach the same forty gigabits. Same result - very different cost. This is interactive, you can click each option."

**Say:**
"Option one - over-provision up front: four boxes on day one, about 88 thousand dollars, with half the iron sitting idle. Option two - ride the 9800 until it hits the wall, then replace it: about 110 thousand, and you pay twice plus you go through a migration. Option three, and this is my proposal - add the card: about 37 thousand dollars, target. Same rack, same console, same contract - and there is always a way back."

**Land:**
"Same forty gigabits. Only the card keeps the rack, the console, the contract - and a way back."

---

## 12 - Cost per inspected gigabit: "Beyond the gigabit, you still win"

**Open:**
"Now let's talk money the right way. Stop pricing the box - price the work that actually gets inspected."

**Say:**
"If you take the three-year cost, and divide it by every ten gigabits of full inspection that actually runs - here is the picture. The 9800 with the card comes out at about 9.3 thousand dollars. Fortinet about 14 thousand. The 9800 today, without the card, about 22 thousand. Cisco about 30 thousand. And Palo Alto about 43 thousand. I want to be fair with you: these are analyst estimates, normalized to a per-box cost at the ten-gig tier - not quotes. But the direction is very clear."

**If asked "where do the numbers come from?":**
"The Decryption Digest 2026 pricing guide, combined with the vendors' datasheets - all linked in the sources at the bottom of the slide."

**Land:**
"The chart is the money. But the win is also prevention, the rack, the console - and no forklift."

---

## 13 - The slot keeps giving: "Throughput today, upgrades on the same slot"

**Open:**
"One more point that matters to a CISO thinking ahead: this investment is protected over time. And that is because it is programmable silicon, not a burned-in ASIC."

**Say:**
"Today, the card buys you the one thing we are asking for right now - four times the inspection. But the same slot keeps giving. The next step: AI-based threat detection running on the card's own Arm cores - without loading the CPU that runs your policy. And after that: post-quantum crypto, arriving as a firmware update to the card - not a new appliance. With the competitors, each new engine like this means a new box and a migration. For you - it is a field upgrade, on the same 9800."

**Land:**
"A fixed ASIC means a new box for every new engine. A programmable slot means the box you own keeps growing."

---

## 14 - Can you trust the silicon: "Your engines, on silicon that already ships"

**Open:**
"A completely fair question you are probably asking in your head: is this proven, or a science project? I have three answers."

**Say:**
"First, the prevention: these are your existing engines, still fed by ThreatCloud AI - the exact same block rate. The card moves the location of the work, not the protection itself. Second, the silicon: BlueField-3 already ships and runs in production today - Check Point's AI Factory Firewall already runs on it to protect AI systems. Same silicon family, just pointed at your perimeter. And third, the accountability: you buy one Check Point product. Support, signatures, policy - all from us. The DPU is a component inside the product, exactly like the CPU or the NIC. This is not a support contract with NVIDIA."

**Land:**
"Same prevention, same vendor, silicon already in production. The card moves the work - not the trust."

---

## 15 - Straight answers: "The hard questions, answered first"

**Open:**
"I want to answer the hard questions before you even have to ask them. These are exactly the things I would check in your seat."

**Say:**
"Policy miss? There is one rule base in SmartConsole; if a block, a log or an exception behaves differently from the normal path - you turn offload off, and the CPU enforces the exact same thing again. Vendor lock-in? There is an abstraction layer between policy and chip, so generation two can target other silicon - without touching your policy. What if there is no card at all? The 9800 is excellent today without it - the slot is upside, never a dependency. And when? It is a gated roadmap: kickoff in Q1 of 27, PoC in Q3, beta in 28, then GA. Every date after the first has a gate in front of it - if the PoC misses the target, we simply do not proceed."

**Land:**
"This is upside on a box that is already best-in-class. You risk a span port for a month - not your perimeter."

---

## 16 - Your next step: "30 days, on your 9800"

**Open:**
"So what is the actual ask? One thing: a 30-day Proof of Value, on your own pair, with no new hardware to ship."

**Say:**
"Here is how it looks. Week one - we baseline on a span port, in monitor mode only, and measure your real encrypted load and your block rate. Nothing inline, no policy change. Weeks two and three - we turn on full TLS inspection, one hundred percent, on your own policy, and then we fail over one gateway on purpose - and you watch full inspection keep running and the surviving box hold the load. Week four - you score it: same blocks, same logs, same exceptions as today. And then we model the four-times reach, from about ten to about forty gigabits, and price the card into your three-year plan."

**Land:**
"A span port, your real traffic, one maintenance window. You walk away with measured numbers - and a three-year plan."

---

## Appendix (only if asked)

**A1 - vs Fortinet / Palo Alto / Cisco:**
"On prevention we are equal or better, and in the rack we lead - 1RU against their 3 to 5RU. And most important: our next engine is a card, not a new box."

**A2 - Prove the TLS numbers:**
"I am not asking you to take the number on faith - we prove it on your traffic in the PoC. Full TLS, on your own policy, measured on a span port."

**A3 - Compliance and certifications:**
"It is the same Check Point product, the same certification path - FIPS, Common Criteria. The DPU is a component inside it - submitted early for approval, not after GA."

**A4 - When is the card available:**
"Design partners first, then a gated roadmap to GA. Every date after the first has a gate in front of it - a responsible roadmap, not a promise."
