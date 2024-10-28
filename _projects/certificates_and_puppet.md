---
name: Certificates & Puppet
tools: [Certificates, OpenSSL, Puppet, SSL, HTTPS]
image: https://ee2cc1f8.rocketcdn.me/wp-content/uploads/2024/07/SSL.png
description: Abundant applications required abundant certificate updates and monitoring
---

# It's always the certificates

At another customer site, they had gone through many changes of leadership and employees so that some of the information about their environment had gone unknown and unaddressed for quite some time. Most of the efforts in the beginning were basically to fix issues when they arose and then make note of the situations for future reference when the issue arose again. This obvioulsy was unsustainable and forced the environment into downed situations, affecting the end users on a semi-frequent basis. As part of their effort to make things better I was tasked with identifying all self-signed and public certificates involved with their environment specific to NetIQ Cybersecurity products and other 3rd party products that tied into it. After all was said and done we identified around 160 public iterations of their SSL Certificates, and several dozen self-signed certificates. We were able to account for all these expiration dates and processes required to update them, thus improving the uptime of their environment overall.

There did, unfortunately, arise a "rogue" certificate, as we decided to call it - which was a 3rd party product I was unfamiliar with - but was clearly integrated with eDirectory for authentication and provisioning. Through some late night effort, we were able to find and resolve this certificate, even though it wasn't part of the standard suite of products that I assist the customer with. The resolution was ultimately quick, and the team was happy after discussing everything in a post-mortem call, and this certificate was added to the list!
