# (Unofficial)NCSC_3_word_passgen

## NOTICE: This tool is not endoursed by the NCSC or any other goverment or commercial entity but takes inspiration from NCSC publicly avalaiable informatiom.

# Password Generator

This is a simple password generator script written in Python. It uses the Tkinter library for the GUI and generates passwords that consist of three words, each word starts with a uppercase letter the password will have a special character, and a two-digit number. 
There is a bit of logic in there to ensure the password length will always be 12 or more characters long.

## How it Works

The script reads a list of words from a text file. It then randomly selects three words, capitalizes them, and concatenates them. It also generates a random special character and a two-digit number, and appends them to the end of the password. The password is then displayed in the GUI.

## Setup

Update line six, enter a path to your wordlist. A wordlist has been provided it has thousands of words.
Lines 8, 9 and 10 control word miniuim length.


## Usage

To use this script, simply run it and click the "Generate Password" button. A new password will be generated each time you click the button.

## Requirements

- Python 3
- Tkinter library
