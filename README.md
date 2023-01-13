[![Codacy Badge](https://app.codacy.com/project/badge/Grade/495cf6fc5be8434ca7b493ff88724433)](https://www.codacy.com/gh/dream-alpha/DreamOsCockpit/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=dream-alpha/DreamOsCockpit&amp;utm_campaign=Badge_Grade)

<a href="https://gemfury.com/f/partner">
  <img src="https://badge.fury.io/fp/gemfury.svg" alt="Public Repository">
</a>

# DreamOsCockpit (DMC)
## Features
- DMC contains fixes for OE2.5 and OE2.6 images that will be installed on top of the image.

## Limitations
- DMC supports DreamOS only
- DMC is being tested on DM 920 and DM ONE only

## Installation
To install DreamOsCockpit execute the following command in a console on your dreambox:
- apt-get install wget (required the first time only)
- wget https://dream-alpha.github.io/DreamOsCockpit/dreamoscockpit.sh -O - | /bin/sh

The installation script will also install a feed source that enables a convenient upgrade to the latest version with the following commands or automatically as part of a DreamOS upgrade:
- apt-get update
- apt-get upgrade

## Links
- Package feed: https://gemfury.com/dream-alpha
