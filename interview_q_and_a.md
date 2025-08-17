# Task 7 — Interview Q&A

## Q1: How can browser extensions pose security risks?
Browser extensions can inject malicious scripts, monitor user activity, redirect traffic, steal sensitive data (like cookies or form inputs), or download additional malware. Since they run inside the browser, they often have access to powerful APIs.

---

## Q2: What permissions should raise suspicion?
- “Read and change all your data on the websites you visit”
- Access to browsing history
- Clipboard or proxy settings
- Manage downloads
- Any permission that does not match the claimed functionality of the extension

---

## Q3: How to safely install browser extensions?
- Install only from official stores (Chrome Web Store).
- Verify developer name, website, and contact info.
- Check number of users, ratings, and reviews.
- Review requested permissions before installing.
- Prefer open-source or well-known extensions.

---

## Q4: What is extension sandboxing?
Extension sandboxing means extensions run in an isolated environment with restricted access to system resources. However, if permissions are broad, the sandbox still allows them to interact with web content and potentially abuse data.

---

## Q5: Can extensions steal passwords?
Yes. If granted access to page content, an extension can read input fields (including password fields) or intercept login requests.

---

## Q6: How to update extensions securely?
Extensions update automatically via the Chrome/Brave store. Secure updating means:
- Only allow auto-updates from the official store.
- Avoid manual CRX installations from untrusted sources.
- Check changelogs and permissions after updates.

---

## Q7: What is the difference between extensions and plugins?
- **Extensions**: JavaScript/HTML-based tools that extend browser functionality (UI changes, ad-blocking, productivity tools).  
- **Plugins** (legacy): External binaries that enabled web content (Flash, Java). Now mostly deprecated due to security issues.

---

## Q8: How to report malicious extensions?
- Use the “Report abuse” option in the Chrome Web Store.
- Provide the extension ID, screenshots, and a description of suspicious behavior.
- Notify Brave/Chrome support if it affects system-wide behavior.
