If, because of incorrect customization, you cannot edit a zone in the WHM editor, which of the following WHM interfaces can you use to re-apply the zone template and remove any customizations?
- WHM » DNS Functions » Reset a DNS Zone.


Which of the following most accurately describes what happens when a zone contains two CNAME records with the same name?
- The zone is considered invalid. 

Which of the following described situations would utilize DNS resolution as a key component of its handling?
- To determine where to send mail for a domain.

Which of the following types of DNS cluster synchronization found in the WHM interface can be accurately described as the copying of all updated versions of local zone files from other servers in the cluster to this server?
- Synchronize all zones to this server only.

Diego is a web designer who operates his own cPanel & WHM server. He wants to create a test subdomain for one of his clients and upload some web content to it so that he can share a "beta" (non-production) version of the site to his client.

Which of the following interfaces should he start with, in order to accomplish this?
- cPanel » Domains » Subdomains

SPF and DKIM are resource records that help reduce which of the following?
- Spoofing and unauthorized senders.

Within which of the following WHM interfaces would you enter the default nameservers for accounts that a reseller creates?
- WHM Home >> Reseller Center >> Basic Reseller Setup

Which of the following statements most accurately describes the term clustering, in the context of a server hosting environment?
- Two or more servers that all serve the same purpose configured in a distributed, connected environment.

Which of the following DNS clustering synchronization types, found in the WHM interface, can be best described as the copying of all updated versions of local zone files to all servers in the cluster?
- Synchronize all zones to all servers.

Which of the following options accurately indicate a task that can be performed from within the WHM interface?
- Change an MX record.

Which of the following can be described as having the following major strengths?
Very high performance.
Low memory footprint.
- PowerDNS

Within which of the following WHM interfaces would you select the nameserver software that you wish to use?
- WHM Home >> DNS Services >> Nameserver Configuration

Which of the following types of authentication is used to establish DNS clustering, in a cPanel & WHM environment?
- API Token

The following options found in the Exim Configuration Manager - Basic Editor interface in WHM enables the checking of DNS resolution to see if the sender's domain exists?
- Sender Verification

Which of the following options best describes the term email reputation?
- It is a calculation of the likelihood of a message being spam based on other messages sent from the same server.

Nameserver address record setup in modern installations of cPanel & WHM, both within the Basic WHM Setup and Edit Reseller Nameservers and Privileges interfaces, provide support for certain DNS records associated which of the following types of hostnames?
- Hostnames that resolve to AAAA records.

Yudith runs a small web-hosting company. She has added and removed several zones manually but has accidentally deleted a zone belonging to a cPanel account. Fortunately, this zone did not contain any custom records. Given the situation, which of the following WHM interfaces should she utilize to re-create the zone?
- WHM » DNS Functions » Add a DNS Zone.

So why use DNS clustering?
- Redundancy, Load reduction

Which of the following options best describes the type of SpamAssassin options that appear in the Exim Configuration Manager - Basic Editor interface, found in WHM?
- Options that affect if and how Exim passes messages to SpamAssassin.

Which of the following options best indicate a legitimate reason that would describe why you would want to configure the forwarder address fields within the WHM Home » Server Contacts » Edit System Mail Preferences interface?
- To prevent "mailer daemon" messages from being sent to the incorrect destination.
- To prevent emails destined for "root" from getting frozen within the mail queue.
option 3 could also be a valid reason, but it's not the primary purpose of configuring forwarder addresses in this context.

Within which of the following WHM interfaces can you enable additional ports for Exim to listen for SMTP connections on?
- WHM Home » Service Configuration » Service Manager

Which of the following methods best indicate the recommended approach for backing up, restoring or resetting the system's Exim configuration?
- Use the corresponding functions found within the Exim Configuration Manager interface, in WHM.

If there is a long delay indicated when an email is being sent, the Mailer Daemon will send a warning message to which of the following destinations?
- The email's sender.

Given the following, which best describes an actual reason that the system may place a message into the Exim queue?
- The load average on the server is above the delivery threshold.

José sends an email message to Maria. If the system cannot deliver the message, José will get a notification from which of the following sources?
- The mailer daemon.

What actions can you perform in the WHM Home » Email » Mail Queue Manager interface?"
- Delete a particular message permanently so that is not delivered.

Justine's boss just told her that the authentication daemon for the mail server is broken. Which of the following options best indicates the component of the mail system that is affected by this?
- The component that validates user credentials.

Given the following, which option best describes an actual reason that the system may place a message into the Exim queue?
- There are DNS issues preventing Exim from finding the remote mail server.

Which of the following tools may help you to resolve issues indicated by the time moved backwards warning?
- The "ntp" tool.

