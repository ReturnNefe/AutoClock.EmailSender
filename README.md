# AutoClock.EmailSender

A plugin of [AutoClock](https://github.com/ReturnNefe/AutoClock).

AutoClock.EmailSender can send an email when when plugins failed to clock-in.

## Installing

1. Download plugin file from [Releases](https://github.com/ReturnNefe/AutoClock.EmailSender/releases).
2. Unzip the file into ``AutoClock/plugins/EmailSender``.
3. Configure ``config.txt`` by reading **Configuration**.

## Configuration

Edit ``config.txt`` in the base directory.

```json
{
    // the mail server of the mail-sender
    mailServer: "",
    
    // the key of the mail-sender
    key: "",
    
    // the mail address of the mail-sender
    sendUser: "",
    
    // the mail address of the mail-receiver
    receiveUser: "",
    
    // the title of the email
    title: ""
}
```