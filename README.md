# RTCaaS
By Christopher van der Made and Håkan Nohre.

Implementing Rapid Threat Containment as a Service (RTCaaS) using SecureX.

All files in this repo are obsolete.

Workflows polls external security events from Umbrella, AMP or any other 3rd party with REST API.

Extracts user identity and MAC address of Target IP from ISE. (using middleware).

Tracks Penalties for Hostnames, IP, MAC and usernames.

If penalty exceeded performs AMP Host Isolation and ISE ANC and creates casebook.

Main documenation of problem scope and design in RTCaaS-documentation.pdf.
