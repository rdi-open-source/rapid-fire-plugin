# Rapid Fire

Rapid Fire - Copying live data on IBM i

## Description

Do you have files with millions or even billions of records? Imagine you have to change such a file, e.g. because a new field has to be added. Possibly you have the time to install this change at the weekend. But what if your shop works 24 hours a day, 7 days a week? In this case, it is absolutely necessary to reduce the time needed for the installation to avoid a long shutdown of the system.

This is where Rapid Fire comes in. With Rapid Fire, it is possible to reduce the downtime of your system to a minimum. Instead of shutting down the system for hours or even days, you are offline for just a few minutes.

Further information about Rapid Fire is available on the [Rapid Fire Site](https://rdi-open-source.github.io/rapid-fire/).

How Rapid Fire works is described in the [Rapid Fire manual](<https://rdi-open-source.github.io/rapid-fire/files/Rapid Fire.pdf>).

## Features

* Copies the data of a file into the new file in a shadow library, while the users keep on working.
* Generates the RPG program that copies the data.
* Starts journaling the file and applies the changes made during the copy from the journal.
* Reduces the downtime of your system to a couple of minutes.
* Creates, tests, starts and monitors the Rapid Fire jobs in RDi, with a view of the file copy status.
* Activity plan: the time frames in which a job is allowed to copy data.

## Requirements

* IBM i 7.2 or later for the Rapid Fire library.
* RDi 9.6.0.13 or later.
* The FTP server of the IBM i, for transferring the Rapid Fire library from RDi.

## Installation

1. Select **Help > Install New Software...** in RDi.
2. Enter the update site `https://rdi-open-source.github.io/rapid-fire/update-site/eclipse/rdi8.0/` and select the features of Rapid Fire.
3. Finish the wizard and restart RDi.

Then install the Rapid Fire library on the IBM i, see [Install Instructions](https://rdi-open-source.github.io/rapid-fire/help/html/install/install_library.html) in the help.

## Usage

How to use Rapid Fire is described in the [help](https://rdi-open-source.github.io/rapid-fire/help/). It is part of the plug-in as well: **Help > Help Contents > Rapid Fire** in RDi.

## Liability

This software is free and provided without warranty. You use it at your own risk: test it with non-critical data first, and back up your data before you use it. The [license](LICENSE) applies in addition.

## See Also

* [Rapid Fire Update Site](https://github.com/rdi-open-source/rapid-fire)
