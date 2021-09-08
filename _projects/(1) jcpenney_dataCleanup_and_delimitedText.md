---
name: Data Cleanup and Delimited Text
tools: [LDAP, XML, CSV]
image: https://static.thenounproject.com/png/2942557-200.png
description: ~customer~ had a multi-year, multi-phase plan put together to modernize their data that had been following decades-old, outdated guidelines. As a preliminary effort, I was tasked with assisting the cleanup and restructuring of over 300,000 user objects as well as thousands of other roles and resource objects in preparation for the future steps of their modernization plan.
---

# Decades-Old Data

At the ~customer~ company, their footprint around the world has been around for a long time. Because of this, many legacy solutions are deployed and used in their production environment. Since these legacy options are becoming not only more insecure, but rapidly losing support, ~customer~ worked to take action to future-proof their company data. Other Architects took the time to analyze the entire environment. After their design plan was pulled together and agreed to, I was tasked with kneading through the data by: identifying problems and inaccuracies, providing solutions to removing orphaned accounts, schema, and attributes, and rebuilding the user information where required. This was mostly achieved through Apache Directory Studio's tools - using LDAP Queries to identify the problems, and capturing .ldif files for correcting the data. <br>
<br>
It should also be noted that these data correction solutions not only had to apply to a centralized eDirectory environment, but as well as over half a dozen other ADAM and AD environments. The centralized eDirectory environment overtime had been exporting the old/bad data into these other environments. The methods to correct these were two-fold: Leveraging eDirectory's built in tools to push the corrected data out to the connected environments, as well as similar Apache DS/.ldif corrections that were deployed directly in eDirectory.

#![preview](https://upload.wikimedia.org/wikipedia/en/thumb/c/c8/Apache_Directory_Logo.svg/1200px-Apache_Directory_Logo.svg.png)

<p class="text-center">
{% include elements/button.html link="https://github.com/YoussefRaafatNasry/portfolYOU" text="Learn More" %}
</p>
