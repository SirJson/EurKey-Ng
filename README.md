# EurKeyNg

A fork of http://eurkey.steffen.bruentjen.eu/ and https://github.com/alexmick/EurKey-Win

All credit to Steffen Brüntjen for the EurKey layout and Alexander Micklewright for uploading it to GitHub

## Motivation

This repository exists because the EurKEY servers seems to be unstable at times. After I found a fork on GitHub I forked it myself for preservation.

## Changes

Because I prefer not to install some random binary I installed [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339) myself and had a look at the layout. Compared to the Github Fork I removed the binding on VK_OEM_5 since I don't use a French Keyboard. I still noticed that the `±` and `§` are missing so I moved them to keys that had been double assigned.

I also removed the most "dead keys" and converted them to normal keys. I think they are not really user friendly and belong into Vim and not a keyboard layout.

## Install

Don't trust random people from the internet. I recommend installing the [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339) and create the Setup yourself from the EurKeyNg.klc file. The program is free and building is really easy.

If absolutely can't build it yourself I provided a compiled version of it in the release section.
