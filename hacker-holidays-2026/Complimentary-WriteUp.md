> **Platform:** TryHackMe
> 
> **Room:** Complimentary
> 
> **Category:** Cloud
> 
> **Tools Used:** Cloud, AWS, Cognito, IAM Misconfiguration

# Complimentary

**Date:** 2026-08-11

## Description

> **Concierge Briefing:**
> Lambo installed the Byte Lotus Wellness app the day she arrived — it was free, it had great reviews (written by the app, but she didn't check), and it got her a tote bag for saying yes to camera, mic, contacts, and location access. No account needed. No login screen. It just… knows things about you the moment you open it.
> That's the whole pitch: “complimentary” access, no friction, no sign-up. Something still has to be deciding what you're allowed to see, even without a login — and whatever that something is, it isn't checking very carefully.
> Your objective: find out how the app knows anything about you at all, and see what else it's willing to hand over.
>
> **ROOM ACCESS:**
> Target: 
>   [HTTP LINK]
> 
>  **TODAY'S ITINERARY**
> - Track down theAWS mechanism issuing you credentials behind the scenes.
> - Use those credentials to dump more than your own record from the app's DynamoDB table.
> - Retrieve the flag from another guest's data
>
> ** @0xMia's STORY **
> "okay wait, the wellness app never once asked me to log in and it STILL knew my name when I opened it 💀 something has to be quietly handing it access behind the scenes... if you find whatever that something is, don't just check what it gives YOU. ask it for more 👀"

---
