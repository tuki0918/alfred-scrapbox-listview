# alfred-scrapbox-listview

## Usage

+ Typing "sb" will fetch a list of scrapbox items.

```
$ sb [keyword]
```

![image](.resources/0.alfred.png)

## Installation

+ Depended on [jq](https://stedolan.github.io/jq/) command.
+ Import this `.alfredworkflow` file.
    + (required) `projectId` ... ex) ######
        + My Page URL: `https://scrapbox.io/######/`
    + (required) `token` ... ex) ######
        + My Logined Cookie: `Cookie: connect.sid=######`
    + (option)   `endpoint` ... ex) scrapbox.io
        + Scrapbox's Domain Name
    + (option)   `JQPATH` ... ex) /usr/local/bin
        + jq command PATH

![image](.resources/1.alfred.v0.2.png)
![image](.resources/2.alfred.v0.2.png)

## Note

Created by Alfred ver 4.1
