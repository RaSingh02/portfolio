---
title: "Fire Drills"
date: 2022-03-29
draft: false
author: "Randeep Singh"
Description: "This post will be talking about the practices of fire drills in software development."
---

### What are fire drills?
Fire drills are practices in software development meant to explore scenarios that can break projects. They can help explore them and identify additional work needed to prevent such incidents from occurring and preventing future issues. Many companies have systems in place to force engineers to create resilient products at the beginning instead of rushing out half-baked ideas that may fail when stressed. A famous system that comes to mind is Netflix's Chaos Monkey. Chaos Monkey will randomly kill servers in the system or other portions of the system. As stated before, this forces engineers to create resilient software, such that they can continue to operate even when individual machines or systems fail. This approach is beneficial for larger companies as their development and team sizes grow regularly. On the other hand, this also means that smaller companies with less sophisticated systems will not benefit from this approach.

### Benefits
Running fire drills can help find obvious changes that may be overlooked since they are so simple. For example, improving access to databases or having multiple backup options for the database itself. Fire drills can help uncover obscure failures as they dig through the cracks and crevices of software applications. However, the nature of these drills will vary from scenario to scenario. Each team has its own different needs. They include communication, documentation, and other human factors whereas Chaos Monkey's downside is that it narrows in on software design. 

### DiRT
This is Google's own version of fire drills. They emphasize that it is important to not point fingers at any single individual or team but to accept that things do go wrong in reality. Instead, emphasis should be on improving systems to prevent any future incidents to occur. Teams need to recognize that there is value in learning about disasters even if it does chip away at the budget. In the case of DiRT, it involves the work of hundreds of engineering and operations personnel over a time period. It has even caused accidental outages and revenue loss for Google. But the bright side is that since it is a company-wide event, the right personnel are there to help contain issues that may arise from these drills. 