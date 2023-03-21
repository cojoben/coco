# coco
Exploit Title:  Medicine Tracker System-XSS injection vulnerability

Date: 2023.3.21

Exploit Author: coco

Vendor Homepage: https://www.sourcecodester.com/php

Software Link: https://www.sourcecodester.com/php/16308/medicine-tracker-system-php-oop-and-mysql-db-source-code-free-download.html

Tested on: XAMPP

In the Medicine Tracker System, users are allowed to record their daily medication status for easy tracking, but the system has an XSS vulnerability that is rated as medium risk.

The vulnerability is in the user's daily medication interface, where users can perform storage row XSS injection when adding new drugs as long as they log in. The destination address is: http://localhost/php-mts/app/?page=medicines

The test code is: alert ("xss success!")

This vulnerability has an effect on both the title and content, and if maliciously exploited, it may lead to user data theft.
