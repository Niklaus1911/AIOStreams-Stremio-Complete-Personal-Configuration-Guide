## AIOStreams \& Stremio – Complete Personal Configuration Guide

Today I want to share my full **AIOStreams/Stremio** configuration. It took a while to adapt everything to my needs, but now that it’s finished (for now), the satisfaction is huge. I’m sure many of you can relate — I hope this guide proves useful.

***

### Step 1. Web Streams (WebStreamr – Inside AIOStreams)

This addon retrieves HTTP results.
It’s a great alternative whenever your Debrid service experiences downtime or doesn’t return results.

**Addon URL:** [https://aiostreamsfortheweak.nhyira.dev](https://aiostreamsfortheweak.nhyira.dev/)

#### Setup

1. Open your preferred **AIOStreams** instance.
2. Optionally, edit the addon’s name and description for clarity in Stremio:
    - Click the pencil icon next to *AIOstreams* on the home page.
    - **Addon Name:** `Web Streams`
    - **Addon Description:** `Provides HTTP URLs from streaming websites`
This will help distinguish it from your main instance.

#### Add the addon

1. Click the **☰** menu (top-left corner).
2. Select **Addons**.
3. Go to the **Marketplace** and search for **WebStreamr**.

#### Configuration

- **Name:** Select your preferred language (e.g. *Spanish Latino*).
- **Timeout:** `10,000`
- **Providers:** Your preferred language (e.g. *Latin American Spanish*).

***

### Step 2. AIOStreams Instance

**Recommended instance:** [https://aiostreamsfortheweebs.midnightignite.me](https://aiostreamsfortheweebs.midnightignite.me)
Maintained by [u/midnightignite](https://www.reddit.com/user/midnightignite/), who does an excellent job keeping it updated.

#### Optional Customization

- **Addon Name:** `Streams`
- **Addon Description:**
`"Debrid Services And Stream Resources: Configuration for use inside and outside the home network, supports streaming from multiple IP addresses."`

***

### Step 3. Service Configuration

1. Go to **☰ → Services.**
2. Enable your preferred **Debrid service**.
(In this case, you can use **TorBox** or **Real-Debrid**.)
    - **TorBox:** [Subscription link](https://torbox.app/subscription?referral=298fe09b-d9f5-432b-9c79-ad94c2d0424a)
    - **Real-Debrid:** [https://real-debrid.com/premium](https://real-debrid.com/premium)

After comparing both services over a year, **TorBox** stands out for reliability and growth. It offers cached links for new releases and allows simultaneous account use from multiple devices and locations — ideal for families.
3. Once your service is active, click the **gear icon**, add your **API Key**, and hit **Save**.

***

### Step 4. Addons

1. Go to **☰ → Addons.**
2. In the **Marketplace**, install the following addons:
    - **Torrentio – Default**
    - **TorBox (Torbox Search) – Default**
    - **Bitmagnet – Default**

Set **Timeout: 5,000** for all.
Disable the **catalogs** on each addon.

***

### Step 5. Filters

Go to **☰ → Filters.**

- **Cache:**
    - *Uncached – Exclude Uncached:* Enabled
- **Resolution:**
    - *Excluded Resolutions:* 720p, 576p, 480p, 360p, 240p, 144p, Unknown
- **Quality:**
    - *Excluded Qualities:* CAM, TS, TC, SCR
- **Language:**
    - *Excluded Languages:* Chinese, Russian, French
    - *Preferred Languages:* Latin, Spanish, Unknown, Multi



**Deduplicator:** Enabled.

***

### Step 6. Sorting

Go to **☰ → Sorting.**

- **Sort Criteria:** Resolution, Language, Size.

***

### Step 7. Formatter (Optional)


***

### Step 8. Miscellaneous

Go to **☰ → Miscellaneous.**

- **Pre-cache Next Episode:** Enabled
- **Always Pre-cache:** Enabled
- **Auto Play:** Enabled
- **Auto Play Method:** Matching File
- **Hide Errors:** Enabled

***

### Step 9. Save \& Install

Finally:

1. Go to **☰ → Save \& Install.**
2. Create a password and install **AIOStreams.**
3. Export a backup copy of your configuration for future use.

***

## Optional Tools for a Clean Setup

> **Note:** The Stremio developers do **not** recommend modifying Cinemeta. Proceed at your own risk.

### Cinebye (Hide/Remove Cinemeta)

[https://cinebye.dinsden.top](https://cinebye.dinsden.top/)

**Authenticate:** Sign in with your Stremio account.

- **Remove Cinemeta Search:** Enabled
- **Remove Cinemeta Catalogs:** Enabled
- **Remove Cinemeta Metadata:** Enabled
Then click **Sync to Stremio.**

***

### StremThru Sidekick (Addon Manager)

[https://stremthrufortheweebs.midnightignite.me/stremio/sidekick/](https://stremthrufortheweebs.midnightignite.me/stremio/sidekick/)

**How to Configure:**

1. Log in with your Stremio account.
2. Go to **Manage**.
3. Uninstall almost all addons, keeping only the following:
    - Cinemeta
    - Local Files (without catalog support)
    - Opensubtitles V3
    - AlOMetadata – Personal Configuration
    - AIOStreams – Personal Configuration
    - Web Streams (WebStreamr – Inside AIOStreams)
4. Go to **Move** and arrange them in the same order as above.

***

## Final Notes

That concludes the setup of all the addons currently in use.
This configuration has greatly simplified my Stremio experience.
Feel free to ask questions, share feedback, or leave suggestions.

**Thank you very much ♡**

***



  
