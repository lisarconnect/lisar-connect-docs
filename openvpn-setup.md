# OpenVPN Setup

This guide explains the basic OpenVPN setup flow for Lisar Connect profiles.

Lisar Connect provides a downloadable `.ovpn` file for supported connection profiles. The file can be imported into OpenVPN-compatible clients.

## Before you start

You need:

- A Lisar Connect account
- An active connection profile
- Access to the profile details page
- OpenVPN Connect or another compatible OpenVPN client installed on your device

## Step 1 — Open your profile details

1. Sign in to Lisar Connect.
2. Open the dashboard.
3. Select your connection profile.
4. Open the profile details page.

The profile details page shows setup information for supported connection methods.

## Step 2 — Download the `.ovpn` file

In the OpenVPN section:

1. Click **Download .ovpn file**.
2. Save the file on your device.
3. Keep the downloaded file private.

The `.ovpn` file is connection material for your profile. Do not share it publicly.

## Step 3 — Import into OpenVPN Connect

In OpenVPN Connect:

1. Open the app.
2. Choose **Upload File**.
3. Select the downloaded `.ovpn` file.
4. Import the profile.
5. Connect using the imported profile.

Use **Upload File**.

Do not use Access Server URL or CloudConnexa import unless your setup explicitly requires it. Lisar Connect provides a downloadable `.ovpn` profile file.

## Step 4 — Check active sessions

After connecting:

1. Return to the Lisar dashboard.
2. Open **Active VPN**.
3. Click **Refresh** if needed.
4. Review the active session details.

Depending on the profile and connection state, the dashboard may show:

- Profile name
- Protocol
- Internal VPN IP
- Entry router
- Exit router
- Usage metrics
- Connection status

## Troubleshooting

### The `.ovpn` file opens as text

This usually means your device does not have an OpenVPN client associated with `.ovpn` files.

Install OpenVPN Connect or another compatible OpenVPN client, then import the file using **Upload File** inside the client.

### OpenVPN Connect asks for credentials

Use the username and password shown in the Lisar profile details page.

Do not share these values.

### The session does not appear immediately

Try:

1. Waiting a few seconds.
2. Clicking **Refresh** on the Active VPN page.
3. Reconnecting the VPN client.

### The import fails

Check that:

- The downloaded file is complete.
- You are importing through **Upload File**.
- You are not pasting the profile URL into Access Server or CloudConnexa.
- Your OpenVPN client is up to date.

## Security note

Downloaded profiles, config URLs, usernames, passwords, private keys, and screenshots containing secrets should be kept private.
