# Privacy Policy for RTLify

**Last Updated:** July 24, 2025

Thank you for using RTLify ("the Extension"). This Privacy Policy is intended to help you understand what data the Extension collects, why it collects it, and what it does with that data.

We are committed to protecting your privacy. The core philosophy of RTLify is to be a client-side tool that respects user privacy.

## 1. Data We Do Not Collect

RTLify is designed to function without collecting any personally identifiable information. We **do not** collect, store, or transmit:

- Your browsing history
- The content of any web page you visit
- Personal information like your name, email address, or location
- Your IP address or any other network information

## 2. Data We Collect and Store

RTLify only stores data that is essential for its functionality. This data is stored locally on your computer using the `chrome.storage` API and is not transmitted to any external servers.

The data we store includes:

- **User Settings**: Your configured preferences, such as the operation mode (Automatic/Manual), default RTL state, and feature toggles (e.g., image flipping, framework support).
- **Whitelist and Blacklist**: The lists of website domains that you explicitly add to the whitelist or blacklist. This data is used solely to determine whether to apply RTL transformations on those specific sites.

If you are signed into your Google Chrome account, these settings may be automatically synced across your devices via Google's service. This process is governed by Google's privacy policy, and we do not have access to this data.

## 3. Permissions and Their Usage

RTLify requires certain permissions to function correctly. Here is an explanation of why we need them:

- **`activeTab` / `scripting`**: These permissions are required to access and modify the structure (DOM) and styling (CSS) of the web page you are currently viewing. This is the core functionality of the Extension, allowing it to apply the RTL layout. The Extension **does not** read, store, or transmit the actual content of the web pages.
- **`storage`**: This permission is used to save your settings locally on your device, as described in Section 2.
- **`host_permissions` (`http://*/*`, `https://*/*`)**: This permission allows the Extension to run on any website you visit. It is necessary for RTLify to be available on any page you wish to transform. The Extension does not actively track your browsing habits; it only activates when you interact with it or when a site matches your automatic mode rules.

## 4. User-Initiated Data Sharing

The only instance where any data is sent externally is when you, the user, explicitly choose to do so.

- **Report an Issue**: If you click the "Report Issue" button, RTLify will open a new issue template on our GitHub support page. This template will be pre-filled with the URL of the website you are on and your browser's User-Agent string to help us diagnose the problem. This action is entirely voluntary. You have full control to edit or remove this information from the GitHub issue before submitting it.

## 5. Third-Party Services

RTLify is a self-contained extension and **does not** use any third-party servers, analytics services, or advertising frameworks. All functionality is executed locally within your browser.

## 6. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any significant changes by updating the "Last Updated" date at the top of this policy. We encourage you to review this policy periodically.

## 7. Contact Us

If you have any questions or concerns about this Privacy Policy, please open an issue on our support repository:
[https://github.com/RTLify/RTLify-support](https://github.com/RTLify/RTLify-support)
