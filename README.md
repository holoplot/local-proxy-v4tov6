Local proxy from IPv4 to IPv6
---

Proxy select connections to IPv6 hosts by listening on localhost IPv4. Useful
for IPv4 only clusters where the host has IPv6.

## Usage

See the [charts/local-proxy-v4tov6/values.yaml](charts/local-proxy-v4tov6/values.yaml) for configuration options.

From non `hostNetwork` pods use the service domain name. From the hosts use `127.1`.