In which WHM interface can you configure the forwarders for the root, cPanel, and nobody mail accounts?
- WHM Home » Server Contacts » Edit System Mail Preferences

Given the following options, which best describes something about an email address that can be determined by using the WHM Home » Email » Mail Troubleshooter interface, found in WHM?
- It will indicate whether the destination address forwards mail to a remote server.

Which of the following options best describes the behavior that occurs when a zone contains no MX records?
- The A record is used to determine where mail should be sent.

Which of the following options best describes the term recursive, in the context of DNS?
- A recursive nameserver can resolve non-local domains.

Which of the following statements best describes the term resolver?
- A nameserver that can resolve non-local domains.

Which of the following options indicates what the abbreviation TTL stands for, in the context of DNS?
- Time To Live; indicating how long a resource record should be cached.

Which of the following most accurately describes what happens when a domain with two NS records in its zone is queried?
- Both records are returned.

Which of the following most accurately describes what happens when a zone contains two CNAME records with the same name?
- The zone is considered invalid.

Which of the following described situations would utilize DNS resolution as a key component of its handling?
- To determine where to send mail for a domain.

Which of the following query returns the IP addresses of the nameservers for the IP address 10.9.8.7?
- dig +nssearch 8.9.10.in-addr.arpa

By default, cPanel creates SPF records in which of the following modes?
- Testing mode (non-production)

Which of the following statements most accurately describes the term clustering, in the context of a server hosting environment?
- Two or more servers that all serve the same purpose configured in a distributed, connected environment.

SPF and DKIM are resource records that help reduce which of the following?
- Spoofing and unauthorized senders.

Within which of the following WHM interfaces can you globally enable DKIM and SPF for all accounts?
- DNS Functions >> Enable DKIM/SPF Globally

Which of the following options most accurately describes the interface or interfaces that you would utilize to create reverse DNS zones from within WHM?
- WHM Home » DNS Zone Manager » Add a DNS Zone, and then WHM Home » DNS Functions » Edit DNS Zone.

Within which of the following WHM interfaces would you be able to add SPF and DKIM records to an account?
- WHM Home >> Account Functions >> Modify an Account

To add a PTR record that points the IP address 192.168.0.4 to mail.example.com, which zone would you modify?
- 0.168.192.in-addr.arpa

If for any reason you'd like to revert the existing zone for a domain back to the template, you can use the "Reset Zone" feature in WHM, which can be found at this path in the interface:
- DNS Functions >> Reset a DNS Zone

The hostname should always be changed within the WHM interface under
- Networking Setup >> Change Hostname

If the hostname does not resolve...
- Alerts will be sent via email automatically to notify the administrator that it would be highly recommended to set up the hostname as an FQDN.

Given the following options, which indicates the ideal source from which you should obtain your server's resolver IP addresses?
- Your hosting provider or data center.

Which of the following has the major weakness of having a considerably extended initial zone loading time, if the server contains a very large quantity of zones?
- BIND/named

Which of the following options accurately indicate a task that can be performed from within the WHM interface?
- Change an MX record.

If, because of incorrect customization, you cannot edit a zone in the WHM editor, which of the following WHM interfaces can you use to re-apply the zone template and remove any customizations?
- WHM » DNS Functions » Reset a DNS Zone.

Nameserver address record setup in modern installations of cPanel & WHM, both within the Basic WHM Setup and Edit Reseller Nameservers and Privileges interfaces, provide support for certain DNS records associated which of the following types of hostnames?
- Hostnames that resolve to AAAA records.

Within which of the following WHM interfaces would you enter the default nameservers for accounts that a reseller creates?
- WHM Home >> Resellers >> Edit Reseller Nameservers and Privileges

So why use DNS clustering?
- Redundancy, Load reduction

To manage DNS clustering in WHM, you can navigate within the interface to the:
- Clusters >> DNS Cluster

If the servers that are being clustered have existing zones on them, you will need to synchronize the zones. This can be done via the WHM interface at:
- DNS Functions >> Synchronize DNS Records

You can find a server's existing API tokens, or a create new ones within WHM's:
- Home >> Development >> Manage API Tokens

If a server's token has changed, you can re-assign a new token to it by editing the cluster node in:
- Clusters >> DNS Cluster

Which of the following types of authentication is used to establish DNS clustering, in a cPanel & WHM environment?
- API Tokens

After installing cPanel & WHM in a new environment, what is the initial, default state of DNS clustering?
- DNS clustering is initially disabled and must be manually enabled.

Which of the following best describes one of the primary, intended purposes of a DNSOnly server?
- Providing a means of establishing DNS redundancy in a cluster configuration.

Within which of the following WHM interfaces would you select the nameserver software that you wish to use?
- WHM Home >> Service Configuration >> Nameserver Selection

