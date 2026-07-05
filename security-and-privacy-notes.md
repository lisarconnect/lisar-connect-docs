# Security and Privacy Notes

This document provides general security and privacy notes for using Lisar Connect.

It is not a legal privacy policy and does not replace the official terms, privacy policy, or product documentation published on the Lisar website.

## Keep connection materials private

The following values should be treated as private:

- `.ovpn` files
- Config URLs
- Usernames
- Passwords
- IPsec PSKs
- Private keys
- Screenshots containing secrets
- Profile-specific connection material

Do not publish these values in GitHub issues, public forums, screenshots, social media posts, or support threads.

## Use trusted devices

Only configure VPN profiles on devices you control and trust.

Avoid importing VPN profiles on shared, unmanaged, or compromised devices.

## Use standard clients carefully

Lisar Connect supports a standard-client setup approach. This can improve portability and reduce vendor lock-in, but users are still responsible for using trusted VPN clients and keeping them updated.

Recommended practices:

- Use official OpenVPN Connect or trusted OpenVPN-compatible clients.
- Keep VPN clients updated.
- Avoid importing unknown VPN profiles.
- Remove old profiles you no longer use.
- Do not share exported configs.

## Understand what a VPN does

A VPN can help route traffic through a VPN tunnel and change the visible network exit point, depending on the setup.

A VPN does not automatically provide complete anonymity, complete privacy, or protection against every tracking method.

Avoid assuming that any VPN setup protects against all threats.

## Avoid overclaiming

Lisar Connect should not be described with unsupported claims such as:

- anonymous VPN
- no logs
- fastest VPN
- bypass everything
- guaranteed access
- military-grade security

Preferred wording:

- standard VPN clients
- secure connectivity
- connection profiles
- OpenVPN-compatible setup
- compatible L2TP/IPsec setup
- no mandatory proprietary app
- reduced vendor lock-in
- transparent setup flow

## Active sessions

The Active VPN page may show active session information such as:

- Profile name
- Protocol
- Internal VPN IP
- Entry router
- Exit router
- Usage metrics
- Connection state

This information is intended to help users understand and manage their current VPN activity.

## Connection history

Connection history may show previous session details where available.

This helps users review connection state, usage, routing, and troubleshooting context.

## Public support safety

When asking for support publicly, do not include:

- Full credentials
- PSKs
- Private keys
- Full profile contents
- Full `.ovpn` files
- Tokens
- Sensitive account details

Safe information to share:

- Device type
- Operating system
- VPN client name and version
- Connection method: OpenVPN or L2TP/IPsec
- Approximate time of issue
- General error message
- Profile name only if it does not reveal sensitive information

## Reporting issues

If you find a security-sensitive issue, do not post details publicly.

Use the official Lisar support channel or contact method shown on the Lisar website or dashboard.
