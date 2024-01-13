Google hacking, also known as Google dorking or Google hacking database searches, involves using advanced search operators to discover sensitive information indexed by Google. This technique is often employed in ethical hacking to identify potential vulnerabilities or gather information about a target. Below are notes on Google hacking in ethical hacking, along with a list of commonly used tools:

### Google Hacking in Ethical Hacking:

1. **Definition:**
   - Google hacking involves using specialized search queries (Google dorks) to find information that search engines have indexed about a target, potentially revealing sensitive data or vulnerabilities.

2. **Objectives:**
   - Identify exposed services, files, or directories.
   - Discover information leaks or misconfigurations.
   - Gather intelligence about a target's online presence.

3. **Google Dorks:**
   - **Site-specific Searches:**
     - `site:example.com` - Search within a specific domain.
   - **Filetype Searches:**
     - `filetype:pdf` - Search for specific file types.
   - **Intitle/Inurl Operators:**
     - `intitle:"index of"` - Find directories listing files.
     - `inurl:admin` - Locate URLs with "admin" in them.
   - **Link Operator:**
     - `link:example.com` - Find web pages that link to a specific domain.
   - **Cache Operator:**
     - `cache:example.com` - View Google's cached version of a site.

4. **Common Google Hacking Techniques:**
   - **Finding Open Directories:**
     - Use directory listing queries to discover exposed directories.
   - **Locating Vulnerable Files:**
     - Search for common filenames or configuration files.
   - **Discovering Log Files:**
     - Look for log files that may contain sensitive information.

### Tools for Google Hacking:

1. **Google Search Operators:**
   - **site:**
   - **filetype:**
   - **intitle:**
   - **inurl:**
   - **link:**
   - **cache:**

2. **Google Hacking Database (GHDB):**
   - A database of Google dorks maintained by ethical hackers and security professionals.

3. **Google Hacking Database (GHDB) Scraper Tools:**
   - **Ghunt:**
     - A tool to extract information from the Google Hacking Database.

### Examples of Google Dorks:

1. **Find Open FTP Servers:**
   ```
   intitle:"index of" inurl:ftp
   ```

2. **Search for WordPress Configuration Files:**
   ```
   filetype:log inurl:wp-config
   ```

3. **Find SQL Databases:**
   ```
   filetype:sql
   ```

4. **Discover Exposed Cameras:**
   ```
   inurl:"/view/index.shtml"
   ```

5. **Locate Sensitive Documents:**
   ```
   intitle:"index of" filetype:doc OR filetype:pdf OR filetype:xls
   ```
It's important to note that Google is continuously refining its algorithms and indexing policies, affecting the effectiveness of certain Google hacking queries over time. Therefore, ethical hackers should stay informed about changes in search engine behavior.