cPanel offers a DNSOnly installation specifically for using a standard cPanel & WHM environment in a DNS cluster configuration. Which of the following is the standard license cost associated with DNSOnly?"
- Free

Which of the following types of DNS cluster synchronization found in the WHM interface can be accurately described as the copying of all updated versions of local zone files from other servers in the cluster to this server?
- Synchronize all zones to this server only.

The system's administrator receives an email alert from WHM when which of the following conditions occur?
- The hostname does not point to the main IP address on the server.

Which of the following types of DNS cluster synchronization found in WHM can be best described as the copying of one updated zone file to the current server, based on the value you provide as the domain you wish to synchronize?
- Synchronize one zone to this server only.

When you use the supported 1:1 NAT setup in WHM, the List Accounts interface in WHM will display which of the following values in each accounts' listed IP address column?
- The public IP address.

Diego is a web designer who operates his own cPanel & WHM server. He wants to create a test subdomain for one of his clients and upload some web content to it so that he can share a "beta" (non-production) version of the site to his client.
Which of the following interfaces should he start with, in order to accomplish this?
- cPanel » Domains » Subdomains

If you have one DNSONLY server and three full cPanel & WHM servers, which of the following is recommended as the optimal cluster configuration, given this scenario?
- The cPanel & WHM servers should be set to push to the DNS Only server, which should not send updates back to the cPanel & WHM Servers.

All that really means is that the database consists of tables in which each entry, or row, in the table has a unique key.
- Relational Database

Each row or entry in a table must include which of the following components?
- Unique Key

To maintain data integrity, only one process can update any particular piece of data at a time. This is the mechanism used to ensure this.
- Locking

What is defined as a special data structure that makes lookups on large tables faster?
- Index

What is the data directory where MySQL data lives?
- /var/lib/mysql/

In a database's folder within the data directory, you see a number of files with MYD and MYI extensions. What table engine is being used for the tables represented by these files?
- MyISAM

Which of the following MySQL storage engines is the native default (native to MySQL - not necessarily in cPanel & WHM) engine used by MySQL versions 5.5.5 and above?
- InnoDB

Which of the following MySQL/MariaDB-related terms describe a data structure that improves operations' speed in a table accurately?
- Index

Which of the following terms can be described as the way that permissions are handled inside a MySQL or MariaDB database?
- Grants

Which of the following types of tables can you repair using the Repair a MySQL Database interface, found in WHM?
- MyISAM

In a cPanel & WHM environment, which of the following MySQL storage engines is set as the default?
- MyISAM

Which of the following is a term that indicates a trait of the object described by the table, or can be otherwise referenced as a table column?
- Field

Which of the following database-related terms defines marking a table or row so that only one process can access it a time?"
- Locking

This feature allows server administrators to grant ownership of database objects (databases and database users) to a cPanel user.
The cPanel user who owns a database can access and manage it through the cPanel interface.
- The Database Mapping Tool

cPanel uses what to keep track of what databases belong to which user.
- A map Previously, cPanel used prefixing to accomplish this.

This interface allows server administrators to retrieve a list of database users, each user's database, and which account owns each database user.
- Manage Database Users

You can use which WHM interface to change the MySQL root password.
- Home > SQL Services > MySQL Root Password

When a user's quota has been reached, what happens to their ability to write to databases?
- They are able to continue writing to their databases without restrictions.

Ananya has a website that writes data into a MySQL database. She was mail-bombed, and as a result, has gone over the quota that was set for her account by the WHM server administrator. Which of the following best describes what happens to her website now?
- It continues operating normally and no production impact is seen.

In modern versions of cPanel & WHM, what benefits can database prefixing, enabled from the SQL tab of the Tweak Settings interface in WHM, provide?
- Primarily cosmetic; helps server administrators identify database ownership, as well as providing auto-grouping in the phpMyAdmin interface.

The WHM Home >> SQL Services >> Manage Database Users interface in WHM can be used for which of the following purposes?
- Rename existing database users.

The WHM Home >> SQL Services >> Additional Access Hosts interface creates server-level grants that are similar to the grants that can be created in which of the following cPanel account-level Interfaces?
- cPanel Home >> Databases >> Remote MySQL

Which of the following definitions best describes InnoDB's data dictionary component?
- A part of the InnoDB storage engine that uses metadata to map structural information to the file it's stored in.

Which of the following actions occur when a user navigates to the Remote MySQL or MySQL Databases interfaces in a cPanel user-level interface?
- Grants are retroactively implemented for any new grants that have been added on the system by the administrator.

When using a cPanel & WHM environment, remote MySQL capabilities should be set up via the MySQL Profiles interface in WHM at which of the following stages of a server's operations?
- After installation, but before beginning to create production accounts on the server.

