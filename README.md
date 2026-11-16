# slihoczkirichard.github.io

Canary target for a BSc thesis measurement at the Budapest University of
Technology and Economics (BME VIK).

This site serves a single static file, `canary.txt`, containing a unique
token. A measurement script requests it through a Secure Web Gateway (SWG)
to measure how long it takes until a web category change is enforced:
the token means "reachable", the gateway's block page means "blocked".

The site intentionally has no other content and collects no data.
