# Privacy Policy for YuLaF – YouTube Language Filter

**Effective Date:** December 25, 2025

---

## 1. Overview

YuLaF – YouTube Language Filter is a Chrome extension designed to filter YouTube videos and channels based on the user's selected languages.

**The extension operates entirely locally on the user's device.**

**No user data is collected, stored externally, or transmitted to any server.**

---

## 2. Data Collection

YuLaF does **NOT** collect, process, or transmit any personal or sensitive user data.

### Specifically, the extension does NOT collect:

- ❌ Personally identifiable information (name, email address, IP address, location)
- ❌ Browsing history or search queries
- ❌ YouTube account or authentication data
- ❌ Usage analytics or tracking data
- ❌ Viewing habits or watch history
- ❌ Video preferences or recommendations
- ❌ Device information or fingerprinting data

---

## 3. Local Storage

YuLaF uses the Chrome Storage API (`chrome.storage.sync`) to store extension settings **locally on the user's device**.

### What is stored:

- Selected language preferences (e.g., English, Spanish, Turkish)
- Extension enabled/disabled status
- Filter configuration options (Strict Mode on/off)
- Sort preference (popularity or alphabetical)

### Important notes about stored data:

✅ **Remains only on your device** (or synced via Chrome sync if you have Chrome sync enabled)  
✅ **Never shared with external parties**  
✅ **Automatically removed** when the extension is uninstalled  
✅ **No cloud servers** - we don't have servers to store your data  
✅ **You control it** - change or delete settings anytime through the extension  

---

## 4. Permissions Usage

YuLaF requests the **minimum permissions** required to function.

### Detailed Permission Breakdown:

| Permission | Purpose | What It Does | What It Does NOT Do |
|------------|---------|--------------|---------------------|
| `activeTab` | Read video titles on YouTube | Temporarily accesses video titles and channel names on the active tab to detect language | Does NOT access other tabs, browsing history, or personal data |
| `storage` | Save user preferences | Stores your language preferences locally so they persist between sessions | Does NOT send data to external servers |
| `tabs` | Update extension badge | Updates the badge icon to show filter status (ON/OFF) | Does NOT access tab content or URLs |
| `*.youtube.com` | Restrict to YouTube only | Ensures the extension only operates on YouTube domains | Does NOT access other websites |
| `img.shields.io` | Display extension stats | Retrieves publicly available Chrome Web Store statistics (user count, rating) for display on welcome page only | Does NOT track users or collect personal data |

**No permission is used to collect, store, or transmit personal user data.**

---

## 5. Third-Party Services

YuLaF uses **ONE** third-party service with strict limitations:

### Shields.io API (`https://img.shields.io/chrome-web-store/*`)

**Purpose:**  
Displays real-time Chrome Web Store statistics (user count and rating) on the welcome page only.

**What data is shared:**  
**NONE.** The API only retrieves publicly available extension statistics from Chrome Web Store.

**User data:**  
No user data is collected, processed, or transmitted to this service.

**When it runs:**  
Only when you open the welcome page. Does not run during normal browsing.

**If it fails:**  
The extension functions normally without displaying these statistics.

