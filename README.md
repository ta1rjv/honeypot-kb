# honeypot-kb - SSH honeypot intelligence site

Read it at **https://ta1rjv.github.io/honeypot-kb/** (English by default, Turkish selectable with the EN | TR switch).

A public knowledge site about observed internet attack traffic against an SSH honeypot (Cowrie): statistics of
sessions, credentials tried, commands, downloaded payloads and MITRE ATT&CK techniques, plus the project's
architecture, threat model, decisions, reports and research as a document library.

This repository only hosts the generated static site. It is built automatically from a private repository
(`ta1rjv/honeypot-intelligence`) and published sanitized: the operator's own infrastructure details (addresses,
ports, access paths, secrets) are removed and a fail-closed leak check runs before every publication. Attacker
indicators (source addresses, credentials tried, payload hashes) are shown for defensive research; URLs and
domains are defanged (`hxxp://`, `[.]`).

The content is provided as is, without warranty of any kind. Do not contact, scan or attack any address shown here.
