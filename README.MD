# Keyboard Acoustic Emanations datasets

This repository holds 5 distinct datasets, each containing recordings of sounds
of individual keystrokes. These datasets were created for classification
purposes for the bachelor thesis *The sound of typing: using Machine Learning to
classify Keyboard Acoustic Emanations* by Marcin Gólski, Piotr Kaszubski and
Bartłomiej Woroch.

## Dataset structure

Each dataset contains 110 (100 train + 10 test) recordings of each of 43 physical
keys: `A-Z`, `0-9`, `'-'` (dash), `';'` (semicolon), `"'"` (quote), `','`
(comma), `'.'` (period), `'/'` (forward slash) and `' '` (space).

Every train and test set is stored as a .wav file and a corresponding .keys
file. A .keys file describes the offset in seconds of each keystroke within a
corresponding .wav file, stored in plain text format.

## More information

For more information on how the datasets were recorded, their structure, and how
to use them, please read the original paper and check the official source code
repository: <https://github.com/RoyalDonkey/put-kbd-thesis>.
