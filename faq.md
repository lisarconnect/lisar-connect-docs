# FAQ

## What is Lisar Connect?

Lisar Connect helps users create VPN connection profiles for standard clients such as OpenVPN and compatible L2TP/IPsec setup.

The goal is to provide managed profile creation, routing options, active sessions, and connection history without forcing a proprietary Lisar app.

## Is Lisar Connect an OpenVPN replacement?

No.

Lisar Connect is not trying to replace OpenVPN or native VPN clients.

Lisar Connect provides the service layer around connection profiles, setup values, routing options, session visibility, and dashboard management.

## Do I need to install a Lisar app?

No mandatory proprietary Lisar app is required for the standard-client setup flow.

Users can connect with supported standard clients such as OpenVPN-compatible clients or compatible L2TP/IPsec setup where available.

## How do I use OpenVPN with Lisar?

Open your profile details page, download the `.ovpn` file, and import it into OpenVPN Connect using **Upload File**.

Do not use Access Server URL or CloudConnexa import for a standard Lisar `.ovpn` file.

## How do I use L2TP/IPsec with Lisar?

Open the profile details page and use the provided server/app record, username, password, and IPsec PSK in your operating system’s L2TP/IPsec VPN settings.

## What is a connection profile?

A connection profile is a managed VPN profile inside Lisar Connect.

Depending on the plan and profile configuration, it may include:

- Profile name
- Plan limits
- Quota
- Entry router
- Exit router
- OpenVPN setup material
- L2TP/IPsec setup values
- Active session visibility
- Connection history

## What is an entry router?

The entry router is the router or location your client connects to first.

## What is an exit router?

The exit router is the router or location where traffic exits, when custom exit routing is available and enabled.

Some profiles may use the same entry and exit location.

## What is GeoDNS?

GeoDNS refers to routing behavior that can select an entry route based on location or routing rules, where supported by the profile and plan.

## What is DNS AdBlock?

DNS AdBlock refers to DNS-level filtering behavior where supported by the profile and plan.

Availability depends on product configuration and plan rules.

## Why does the dashboard show active sessions?

The Active VPN page helps users review live sessions, protocol, usage metrics, route details, and connection state where available.

## Why does connection history matter?

Connection history helps users review previous VPN activity by profile, status, protocol, route details, and usage data where available.

## Can I share my `.ovpn` file?

No.

Downloaded profiles and connection credentials should be kept private.

## Can I share my IPsec PSK?

No.

The IPsec PSK is a secret value and should not be shared publicly.

## What should I do if setup fails?

Check:

- Profile status
- Downloaded `.ovpn` file
- Username and password
- IPsec PSK
- VPN client version
- Device VPN support
- Network restrictions

If the issue continues, contact support with the profile name, device type, operating system, connection method, and approximate time of the issue.
