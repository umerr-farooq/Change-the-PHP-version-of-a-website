#How to Change PHP Version for a Specific Folder or a Subdomain
You can change the PHP version for a specific folder of a subdomain by editing the .htaccess file. This method allows you to use multiple PHP versions on the same account.

```
<FilesMatch "\.(php4|php5|php3|php2|php|phtml)$">
SetHandler application/x-lsphp81
</FilesMatch>
```

Copy and paste the following command to the beginning of the .htaccess file to install PHP 8.1. To install a different PHP version, change 81 with your desired version number. Read our PHP version change article to view other useful commands.
