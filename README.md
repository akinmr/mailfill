# mailfill
Fill mail template from csv file

## Usage
- Create mail template file and save as template.eml
	- You can save mails in Draft folder of Thunderbird via UI or IMAP Maildir
	- Mail encoding should be UTF-8 and not base64-encoded
	- Write placeholder as AAAAAAAA (A x 8) for column A, it supports upto column Z
- Create filler CSV file and save as data.csv
- Execute
	- Each mail is saved as output-#.eml
- Put them to mailer's Draft directory
	- If you are using Maildir format in Dovecot IMAP, place under ~/Maildir/.Drafts/new/
