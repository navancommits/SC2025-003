# Patch Installation Instructions

**Before applying the patch, it is advisable to perform a backup of the following files in your instance:**

- `\sitecore\shell\Applications\Dialogs\Upload\Upload.xml`
- `\sitecore\shell\Applications\Dialogs\Upload\Upload2.aspx`

---

**To apply this patch:**

- Open the Sln in VS 2022 Community Edition in admin mode
- Once opened, for the project, create publish profile to point to your local web root folder
- Then, publish Visual Studio project
- Check Showconfig.aspx to find the latest configs

**Reference**
https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1003667
