---
title: "The Hidden Cost of Open Source: When Libraries Change Licenses"
description: "Understand the risks of relying on open-source libraries and recent cases like MediatR and AutoMapper moving to commercial licenses."
image: "/images/open-source-libraries.png"
date: 2025-04-09T08:00:00Z
draft: false
---

In today’s fast-paced tech world, open-source libraries are everywhere. They help us build faster, ship sooner, and rely on community-tested solutions. But what happens when one of those libraries suddenly changes its license?

At **SeguraB**, our consulting work focuses on helping companies make sustainable technology decisions. Today, we want to bring attention to a crucial topic: **what happens when your project depends on open-source software that becomes commercial overnight**?

## Recent Examples: MediatR and AutoMapper

Two well-known libraries in the .NET ecosystem, **MediatR** and **AutoMapper**, have recently moved to **commercial licensing models**. This shift has caught many developers and organizations off guard.

These libraries were essential to countless personal and enterprise projects. Their original permissive licenses helped drive adoption. But now, teams are forced to:

- Pay for commercial licenses
- Find and migrate to alternatives (which may not be as stable or supported)
- Refactor large portions of existing code

### What's the impact?

- **Unexpected costs** in live or long-term projects  
- **Legal risks** from unknowingly violating new licenses  
- **Loss of trust** in external dependencies  
- **Time and effort** spent on migration or evaluation

## Practical Recommendations

At **SeguraB**, we advise our clients to follow these best practices when integrating open-source libraries:

1. **Always review the license before adopting**  
   Just because it’s on GitHub doesn’t mean it’s truly free to use in all contexts.

2. **Favor libraries with strong community or corporate backing**  
   Libraries like React, Vue, or Bootstrap are supported by large ecosystems, making sudden licensing shifts less likely.

3. **Audit your dependencies regularly**  
   Especially in enterprise settings, make it a habit to review your stack’s licenses every quarter.

4. **Have a backup plan**  
   Avoid tight coupling. Consider abstractions that allow swapping out key libraries if needed.

## What About Frontend?

Even though our focus at SeguraB is mainly on backend, frontend projects are just as vulnerable. For instance, UI libraries like **PrimeNG** or **Kendo UI** often have free tiers with crucial components locked behind a paywall.

Now imagine building your entire UI with one of these tools, only to realize the next release makes your essential components paid-only. You’d be faced with a tough choice: pay, or rewrite major parts of your app.

## Final Thoughts

Open source is powerful—but it’s not without risk. The decisions we make today regarding third-party dependencies can have lasting impacts on maintainability, legal compliance, and cost.

At **SeguraB**, we help teams not only build solid solutions, but also make technology decisions with foresight and responsibility.  

> _“The true cost of software isn't just in writing it—it's in maintaining, licensing, and evolving it.”_

---

**Have an active project and unsure if your stack is future-proof?**  
Let’s audit it together and plan with long-term sustainability in mind.