Which of the following options indicate the correct number of characters that a MySQL 4.1 password contains before being updated to the current standard of 41 character-hashes?"
- 16 characters.

Given the following options, which accurately describe a feature specific to the MyISAM storage engine?
- .MyISAM has repair capabilities that allow you to perform the REPAIR query, either directly or from the WHM interface, on tables that may have corrupted data or indexes

Using the Manage MySQL Profiles interface in WHM, what is the recommended maximum number of cPanel & WHM servers should be connected to each configured remote MySQL server?
- 1

What is the minimum version of MySQL that can be running on a remote server, in order for it to be used in a Remote MySQL Profile?
- 5.5

Which of the following options describes the best way to import a SQL dump into a PostgreSQL databases via the WHM interface?
- There are no features in WHM that provide this capability; it must be performed from the command-line.

Given the options below, which of these accurately indicate a point during WHM user interactions, which triggers the system to create grants for all pre-existing cPanel accounts, is based on the configurations set within the Additional MySQL Access Hosts interface?
- When the user clicks the link at the bottom of the Additional MySQL Access Hosts interface labeled "click here".

Running a REPAIR TABLE query, or performing repairs via the "Repair a MySQL Database" interface in WHM, will only have an effect on which of the two previously referenced table storage engines?
- MyISAM

Which of the following WHM interfaces would you use to configure a cPanel & WHM server to utilize a remote MySQL® server environment to handle its database operations?
- Manage MySQL® Profiles

WHM contains an interface feature that allows you to attempt an automatic repair on which of the following types of tables?
- MyISAM

Which of the following actions can you perform directly from within the WHM interface, without using phpMyAdmin?
- Change a database user's password.

Which of the following is one of the most common causes of MySQL upgrade failures?
- Aborting the upgrade, intentionally or otherwise, part-way through the procedure.
- The my.cnf file contains a number of non-default customizations that have not been verified prior to upgrading.

MySQL Profiles can set up what kind of relationship between servers
- 1-to-1 (1:1) only

Which of the following options describes an actual benefit of utilizing remote MySQL capabilities using the MySQL Profiles feature in WHM?
- Remote MySQL servers can reduce load on the WHM Server.

Which of the following details about the remote server would you need to know, if you wanted to set up a new remote MySQL profile in WHM?
- Remote SSH port

Which of the following best describes the MySQL root password's role in a cPanel & WHM environment?
- A password that is primarily handled via automated means by cPanel & WHM back-end services and can be reset as needed.

The WHM Home >> SQL Services >> Manage Databases interface allows you to do which of the following operations?
- Automate renaming of a MySQL/MariaDB database.

By default, what kind of remote MySQL access is allowed, given the correct user and password?
- No remote access is provided by default.

This installs, configures, updates, and validates your web server, as well as your PHP installation along with other components of your web server.
- EasyApache 4

What is the latest version of Apache supported by EasyApache 4?
- 2.4

If your system uses Tomcat, which version of cPanel & WHM would you need to be running in order to migrate to EasyApache 4?
- 76

EasyApache 4 is based on what type of packages?
- Redhat Package Manager

The most basic and often most important Apache configuration changes you can make can be found:
- Home >> Service Configuration >> Apache Configuration >> Global Configuration

What is the name of the feature used to provide support for multiple concurrently running PHP versions in EasyApache 4?
- MultiPHP

In modern installations of cPanel & WHM, how is the PHP version determined for newly created accounts, when System PHP-FPM status is set to ON?
- It is set to the same value as the system default.

Which of the following options is NOT a real Multi-Processing Module (MPM) available for installation within WHM's EasyApache 4 interface?
- Postfork

In a cPanel & WHM environment running EasyApache 4, which of the following RPMs would provide PHP 5.6 to the account?
- ea-php56

Which of the following options best describes the method you would use to install the PHP-FPM software, within a cPanel & WHM environment?
- PHP-FPM appears under the PHP Extensions stage of the EasyApache 4 profile customization walkthrough.

In a cPanel & WHM environment operating with EasyApache 4, one could define an EasyApache profile as which of the following?
- A collection of packages that can be provisioned.

Which of the following options accurately describes an action one performs in WHM's EasyApache 4 interface?"
- Install new PHP extensions for use in your active Apache/PHP environment.

Which of the following options accurately indicates the file syntax that can be seen within downloaded EasyApache 4 profiles?
- JSON

When operating in a cPanel & WHM environment running EasyApache 4, within which of the following WHM interfaces can you adjust the server's default PHP version?
- This can be adjusted from within WHM's MultiPHP Manager interface.


