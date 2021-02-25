# Python Easy Logger
*An easy to implement & foolproof logger for your precious Multi-Modular applications*

---


Do you have a multi-modular python application and want to swiftly enable logging in it?
Are you tired of Initializing logger in your every module and keeping track of it ?
Is your Python logger not working as it is supposed to ?
Do you want different kind of logging happening together with minimal code ?

If the answer is 'YES' to any of the question above then you have come to the right place.

We have written an easy to implement wrapper for you that prevents you from scratching your head for the small logging issues you might encounter.

## Features

---

*   Python Easy Logger is an easy to use wrapper for the [Python Logging Library](https://docs.python.org/3/library/logging.html).
*   Compatible with Python 3.x
*   Makes use of Logging Configuration which allows switching the type of logging required without modifying the source code. Helpful especially in the case of compiled application for distribution.
*   Easy to import and single line initialization in the module
*   Supported level of Logging include Debug, Info, Warning, Error & Critical


## Getting Started

---

Just download the module \[ Logger.py \] with the config \[ logging.conf \] and place in it your working directory of the project.

## How To Use

---

Import the Easy-Logger Wrapper into your Script/Module
```
import Logger
```

Then initialize it in the main indent
```
logger = Logger.Logger("Program Or Module Name")
```
And that all. Now you can log your heart out throughout your module using :

```
*   logger.debug("Your Debug Log Message")
*   logger.info("Your Info Log Message")
*   logger.warning("Your Warning Log Message")
*   logger.error("Your Error Log Message")
*   logger.critical("Your Critical Log Message")
```
## Advanced Usage

---

There are two level of details in the Easy-Logger at the moment
*   root
*   brief
The level can be changed easily when initializing the module

```
logger = Logger.Logger("Program Or Module Name",'brief')

logger = Logger.Logger("Program Or Module Name",'root')
```
## Upcoming

---

*   Example Code
*   More level of details handlers in the Easy-Logger
*   Details about modifying the configuration file
*   Logs rotation details
*   Network Logging
*   More Log Formats