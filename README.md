 ​
# DEBO LEECHER
2
​
3
DeboLeecher allows you to leech (re-upload) contents from internet including torrent to telegram. This bot using Telegram MTProto powered by pyrogram.
4
​
5
## Feature
6
​
7
* Set as Private (using password)
8
* Able to use at group
9
* Able to leech larger than 2GB (telegram max upload at once)
10
* Split as video (.mp4, .mkv, .avi, .webm, .wmv, .mov)
11
* Upload files as media or as document
12
* Upload files as a single zip file
13
* Custom thumbnail
14
* Default torrent tracker
15
* Customizeable language (default is english)
16
* Configuration using environment variable
17
​
18
## Configuration
19
​
20
Change config by set the corresponding environment variable name.
21
​
22
* `WORKDIR` : working directory path
23
* `LOG_FILE` : log file name
24
* `MAX_LOG_SIZE` : maximum log size
25
* `EDIT_SLEEP` : delay between edit message
26
* `UPLOAD_MAX_SIZE` : maximum file size (in bytes) upload at once (watchout telegram max upload size)
27
* `UPLOAD_AS_DOC` : upload any files as document (1 or 0)
28
* `UPLOAD_AS_ZIP` : upload any files as a bundled zip file (1 or 0)
29
* `ARIA2_DIR` : download directory before uploading
30
* `TORRENT_TRACKER` : addition tracker for all torrent, separated by (`,`)
31
* `BAR_SIZE` : bar size on upload and download
32
* `THUMBNAIL_NAME` : default thumbnail file name
33
* `LOCAL` : languange bot using
34
* `CHAT_ID` : default chat_ids that have access to bot, separated by (`,`)
35
​
36
## Deploy button
37
​
38
[<img src="https://deploy.cloud.run/button.svg" alt="Run on Google Cloud" height="40"/>](https://deploy.cloud.run?git_repo=https://github.com/azamaulanaaa/botkaca.git "Google Cloud")
39
[<img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku" height="40"/>](https://heroku.com/deploy?template=https://github.com/azamaulanaaa/botkaca "Heroku")
40
​
41
*Currently google cloud does not supported due to app.json clash with heroku. Check out Google Cloud Run issue [#112](https://github.com/GoogleCloudPlatform/cloud-run-button/issues/112#issuecomment-663858778 "Both Cloud Run Button and Heroku Button - app.json Clash")*
42
​
43
## How to run
44
​