To change your server's default version of PHP or a virtual host's version of PHP, use WHM's MultiPHP Manager interface found:
- WHM >> Home >> Software >> MultiPHP Manager

If the version of PHP that you wish to use does not exist on your server, you can install it with the EasyApache 4 interface found:
- WHM >> Home >> Software >> EasyApache 4

What is the abbreviation for the resource that provides the packages that must be used if you want to include unsupported PHP versions in your EasyApache 4 installation?
- Software Collection Libraries, otherwise referred to by its abbreviation, SCL

In modern installations of cPanel & WHM, when selecting DSO from the EasyApache 4 interface without mod_ruid2 or mpm_itk, what recommendation will be displayed to you automatically, directly from within the EasyApache 4 interface?
- PHP DSO runs as the nobody user by default. In a shared hosting environment, this is a security issue.

In a cPanel & WHM environment, which of the following options accurately describes what the system default PHP version setting defined in WHM's MultiPHP Manager interface represents?
- The version that is used if a domain does not already have a specific version selected for it.

Which of the following options best describes the procedure needed to enable the BlueHost SymLink Protection Patch?
- Toggle the corresponding option found in WHM's Apache Configuration's Global Configuration interface.

If a user wants to utilize the system default version of PHP, which of the following selections would they enable for their account?
- inherit

Given the following options, select the components or component combinations that would provide standard per-user process ownership for handling PHP content.
- suPHP (mod_suphp) OR Ruid2 (mod_ruid2) OR PHP-FPM

Which of the following PHP handlers works on only one PHP version at a time?
- DSO

Which of the following options describes the appropriate method needed to enable PHP-FPM from within the WHM interface?
- PHP-FPM is enabled via WHM's MultiPHP Manager interface.

Do you remember what the typical PHP handler options are for a default cPanel & WHM environment?
- DSO
- suPHP
- CGI
- FCGI

This module is used in EA4 to provide the website an improved performance with greater security.
- mod_ruid2
Mod_ruid2 has a very simple function:
It ensures that the PHP processes that Apache creates are owned by the account that owns the domain the script is being executed from.

Apache doesn't always know how to deal with certain types of applications or code.
It uses this to determine what should happen when it encounters these things.
- Handler

Its role is similar to that of mod_ruid2 but simply addresses it at a different point in the HTTP conversation.
It instructs Apache to simply adjust the process' user and group identifiers prior to responding back to an HTTP request.
- ITK

This per-use module aims to accomplish the same result as ruid2 and ITK by simply running the CGI software as the account owner of the script being executed.
- suEXEC

This handler should be considered experimental in a cPanel & WHM environment.
- FCGld
Because of the way that FCGId operates, and its experimental status, it will not work with MultiPHP capabilities.
During PHP requests, which of the following statements accurately describes how the DSO handler processes the request?
- PHP handling operates internally by Apache's own processes.

Which interface can be used to set a virtual host's PHP version?
- cPanel & WHM

When operating in a cPanel & WHM environment, which of the following files are used by Apache to define the PHP configuration?
- /etc/apache2/conf.d/php.conf

You're operating in a PHP 5.6 environment and using DSO as your PHP handler. You've created a .user.ini file in your website's public_html folder, but are not seeing your changes reflected.
What most accurately describes the issue that is occurring here?
- An .htaccess file stored in public_html should be used instead, containing the appropriate syntax for declaring PHP values.

Of the following options, which of these handlers operate in a non-persistent state, requiring the creation of new PHP processes each time something is executed?
- suPHP

Which of the following options best describes one of the most notable behaviors that separates the DSO handler from other PHP handlers available in a cPanel & WHM environment?
- DSO does not create new "php" processes to handle requests, but instead works internally with Apache, spawning from the parent httpd process.

Which of the following accurately indicates the user that processes created for the DSO handler are owned by?
- nobody user

In modern installations of cPanel & WHM, which of the following PHP configuration values are set automatically during the Initial Setup Assistant steps?
- memory_limit

Besides increasing the speed of the build process, which of the following options describes another reason that EasyApache 4 provides an improvement over EasyApache 3
- Reduced chance of critical Apache failures.

Which of the following options accurately describe an action that one can perform from within WHM's EasyApache 4 interface?
- Install new PHP extensions for use in your active Apache/PHP environment.
- Change the MPM that is used in your Apache installation.

Which of the following Apache modules are core to Apache and can be disabled, but cannot be removed using the EasyApache 4 interface?
- mod_userdir

In modern installations of cPanel & WHM, EasyApache 4 will allow you to install which of the following versions of Apache?
- Apache 2.4

Which of the following options accurately describes an action one performs in WHM's EasyApache 4 interface?"
- Install new PHP extensions for use in your active Apache/PHP environment.

