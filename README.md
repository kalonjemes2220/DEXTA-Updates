# DEXTA Browser

### Browse with confidence. Stay in control.

**A compact Android browser with built-in protection and practical
tools.**

[Download the latest
APK](https://github.com/kalonjames2220/DEXTA-Updates/releases/latest) ·
[View all
releases](https://github.com/kalonjames2220/DEXTA-Updates/releases)

`ANDROID` `LIGHTWEIGHT` `AD & TRACKER BLOCKING` `PRIVACY-FOCUSED`

------------------------------------------------------------------------

## A browser that keeps things simple

Your browser should help you get to the things you want --- not get in
your way.

**DEXTA Browser** combines everyday browsing, built-in content blocking,
useful productivity tools, and privacy controls in a lightweight Android
app. Choose how much protection you want, manage site permissions, and
keep your browsing experience under your control.

No DEXTA account is required. The app is free to use and has no in-app
advertising.

## What makes DEXTA different?

  ----------------------------------- -----------------------------------
  **Small download**                  The APK attached to the current
                                      v2.1.5 release is approximately
                                      **779 KB**. Installed storage use
                                      will be larger.

  **Protection built in**             Ad, tracker, and pop-up controls
                                      are available directly in the
                                      browser.

  **Your settings, your choice**      Enable or disable protection
                                      globally or adjust it for an
                                      individual website.

  **Useful tools included**           Reader mode, downloads, password
                                      vault, translation, QR generation,
                                      and more.

  **No DEXTA account**                Start browsing without signing up
                                      for a DEXTA account.

  **Free and ad-free**                No paid subscription is required
                                      and there are no ads inside the
                                      DEXTA app interface.
  ----------------------------------- -----------------------------------

## Explore the features

### 1. Browse with built-in protection

DEXTA includes a filter-based blocker designed to reduce unwanted
advertising, trackers, and intrusive page behaviour.

-   Built-in ad and tracker filtering.
-   Support for filter sources such as EasyList and EasyPrivacy.
-   Optional blocking of pop-ups and redirects.
-   Smart blocking for suspicious ad-server domains.
-   Per-website protection controls.
-   Custom blocked-domain list.
-   Optional Strict Mode for additional cross-domain script and frame
    blocking.
-   A protection summary with blocked-request statistics.

**You stay in control:** if a website needs a blocked feature, you can
adjust protection for that site instead of changing your settings
everywhere.

### 2. Privacy controls you can understand

Privacy is not a magic switch. DEXTA provides practical controls and
explains when optional services are involved.

-   Private tabs that do not add pages to browsing history.
-   Third-party cookie blocking option.
-   Safe Browsing protection option.
-   JavaScript control.
-   Optional app lock using your Android device's screen-lock or
    biometric authentication.
-   Password vault encrypted with AES-256-GCM; its encryption key is
    held by Android Keystore.
-   Passwords are excluded from the browser's regular backup.
-   Clear browsing data when you choose.

**A clear distinction:** private tabs prevent history from being saved
by DEXTA, but they do not make you anonymous to websites, network
providers, or other services.

### 3. A practical password vault

Keep saved website credentials in DEXTA's encrypted password vault.

-   AES-256-GCM encryption.
-   Encryption key protected by Android Keystore.
-   Optional biometric protection for opening the vault.
-   Password generator.
-   Autofill support through Android's Autofill service, when enabled in
    Android settings.
-   Passwords are not included in DEXTA backup files.

Use a secure screen lock on your phone to help protect access to your
device.

### 4. Tools for everyday browsing

DEXTA brings useful features together in one place:

-   Multiple tabs, private tabs, tab groups, pinned tabs, and
    reopen-closed-tab support.
-   Bookmarks and browsing history.
-   Search suggestions with selectable search engines.
-   Reader Mode for a cleaner reading view.
-   Webpage and selected-text translation.
-   Desktop-site mode.
-   Download manager with progress, pause/resume where the server
    supports it, retry, and file sharing.
-   Generate a QR code for the current page.
-   Install and manage supported user scripts.
-   Save a page as PDF and capture the visible screen.
-   Optional encrypted export/import for supported browsing data.

**About extensions:** DEXTA uses a user-script system. It does not run
Chrome Web Store extensions or provide the full Chrome extension API.

### 5. A home screen with a little more life

Make the start page useful at a glance.

-   Weather information from Open-Meteo.
-   Celsius and Fahrenheit temperature units.
-   Automatic or manually selected weather location.
-   Day/night sky effects and optional weather animations.
-   Optional news feed from public RSS sources.
-   Customisable shortcuts.

Weather and news are optional features. You can turn them off in
settings.

### 6. Developer tools when you need them

DEXTA includes an integrated set of WebView developer tools for
inspecting and troubleshooting pages.

Available panels include Elements, Console, Network, Sources,
Application, and responsive inspection. Some advanced Chrome DevTools
capabilities are not available in Android WebView.

------------------------------------------------------------------------

## When a website does not work

Some websites depend on pop-up windows, redirects, third-party scripts,
or resources that a blocker may restrict.

If a page, login window, payment flow, or video player does not work as
expected:

1.  Open the website in DEXTA.
2.  Open the browser's Ad Blocker settings.
3.  Temporarily turn off **Block pop-ups and redirects** for the site,
    if a pop-up or login window is required.
4.  If the problem continues, temporarily disable the ad blocker for
    that website.
5.  Reload the page and try again.
6.  Turn protection back on when you are finished if the site works with
    it enabled.

If Strict Mode is enabled, a site may also need an individual domain to
be allowed or Strict Mode to be disabled for that site.

**Security reminder:** only allow pop-ups or disable blocking on
websites you trust. These controls can permit unwanted content.

## Privacy, data, and transparency

We want users to understand what the browser does --- and what happens
when optional online features are used.

### What the app is designed to do

-   DEXTA does not require a DEXTA account.
-   The inspected project dependencies do not include a third-party
    advertising or analytics SDK.
-   Saved passwords are encrypted locally using Android Keystore-backed
    AES-256-GCM.
-   Regular browser backups exclude passwords and cookies.
-   The optional encrypted sync file is passphrase-protected and
    file-based; DEXTA does not provide a cloud sync server.

### Online services used by optional features

Some features need to contact other services to work. For example:

  -----------------------------------------------------------------------
  Feature                             Service / data flow
  ----------------------------------- -----------------------------------
  Weather                             Open-Meteo receives approximate,
                                      rounded location coordinates when
                                      weather is used. Weather is not
                                      fetched from private tabs.

  Page translation                    Page text selected for translation
                                      is sent to Google's translation
                                      endpoint.

  Safe Browsing                       Uses Google's Safe Browsing service
                                      when enabled.

  Search suggestions                  Text entered in the address bar may
                                      be sent to the selected search
                                      provider when suggestions are
                                      enabled.

  News                                The selected public RSS feed is
                                      requested to retrieve headlines.

  Updates                             DEXTA checks the configured public
                                      update source for release
                                      information.
  -----------------------------------------------------------------------

Websites you visit can also receive the information required to load
their pages. DEXTA cannot prevent a website, search provider, or network
operator from collecting data under its own policies.

### Diagnostic logging

The inspected project contains a diagnostic logging component used for
troubleshooting. It can write limited network and URL-path diagnostic
details to Android system logs (Logcat). The code is configured to omit
URL query strings, fragments, cookies, and request/response headers.
This is device-side diagnostic logging, not evidence of an analytics
service --- but it means we should not claim that the app creates
absolutely no logs.

For a complete technical review, inspect the source code and the current
privacy documentation before relying on any privacy claim.

------------------------------------------------------------------------

## Download DEXTA

**Latest version: 2.1.5 · Build 5**

[**Download DEXTA Browser
APK**](https://github.com/kalonjames2220/DEXTA-Updates/releases/latest)

You can also visit the [Releases
page](https://github.com/kalonjames2220/DEXTA-Updates/releases) to view
previous versions and their release notes.

### Install on Android

1.  Download the APK from the official GitHub Releases page.
2.  Open the downloaded APK.
3.  If Android asks, allow your browser or file manager to install apps
    from that source.
4.  Review the Android installation prompt and install DEXTA.

Only download DEXTA from the official repository. Android may show a
security warning when installing apps outside Google Play.

## Compatibility

-   **Platform:** Android
-   **Minimum Android version:** Android 8.0 (API 26)
-   **Browser engine:** Android System WebView (Chromium)
-   **Current release APK:** approximately 779 KB
-   **Price:** Free

The installed app size is not the same as the APK download size and
varies by device.

## Known limitations

A transparent project should also explain its limits:

-   DEXTA uses Android System WebView, not a separately packaged full
    Chromium browser.
-   Chrome Web Store extensions are not supported; DEXTA provides user
    scripts instead.
-   Strict Mode can affect websites that depend on cross-domain scripts
    or frames.
-   Some websites may still display ads, and no blocker can guarantee
    removal of every ad.
-   Download resume depends on the server supporting byte-range
    requests.
-   The optional DNS-over-HTTPS feature applies to DEXTA's own network
    requests; Android WebView page traffic uses the device's network
    resolver.
-   Private tabs in Android WebView may share cookies with regular tabs.
    Private browsing should not be treated as complete isolation.
-   Translation depends on Google's public translation endpoint and may
    be rate-limited or changed by that service.

## Feedback and contributions

Found a bug, have a suggestion, or want to report a website
compatibility issue?

Please open an issue in the repository and include: - Your Android
version. - Your DEXTA version. - The website or feature affected. -
Steps to reproduce the issue. - Screenshots or logs only when they do
not expose passwords, private URLs, or other personal information.

Please do not post passwords, session cookies, private browsing details,
or other sensitive information in public issues.

------------------------------------------------------------------------

### DEXTA Browser

**A smaller browser. A more considered browsing experience.**

Free to use · No in-app ads · Built-in controls
