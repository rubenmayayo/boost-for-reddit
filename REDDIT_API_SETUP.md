# How to get a Reddit API client ID for Boost

Since Reddit's API changes, Boost no longer ships with its own API key. On first launch it asks for three values: **client ID**, **redirect URL** and **user agent**. You only have to do this once, and the values are stored only on your device.

Reddit no longer lets you create your own API app, but you can use the client ID of RedReader, an open-source Reddit client.

## 1. Get the client ID

1. Install [RedReader from Google Play](https://play.google.com/store/apps/details?id=org.quantumbadger.redreader).
2. Open it, log in with your Reddit account and tap **Allow** when Reddit asks for permission.
3. Reddit will send you an email saying you authorized a new app. Look for this line:

    `App ID: xxxxxxxxxxxxxx`

4. Copy it. In Boost you can paste the whole line; Boost keeps only the ID.

You can uninstall RedReader afterwards if you want.

## 2. Enter the values in Boost

- **Client ID:** the App ID from the email
- **Redirect URL:** `redreader://rr_oauth_redir`
- **User agent:** `org.quantumbadger.redreader/1.25.1`

Tap **Save**, then log in again with your accounts.

You can change these values later in **Settings > Advanced > Developer**.

## Troubleshooting

- **"invalid redirect_uri parameter"**: check the redirect URL is exactly `redreader://rr_oauth_redir`.
- **"invalid client id"**: check that you copied only the ID, with no spaces.
- **No email from Reddit?** Check your spam folder, and make sure your Reddit account has a verified email address.