Which of the following EasyApache 4 profile actions can you perform from WHM's EasyApache 4 interface, in modern installations of cPanel & WHM?
- Upload a profile file from your file system or via a URL.

Which of the following options exist on the Configuration Settings tab within the WHM Home » Security Center » cPHulk Brute Force Protection interface in WHM?
- Minimum Failures by IP Address

Which type of attack does cPHulk help to protect against?
- Brute Force

What option does IP Address-based protection possess that Username-based protection does not?
- Command to Run (when brute force protection is triggered)

True/False: cPHulk is disabled by default on new installations.
- False

When a WHM login fails because cPHulk has blocked access, what do you see?
- "The login is invalid" in a red banner above the login box

True/False: You can enable/disable cPHulk during the Initial Setup Wizard after a fresh cPanel & WHM installation.
- True

True/False: The Brute Force Protection Period option controls the amount of hours per day that cPHulk stays active.
- False

A shared key is used by which type of user?
- Both

What kind of key to decrypt does a receiver use to see a sender's data?
- Public Key

A private key is used for performing what action on data?
- Encryption

A bundle of signed certificates creates what?
- Chain of Trust

Which of the following demonstrates trust in SSL?
- a chain of signed certificates leading back to an authoritative source

Encryption is
- Disguising data using mathematical functions

When you cannot decrypt using the same key you encrypted with, but instead with its unique counterpart, it's referred to as what type of encryption?
- Asymmetric

Which of the following does a self-signed certificate put you at risk of?
- Man-in-the-middle attack

When using an Organization Validated Certificate, which of the following statements accurately describes how the browser will indicate this in its address bar?
- Only a padlock indicating a valid SSL certificate.

When should you use a shared secret when creating a certificate, key, and CSR?
- Never

How do you remove an SSL certificate from a domain?
- click on the trash can icon in the Actions column next to the desired domain where they are listed on the page WHM Home » SSL/TLS » Install an SSL Certificate

When SNI is in use, which items are used to determine which virtual host to return? (Select all that apply)
- requested hostname
the IP address the client connected to

True/False: We recommend that you always have the generated certificate, key, and CSR emailed to you to serve as a backup.
- False

True/False: A larger key is more secure, but takes more resources to process each new SSL request.
- True

At what point does cPanel replace an expiring SSL with a self-signed certificate?
- The night before

Which option will force users using the /cpanel, /webmail and /whm URLs to use SSL?
- Redirection

Within which of the following cPanel & WHM user interfaces can you manage Domain TLS?
- None of these

In a cPanel & WHM environment, which of the following indicates the frequency that AutoSSL polls for pending certificates?
- Every 5 minutes the first day, every hour the second day, and once a day after that.

Which of the following services are NOT usable with WHM's Service SNI feature?
- mysql

You can add or remove SNI from the mail services on which page?
- It's enabled by default on main domains with SSL certificates.

True/False: The Tweak Setting "Require SSL" will redirect proxy subdomain entries to their secure counterparts.
- True

Which of the following causes a hostname mismatch warning? (Select all that apply)
- visiting a site on a shared IP address that does not have SSL enabled using https://
visiting www.domain.com for a site whose certificate is for domain.com

Which of the following causes an insecure content on a secure page warning?
- visiting a site with some images loaded with http instead of https

Why might a site look different when viewed with HTTPS rather than with HTTP?
- the site does not have its own SSL certificate, so Apache displays a different site on that IP address that does have a certificate.

The most common cause of the self-signed warning is
- It is a self-signed certificate

Which of the following can cause an expired certificate warning?
- the wrong date on the client computer

The default provider, cPanel (Powered by Sectigo), can secure how a maximum of how many domains per-certificate (or per-VirtualHost)?
- 1000

With AutoSSL enabled, what type of certificate are your websites automatically secured with?
- Domain-Validated (DV)

When a certificate issued by AutoSSL is going to imminently expire, which of the following does AutoSSL do?
- Automatically replaces them with an updated certificate, when AutoSSL runs its certificate checks.

Where can you see the next scheduled AutoSSL check time?
- In the Manage AutoSSL home interface within WHM

How often does AutoSSL perform a certificate check, if the age of the certificate request is less than one day?
- Once every five minutes

True/False: Setting a user to "Enable AutoSSL" does not override feature list settings applied for that user account.
- True

In computing terms, the "root" of something is:
- The start of something

Which actions can be performed from the Manage Service SSL Certificates page? (Select all that apply)
- install a new certificate on any of the SSL-capable services
- install a self-signed certificate for the server's
- hostname on any of the SSL-capable services

view the issuer, key size, and expiration data for the certificate installed on any of the SSL-capable services
The Tweak Setting "Always Redirect to SSL" redirects which method of logging in?
- /cpanel, /webmail, /whm URLs

