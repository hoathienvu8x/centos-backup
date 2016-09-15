# centos-backup

CentOS backup is a bash script witch can be used to backup, upload and send notification to mail

It's written in bash scripting language

## Features
* Upload to google driver, dropbox
* No password required or stored
* Simple step by step configuration wizard

## Getting started

First, clone the repository using git (recommended):
```bash
git clone https://github.com/hoathienvu8x/centos-backup/
```

or download the script manually using this command
```bash
curl "https://github.com/hoathienvu8x/centos-backup/archive/master.zip"
```

Then give the execution permission to script and run it:

```bash
$chmod +x centos-backup/api
$sh centos-backup/api
```

To edit or create your own crontab file, type the following command at the UNIX / Linux shell prompt:

```bash
$ crontab -e
```

Append the following entry:

```bash
0 5 * * * sh /path/to/api
```

Save and close the file.

This command is run script every day on 5h am