# Topic Page 2 — Evolution of HTTP

## Overview
HTTP has evolved to support a much larger and more demanding web. The earliest version only retrieved hypertext documents. Later versions added headers, status codes, persistent connections, security expectations, multiplexing, and new transport technology.

## HTTP/0.9
HTTP/0.9 was extremely simple. A client sent a one-line GET request and the server returned the requested hypertext document. There were no response headers, status codes, or general support for many different content types.

## HTTP/1.0
HTTP/1.0 added important features such as protocol version information, headers, status codes, and support for multiple media types. These additions made HTTP practical for a rapidly growing web.

## HTTP/1.1
HTTP/1.1 improved efficiency and flexibility. Important additions and improvements included persistent connections, the Host header, stronger caching behavior, range requests, and chunked transfer encoding. HTTP/1.1 became one of the longest-lasting versions of the protocol.

## HTTPS and TLS
As the web became more important for personal and financial activity, security became essential. HTTPS combines HTTP with TLS so that communication can be encrypted and the browser can authenticate the site it is communicating with.

## HTTP/2
HTTP/2 preserved the meaning of HTTP requests and responses but changed how messages are transferred. It introduced binary framing, multiplexing, and header compression. These features help modern webpages load many resources efficiently over fewer connections.

## HTTP/3
HTTP/3 uses QUIC instead of TCP as its underlying transport. QUIC supports multiple streams, encryption, and connection migration. HTTP/3 was designed to reduce some transport-level delays that can affect HTTP/2 when packets are lost.

## Comparison table
| Version | Main contribution | Important limitation or challenge |
| --- | --- | --- |
| HTTP/0.9 | Basic hypertext retrieval | No headers or status codes |
| HTTP/1.0 | Headers, status codes, media types | Often required many separate connections |
| HTTP/1.1 | Persistent connections, caching, Host header | Performance limits under many parallel requests |
| HTTP/2 | Binary framing, multiplexing, header compression | Still relies on TCP ordering |
| HTTP/3 | QUIC transport, multiplexed streams, connection migration | Deployment depends on QUIC/UDP support |

## Timeline points
- 1989–1991: Early World Wide Web work at CERN includes HTTP.
- 1991: HTTP/0.9 era.
- 1996: HTTP/1.0 documented.
- 1997–1999: HTTP/1.1 develops and matures.
- 2015: HTTP/2 standardized.
- 2022: Modern HTTP specifications include HTTP/3.

## Suggested visual
Create or find a simple timeline graphic showing the progression from HTTP/0.9 to HTTP/3.