Which of the following are parts of a certificate? (Select all that apply)
- CRT
- key
- CA Bundle

In modern installations of cPanel & WHM, you are able to purchase Extended Validation Certificates through which of the following cPanel Interfaces?
WHM's Purchase and Install an SSL Certificate interface.
Which services are SSL-capable? (Select all that apply)
- FTP
- webmail
- WebDisk

Which of the following does a web client check when receiving a certificate from a webserver? (Select all that apply)
- the expiration date is after the current date
- the connected hostname is covered by the certificate
- the certificate was issued by an authority that the browser trusts

When do SSL-capable services have self-signed certificates automatically installed? (Select all that apply)
- during the initial installation of cPanel & WHM
- the night before the certificate expires

True/False: The HTTP Header Response is the phase that delivers the HTTP status code.
- False

Which of the following describes ModSecurity?
- web application firewall (WAF)

Which of the following represent standard components of the SecRule syntax? (Select all that apply.)
- Operator
- Variables
- Actions

True/False: The Logging phase of an HTTP transaction still allows ModSecurity to perform connection filtering/blocking changes instructed by rules.
- False

After a fresh installation of cPanel & WHM, what is the initial state of the OWASP Vendor entry?
- Available, but not installed.

Which of the following actions can be taken from the primary ModSecurity Vendors home interface?
- Disable automatic ruleset updates for a vendor.

What does it mean when a hit entry has a blank value in the Hosts column of the Hits List interface?
- This hit did not originate from outside the server.

Who or what affects and/or changes the Staging value of a particular rule?
- The ruleset vendor.

True/False: It is possible to turn updates off, even when a vendor's rules set is installed and enabled.
- True

TRUE/FALSE: Only the Company Name value defined in the Public Contact tab of the Customization interface will be accessible to the public - not the Company Name value defined in the Customize Branding tab.
- True

What needs to be appended to a URL in order to retrieve the Public Contact information JSON data?
- cgi-sys/contact_details.cgi

When the Help Link field is defined, roughly where in the cPanel account interface does a "Help" link appear?
- In the footer (bottom right corner).

TRUE/FALSE: When a Company Logo image is provided, it will be displayed along with the text defined in the Company Name field, within the top bar of the cPanel account interface.
- False

What file format is required for the Favicon?
- ICO

What is the interface path where you can find the Customization section within WHM?
- Home >> cPanel >> Customization

Do you remember what file format is used for custom styles, when uploading or downloading them from the Customize Style tab of the Customization interface?
- gzipped tar

TRUE/FALSE: When you only define value in the Company Name field of the Customization interface, it will display the value as header text in the top bar of the cPanel account interface.
- True

Which of the following would be a reason to use the Mail profile?
- To help distribute the load for your server.

Which of the following services will always be disabled when using the Mail profile?
- httpd
- ftpd
- proftpd
- pureftp

What is the URL clients should use to access webmail?
- https://webmail.example.com/

What is the recommended method of dedistributing an account?
- Modify Account

A child node can use what version of cPanel compared to the parent node?
- The child node can use the same or newer version of cPanel that the parent node uses.

Which of the following is not a benefit to using Mail Node?
- No more spam email.

Which of the following services are disabled by default (include any optional services)?
- ftpd

You should have selected this answer
- httpd
- mysql
- postgresql
- proftpd
- pureftp

Which of the following statements is true?
- You can have multiple child nodes, but only 1 child per functionality per account.

When should you use the Managing Distribute Accounts feature within Link Server Nodes?
- Only in an emergency situation, such as if the child node is permanently down.

Which of the following is a reason to use the Mail Profile?
- To help distribute the load for your server.

Which of the following does not happen when you distribute an account to a mail node?
- Local mail is retained on the parent node perpetually.

If a parent node is on v96, which of the following versions (select all that apply) can the child node be on?
- v98
- v96 --

Select all server roles that are available for Mail Node (including optional roles):
- Send Mail
- Local Mail
- PostgreSQL
- Receive Mail
- DNS
- Spam Filter
-  Webmail
- Relay Mail
- Calendars and Contacts
- MySQL/MariaDB

What must you update the CNAME mail record to if you are manually editing the Zone Templates?
- mail IN CNAME %maildomain%

What happens if the IMAP/POP3/SMTP traffic does not automatically route to the child node?
- The parent server creates proxy IMAP and POP3 connections to the child node, and reroute SMTP mail delivery to the child node.

When is it recommended to make changes to the hostname of a linked node in the Link Server Nodes interface?
- Only to ensure it matches the current child node's hostname.

Is there downtime when offloading mail from a parent node to a child node?
- No, the automatic process will only delete email from the parent node after the child node has finished receiving all the mail.