**Privacy:**  
Shields.io does not track users or collect personal information.  
[Learn more about Shields.io privacy](https://shields.io/)

---

### What YuLaF does NOT use:

❌ Google Analytics or any analytics service  
❌ Advertising services or ad networks  
❌ Remote code execution  
❌ User tracking or profiling services  
❌ Social media integrations  
❌ Third-party cookies  
❌ External APIs for language detection (uses Chrome's built-in API)  

---

## 6. Chrome Web Store Data

The extension retrieves **publicly available statistics** about itself from Chrome Web Store via Shields.io API:

- Total user count (number of installs)
- Average user rating

### Important clarifications:

✅ **Public data** - Already available on the Chrome Web Store listing  
✅ **Not linked to individual users** - Aggregate statistics only  
✅ **Displayed only on welcome page** - For informational purposes  
✅ **Optional** - If the API fails, the extension works normally  
✅ **No user tracking** - Does not identify or track individual users  

---

## 7. How Language Detection Works

YuLaF uses **Chrome's built-in language detection API** (`chrome.i18n.detectLanguage`):

1. Reads video title or channel name from the YouTube page
2. Sends text to Chrome's **local** language detection engine
3. Chrome returns detected language **locally on your device**
4. YuLaF compares it with your selected languages
5. Shows or hides the video based on match

**Important:**  
- All processing happens **on your device**
- Text is NOT sent to external servers
- Results are cached temporarily for performance
- Cache is cleared when you close the browser

---

## 8. Children's Privacy

YuLaF does **not** knowingly collect data from children under the age of 13.

Since **no user data is collected at all**, the extension is safe for users of all ages.

**Parents:**  
You can review this privacy policy to understand exactly what YuLaF does and does not do with data.

---

## 9. Data Security

YuLaF implements security best practices:

✅ **Local-only processing** - All language detection occurs locally using Chrome's built-in APIs  
✅ **No external servers** - We don't have servers, so there's nothing to breach  
✅ **Secure storage** - Settings stored using Chrome's official Storage API with built-in encryption  
✅ **Minimal network requests** - Limited to YouTube.com and Shields.io API only  
✅ **No code injection** - Extension does not inject malicious code  
✅ **Regular updates** - We maintain the extension to address any security issues  

---

## 10. User Rights

You have full control over your data:

| Right | How to Exercise It |
|-------|-------------------|
| **Access** | View your settings anytime through the extension popup or Advanced Settings page |
| **Modify** | Change language preferences and filter settings instantly - changes apply immediately |
| **Delete** | Uninstalling the extension removes all stored data automatically |
| **Export** | Settings are stored locally - you can view them in Chrome DevTools if needed |
| **Opt-out** | Disable the extension at any time without any data retention |

**No account deletion needed** - We don't have user accounts!

---

## 11. Policy Updates

This privacy policy may be updated if:

- Extension functionality changes
- Legal requirements change
- User feedback suggests improvements

### How we notify you of changes:

✅ Updated "Effective Date" at the top of this document  
✅ Changelog in the [GitHub repository](https://github.com/vakkaskarakurt/YuLaF-Privacy)  
✅ Chrome Web Store update notes (for major changes)  
✅ In-extension notification (for significant privacy-related changes)  

**We will never reduce your privacy protections without clear notification.**

---

## 12. International Compliance

YuLaF respects privacy laws worldwide:

- **GDPR** (European Union) - Full compliance through zero data collection
- **CCPA** (California) - No personal data sold or shared
- **KVKK** (Turkey) - Turkish data protection law compliance
- **Other regions** - We follow global privacy best practices

**Since we don't collect personal data, most privacy regulations don't apply, but we still exceed their requirements.**

---

## 13. Cookies and Tracking

**YuLaF does NOT use:**

❌ Cookies  
❌ Tracking pixels  
❌ Browser fingerprinting  
❌ Session tracking  
❌ Cross-site tracking  
❌ Behavioral tracking  

**The extension sets NO cookies and does NO tracking whatsoever.**

---

## 14. Contact & Reporting

### For privacy questions or concerns:

**GitHub Issues** (Recommended):  
[Open a Privacy Issue](https://github.com/vakkaskarakurt/YuLaF-Privacy/issues)

**Chrome Web Store Support:**  
Use the support tab on the [extension listing](https://chromewebstore.google.com/detail/yulaf-youtube-language-fi/ejfoldoabjeidjdddhomeaojicaemdpm)

### To report a privacy violation:

If you believe YuLaF is violating this privacy policy:

1. Open a detailed issue on this repository
2. Include specific information about the alleged violation
3. We will investigate and respond within **48 hours**

---

## 15. Transparency Commitment

We believe in **radical transparency**:

✅ This privacy policy is **public** on GitHub  
✅ Available for anyone to review, anytime  
✅ Versioned and tracked - you can see all changes  
✅ Community can ask questions or request clarifications  
✅ We respond to privacy concerns promptly  

---

## 16. Legal Basis for Processing (GDPR)

Under GDPR, we don't process personal data, but if we did, the legal basis would be:

- **Consent** - You install the extension voluntarily
- **Legitimate Interest** - Providing the filtering service you requested
- **Contract** - Terms of use when you install from Chrome Web Store

**However, since no personal data is processed, these legal bases are not actively used.**

---

## 17. Your Rights Under GDPR (If Applicable)

Even though we don't collect personal data, here are your rights:

| Right | Status |
|-------|--------|
| Right to Access | Settings visible in extension |
| Right to Rectification | Change settings anytime |
| Right to Erasure | Uninstall extension |
| Right to Restrict Processing | Disable extension |
| Right to Data Portability | Settings stored locally |
| Right to Object | Disable/uninstall extension |
| Right to Withdraw Consent | Uninstall extension |

---

## 18. Intellectual Property

YuLaF is proprietary software.

**This privacy policy** is provided under Creative Commons CC0 1.0 Universal license (public domain).

**The extension code** is proprietary - see Chrome Web Store listing for terms of use.

---

## 19. Disclaimer

This privacy policy applies to **YuLaF - YouTube Language Filter** Chrome extension only.

**Not responsible for:**
- YouTube's privacy practices
- Chrome browser's privacy practices
- Third-party websites linked from the extension

Please review their respective privacy policies.

---

## 20. Questions We Answer

**Q: Do you sell my data?**  
A: We don't have your data to sell!

**Q: Do you share data with advertisers?**  
A: No. We don't use advertising and have no data to share.

**Q: Can law enforcement request my data?**  
A: We don't have user data to provide. The extension works entirely locally.

**Q: What happens if you get acquired?**  
A: Privacy protections remain. The extension architecture makes data collection impossible without a complete rewrite.

**Q: How can I verify your claims?**  
A: Check Chrome DevTools Network tab - you'll see we make no tracking requests.

---

**YuLaF is committed to user privacy, transparency, and local-only processing.**

**We believe privacy is a fundamental right, not a feature.**

---

**Last Updated:** December 25, 2025

**Version:** 1.0

**Maintained by:** Vakkas Karakurt & Emrah Fidan

© 2025 YuLaF. All rights reserved.

[⬆ Back to top](#privacy-policy-for-yulaf--youtube-language-filter)
