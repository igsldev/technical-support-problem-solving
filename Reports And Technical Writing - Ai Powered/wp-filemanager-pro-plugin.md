### **🚨 Security Alert: WordPress Plugin Compromise - `wp-file-manager-pro` Injecting Unauthorized Code**  

 
✍️ **Author:** Team BoxxHash 
🔒 **Category:** Website Security  

---

### **🔍 What Happened?**  
We recently discovered that the **WordPress plugin `wp-file-manager-pro`** was compromised and injected **unauthorized Google AdSense code** into our website. This malicious code used an **unknown AdSense publisher ID (`ca-pub-3838462999229532`)** to display unauthorized ads, potentially stealing revenue and exposing security vulnerabilities.  

🚨 **If you have `wp-file-manager-pro` installed on your WordPress site, take immediate action!**  

---

### **🔎 How Did the Injection Occur?**  

Through investigation, we found that **`wp-file-manager-pro` contained a vulnerability** that allowed attackers to modify critical theme files, including `header.php`. The possible ways this injection happened include:  

✅ **1. Exploiting File Management Capabilities**  
   - The plugin provides **direct file management** in WordPress, allowing admins to modify core files.  
   - If exploited, attackers could use it to **modify theme files (`header.php`, `functions.php`)** and inject malicious code.  

✅ **2. Unrestricted File Upload Vulnerability**  
   - Some versions of `wp-file-manager-pro` allow **unauthenticated file uploads**, which can lead to **remote code execution**.  
   - Attackers may have uploaded **a malicious PHP script** to modify files and insert unauthorized ads.  

✅ **3. Modifying Theme Files (`header.php`)**  
   - The injected code was found inside `<head>` in `header.php`, possibly via **direct file modification or database injection**.  

✅ **4. Admin Account Compromise via Plugin**  
   - The plugin could have been used to create a **backdoor**, giving attackers unauthorized admin access.  

✅ **5. Outdated Plugin Vulnerability**  
   - If **`wp-file-manager-pro` was outdated**, it might have had **unpatched security flaws** that attackers exploited.  

---

### **🚀 How We Fixed the Issue**  

🔹 **1. Removed the Malicious Code**  
   - We manually **deleted the injected Google Ads script** from `header.php`.  

🔹 **2. Scanned for Malware & Backdoors**  
   - Used **Wordfence & Sucuri Security** to detect and remove any **hidden malware**.  

🔹 **3. Disabled & Deleted `wp-file-manager-pro`**  
   - Immediately **removed the plugin** from our website.  

🔹 **4. Reviewed WordPress Admin Users**  
   - Checked for **unauthorized admin accounts** and removed suspicious users.  
   - **Reset all administrator passwords** and enforced **Two-Factor Authentication (2FA)**.  

🔹 **5. Checked File Integrity & Plugin Logs**  
   - Manually reviewed **recent file modifications** in `/wp-content/plugins/` and `/wp-content/themes/`.  
   - Looked at the **plugin’s database records** for unauthorized changes.  

🔹 **6. Restricted File Upload Permissions**  
   - Implemented **server-side file validation** to prevent arbitrary PHP file uploads.  
   - Ensured **only specific file types (e.g., images, PDFs) could be uploaded**.  

🔹 **7. Reported the Plugin to WordPress.org**  
   - Submitted a **security report** to **WordPress Plugin Review Team**.  
   - Contacted **Google AdSense** to report unauthorized usage of `ca-pub-3838462999229532`.  

---

### **📌 What This Means for WordPress Users**  
- If you are using `wp-file-manager-pro`, **uninstall it immediately** and scan your site for malware.  
- **Unauthorized ads may redirect your traffic or steal revenue**.  
- **Ensure all plugins are updated** and remove any **suspicious or unused plugins**.  

---

### **🛡️ Preventing Future Security Issues**  

✅ **1. Avoid Untrusted Plugins**  
   - Download plugins **only from WordPress.org** or **trusted developers**.  

✅ **2. Use Security Plugins**  
   - Install **Wordfence, iThemes Security, or Sucuri Security** to detect **unauthorized changes**.  

✅ **3. Disable Direct File Editing**  

   - Add this to `wp-config.php` to **prevent file modification via the admin panel**: 

     ```php
     define('DISALLOW_FILE_EDIT', true);
     define('DISALLOW_FILE_MODS', true);
     ```

✅ **4. Regularly Scan for Malware**  
   - Use **MalCare** or **Wordfence** for **daily security scans**.  

✅ **5. Monitor User Activity**  
   - Install **activity log plugins** to track admin login attempts and file changes.  

✅ **6. Restrict File Upload Permissions**  
   - Allow uploads **only for trusted users** and enforce **strict file type validation**.  

---

### **🚀 Final Thoughts** 
 
This incident highlights **why it’s crucial to monitor WordPress plugins** for security risks. Attackers often target **vulnerable plugins** to **inject malicious code, steal data, or hijack revenue**.  

🔹 **Have you used `wp-file-manager-pro`?**  
🔹 **Noticed unusual ads or security issues?**  


---

🔒 **Security Team**  : BoxxHash 


---