What can a user do if they want to separate the quota between the Mail Node and the Parent Node?
- Nothing, the quota on the mail node will always be calculated along with the rest of the parent node's quota.

What interface allows you to link a child node to a parent node?
- Link Server Nodes

How should users access their webmail?
- http://webmail.example.com/

Enabling a Server Profile other than Standard Node will perform which of the following tasks?
- Hide interfaces and block API functions that are not permitted with the chosen Profile.

Which of the following does not apply to Mail Node servers?
- System and user configurations propagate from the child to the parent node.

In which of the following WHM interfaces would you enter the default nameservers for accounts that root creates?
- WHM Home >> Server Configuration >> Basic WebHost Manager Setup

Within which of the following WHM interfaces would you perform a graceful restart of the nameserver software?
- WHM Home >> DNS Services >> Restart Nameserver

As a WHM administrator, you receive the following email alert:
> The hostname server.example.com resolves to the 10.0.2.5 IP address. It should resolve to the 10.0.3.5 IP address.
What is the most likely scenario to have caused this notification to be sent? 
- The hostname does not point to the main IP address on the server.

Which of the following mail diagnostics are available within the WHM interface, and can help you troubleshoot mail?
- A diagnostic tool that performs a permission reset or a reset on an account’s mailbox files permissions on an account's mailbox files and folders.

Within which of the following WHM interfaces would you look to determine why the system did not deliver an email message?
- WHM Home » Email » Mail Delivery Reports

You can use the Exim Configuration Manager - Basic Editor to configure Exim to deliver mail without scanning messages based on which of the following criteria?
- When the message is over a certain size.

If you receive a report that emails from a particular user on your server are not being delivered to the inbox or bounced back, and you see a green checkmark icon next to the message when you check the WHM Home » Email » Mail Delivery Reports interface, what is the most likely explanation for this icon?
- That the message was delivered successfully to a folder other than the inbox.

All mail from a specific user is neither delivered to the inbox nor bounced. When you check the WHM Home » Email » Mail Delivery Reports interface, you see a funnel-shaped icon next to the message.
Which of the following options best describes what this probably indicates?
- The message was likely rejected at SMTP-time due to spam-like characteristics.

If you suspect that mail sent to the user who is over their quota is not delivered, which of the following WHM interfaces might you look to confirm why the message was not delivered?
- WHM Home » Email » Mail Queue Manager

Given the following options, which accurately describe the Mail Troubleshooter interface's behavior, found in WHM?
- It sends an actual test message, but only to local destinations on the server.

The following items from the WHM Home » Service Configuration » Exim Configuration Manager - Basic Editor interface would allow you to exclude mail sent from specific remote IP addresses or hostnames from being subjected to recipient verification checks, sender checks, spam checks, and relay checks?
- Trusted SMTP IP Addresses

When mail is delivered to "/dev/null”, which of the following statements accurately indicate what happens to the message?
- The message has been permanently deleted.

What does it mean when a mail server "relays" its mail?
- It is handing mail off to another mail server for delivery.

Which of the following Mail interfaces in WHM can provide you with a historical snapshot of the mail queue?
- Mail Queue History

Which of the following options describes one of the commonly known characteristics, though are not always indicative, of an average spam email message?
- The message has a "BCC" address defined.

Which of the following options describes an action that can be performed from within WHM's MultiPHP Manager interface?
- You can turn on PHP-FPM, per-virtual host, from this interface.

Why is it suggested against using PHP DSO without mod_ruid2 or mpm_itk?
- PHP DSO runs as the user nobody by default. In a shared hosting environment, this is a security issue.

In modern installations of cPanel & WHM, which of the following PHP configuration values are set automatically during the Initial Setup Assistant steps?
- max_execution_time
- memory_limit --

Which of the following statements accurately describe a situation in which DNS zone templates would be useful, in a cPanel & WHM environment?
- Any time that similar customizations are needed across all hosted accounts.

In what mode does cPanel create SPF records by default?
- "Soft fail" mode (production or non-production)

As a WHM administrator, you receive the following email alert:
The hostname server.example.com resolves to the 10.0.2.5 IP address. It should resolve to the 10.0.3.5 IP address.
What is the most likely scenario to have caused this notification to be sent? 
- The hostname does not point to the main IP address on the server.

What happens when a domain with two NS records in its zone is queried for its NS records?
- Both records are returned.

Within which of the following WHM interfaces would you perform a graceful restart of the nameserver software?
- WHM Home >> DNS Services >> Restart Nameserver

In which of the following WHM interfaces would you enter the default nameservers for accounts that root creates?
- WHM Home >> Server Configuration >> Basic WebHost Manager Setup
