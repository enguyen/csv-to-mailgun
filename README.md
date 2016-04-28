# csv-to-mailgun
A little bash script for create email forwarding Routes on Mailgun.com from a CSV file. I found it useful for migrating a whole domain's mess of forwarding rules from a random email provider to use Mailgun instead. Mailgun provides faster, more robust email processing. Much more sophisticated processing is possible -- this just gets a dumb mess of forwards working for you.

From the in-script help:
```
Usage: .mailgun.sh APIKey file
  * APIKey: Your Mailgun API key
  * file: The CSV file to read from. First column are From: email addresses. All other columns are the emails to forward to.
```

Learn more:
 * [Mailgun](http://mailgun.com)
 * [Getting your Mailgun API key](https://help.mailgun.com/hc/en-us/articles/203380100-Where-can-I-find-my-API-key-and-SMTP-credentials-)
