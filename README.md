# RTCaaS
By Christopher van der Made and Håkan Nohre.

Implementing Rapid Threat Containment as a Service (RTCaaS) using SecureX.

Video description with demo https://www.youtube.com/watch?v=82hwVG9xA_4&list=PLOM0SD277fTF_qtBi8bCjQMyh04fdLIBH&index=4

Workflows polls external security events from Umbrella, AMP or any other 3rd party with REST API.

Extracts user identity and MAC address of Target IP from ISE. (using middleware).

Tracks Penalties for Hostnames, IP, MAC and usernames.

If penalty exceeded performs AMP Host Isolation and ISE ANC and creates casebook.

Main documenation of problem scope and design in RTCaaS-documentation.pdf.

There is also a middleware, RTC used to broker via SXO and ISE and AD. (This middleware can also be used for other projects, not related for RTCaaS.
Install with docker-compose up on a machine with docker-cmpose running (and after downloading the docker-compose.yml).

How to install and configure the middleware should not take more than 10 minutes and is documented in RTC Middleware Installation and Configuration.
