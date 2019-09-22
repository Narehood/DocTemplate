---
title: Ubuntu
category: Installation
order: 1
---

<img class="doc-img" src="{{ site.baseurl }}/images/ubuntu.png" alt="Ubuntu" style="width: 75px; float: right;"/>

Installing MusicBot on Ubuntu via the command line is the **recommended way to install the bot**, though the system dependencies differ depending on what version of Ubuntu you are using. Firstly, lets install the dependencies required for your system:

## Ubuntu 18.04

~~~ bash
# Install build tools
sudo apt-get install build-essential unzip -y
sudo apt-get install software-properties-common -y

# Install system dependencies
sudo apt-get update -y
sudo apt-get upgrade -y
~~~

## Ubuntu 16.04

~~~ bash
# Install build tools
sudo apt-get install build-essential unzip -y
sudo apt-get install software-properties-common -y

# Install system dependencies
sudo apt-get update -y
sudo apt-get upgrade -y
~~~

## Ubuntu 14.04

~~~ bash
# Install build tools
sudo apt-get install build-essential unzip -y
sudo apt-get install software-properties-common -y


# Install system dependencies
sudo apt-get update -y
sudo apt-get upgrade -y
~~~
