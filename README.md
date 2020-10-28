# RTCaaS
By Christopher van der Made and Håkan Nohre.

Implementing Rapid Threat Containment as a Service (RTCaaS) using SecureX.

Workflows polls external security events from Umbrella, AMP or any other 3rd party with REST API.

Extracts user identity and MAC address of Target IP from ISE. (using middleware).

Tracks Penalties for Hostnames, IP, MAC and usernames.

If penalty exceeded performs AMP Host Isolation and ISE ANC and creates casebook.

Main documenation of problem scope and design in RTCaaS-documentation.pdf.

There is also a middleware, RTC used to broker via SXO and ISE and AD. 
Install with docker-compose up on a machine with docker-cmpose running (and after downloading the docker-compose.yml).

