# Anking's Medical and Drug Terms Keyboard Maestro Macro

## What is it?

This is 2 importable macros for [Keyboard Maestro](https://www.keyboardmaestro.com/main/) (Mac only. Windows users see below). These macros act as a text expander for quickly typing long or difficult to spell disease and drug names.

1. Med Terms: These are terms based on the [USMLE content outline](https://www.usmle.org/pdfs/usmlecontentoutline.pdf). 
2. Drug Terms: These terms are generic and brand drug names

<p align="center">
  <img src="https://raw.githubusercontent.com/AnKingMed/MedTermsList/main/KM%20macro.gif?raw=true" width="400">
</p>

## How do I download it?
Download this [zip file](https://github.com/AnKingMed/MedTermsList/archive/refs/heads/main.zip). Unzip the files and double click the `MedTermMacros.kmmacros` file to open it in [Keyboard Maestro](#what-is-keyboard-maestro).

## How do I use it?
1. To use the medical terms search filter, simply type `.md` and a search bar will come up. Then you can type the search term you are looking for and suggestions will come up. You can use the use the arrow keys (<kbd>↑</kbd><kbd>↓</kbd>) to select a suggestion and <kbd>Enter</kbd> to insert the text.
2. To use the drug terms search filter, simply type `.rx`. This will work in the same way that the medical terms search filter works.

\*_When used without internet connection, it will pull terms from `KM-MedTerms.txt` and `KM-RxTerms.txt` files from your `~/Documents` folder (they are created with the use of this macro)._

## What is Keyboard Maestro?
20% off Keyboard Maestro discount available on  [https://www.ankingmed.com/discounts](https://www.ankingmed.com/discounts)  (non-affiliate)

## How do I add or change words in the list?
You can suggest a Pull Request on this GitHub account! The Macro pulls the list from here as long as you have an internet connection.

\*_You can also click the edit icon at the top right of the page and GitHub will automatically fork and create a Pull Request with the changes._

## What if I'm a Windows users?
Unfortunately, Keyboard Maestro doesn't work on Windows. However, we did find [this software](https://www.phraseexpress.com/download/) that works. Download the .txt files and import into Phrase Express. It will import as a folder. You can then set an "Autotext abbreviation" (i.e. `.md` or `.rx`) to the folder and have "Show in popup" checked. Doesn't work as well, but it's something
