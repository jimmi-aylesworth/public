# Breaking the Juice Shop: Hands-On Web App Hacking with Kali Linux

There's a particular kind of clarity that only comes from breaking something on purpose.

You can read about SQL injection a hundred times. You can memorize the OWASP Top 10 like a catechism. But none of it really lands until you've slipped a `' OR 1=1--` past a login form and watched someone else's session fall open in front of you. That's the moment web application security stops being theory and starts being a skill.

That moment is exactly what these labs are built around.

## Why Juice Shop?

OWASP Juice Shop is, by design, the most broken web application you'll ever love. It's a modern single-page app — Angular front end, Node/Express back end, a real REST API — deliberately seeded with vulnerabilities that mirror the ones haunting production systems right now. Not toy bugs. The real stuff: broken access control, injection, busted authentication, security misconfigurations, and a long tail of subtler flaws that reward patience.

What makes it sing as a teaching tool is the gamification. Every successful exploit trips a hidden scoreboard challenge. You don't just think you found something — you get confirmation, a difficulty rating, and the nagging awareness that there are dozens more challenges you haven't cracked yet. It turns learning into a hunt.

## Why Kali?

Because the playground is only half the lesson. The other half is the toolkit.

Kali Linux puts the offensive practitioner's standard kit one terminal away — Burp Suite for intercepting and mangling requests, sqlmap for automating injection, the browser dev tools you'll learn to abuse, and a dozen smaller utilities you'll reach for once you know they exist. The labs walk through using these tools the way an actual attacker would: methodically, curiously, and with a healthy disrespect for whatever the developer assumed you'd do.

The goal isn't to memorize commands. It's to build the instinct — to look at an input field and immediately wonder _what happens if I don't play nice_?

## What you'll actually do

The labs move from reconnaissance to exploitation in the order that mirrors real engagements:

- Mapping the target — understanding the API surface before you touch it
- Authentication and access control — getting in where you shouldn't, and reaching data that isn't yours
- Injection — the classic flaws that refuse to die, and why they still work
- Client-side trust failures — what the browser hands you that it never should
- Chaining it together — because real findings are rarely a single bug


Each one is broken down so you understand not just how the exploit works, but why the flaw existed in the first place — which is the part that actually makes you better at defending systems too.

## Why I built these

I work both sides of the fence — red team and blue team — and I teach. Over the years I've found that the people who become genuinely good at security are the ones who got their hands dirty early and often. So I'm putting the labs, walkthroughs, and the field manual I use day-to-day out into the open, where anyone willing to put in the reps can use them.

If that sounds like something you'd find useful, take a look. Break something. Learn how it broke.

And if these labs save you some time, teach you something that sticks, or just scratch that hacker itch — consider buying me a coffee. It keeps the lab lights on and the next set of walkthroughs coming.

Happy hunting.

— _Jimmi_
