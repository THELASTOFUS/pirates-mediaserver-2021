# Pirates Mediaserver [![Build Status](https://travis-ci.org/sayem314/pirates-mediaserver.svg?branch=master)](https://travis-ci.org/sayem314/pirates-mediaserver)

## About

This repository contains scripts for setting up a private media-server. This script can install Plex, Sonarr, Radarr and Jackett on the fly.

## Requirements

At this moment only following distros are supported.

|   Debian    |   Ubuntu    |    CentOS    |
| :---------: | :---------: | :----------: |
| Recommended |  LTS Only   | Experimental |
|     7-9     | 12.04-16.04 |    6 & 7     |

## Install

Fixed some things from the 4 year old one. Does not work for Jackett or Radarr... Plex and Qbittorrent NOT tested

Just execute below code to install them all.

`wget https://git.io/setup.sh -O - -o /dev/null|bash`

To exclude certain apps follow these instructions:

### Step 1

Download script: `wget https://git.io/setup.sh -O setup.sh`

Make it executable: `chmod +x setup.sh`

### Step 2

Now use variable like this: `PLEX=no JACKETT=No ./setup.sh`

This will install everything else except Plex and Jackett. Hope this explain basic usage.

_There is also specific install instruction available on each folder_
