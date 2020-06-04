# pbbackup
Archiving tool for [2020PB](https://github.com/2020PB/police-brutality)
## Prerequisites
- [youtube-dl](https://youtube-dl.org/)
- [pageres](https://github.com/sindresorhus/pageres)

## Instructions

1. Clone the [2020PB](https://github.com/2020PB/police-brutality) repo
2. Clone this repo
3. Provided that the two repos are within the same parent folder, you should be able to ./pbbackup

## Explanation
pbbackup will download any video provided one is available and  then screenshot the page, if there is no video it will just screenshot the page. Then it puts these both in a numeric sub-directory whose parent directory is the location of the incident i.e Arkansas > 0 > video.mp4

A cron job could be used to automate this process by pulling the [2020PB](https://github.com/2020PB/police-brutality) repository and then running this script. The script is set up so there shouldnt be any duplicate files.
