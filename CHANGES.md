<!-- markdownlint-disable  MD013 -->
# dkb-robo changelog

This is a high-level summary of the most important changes. For a full list of changes, see the [git commit log](https://github.com/grindsa/dkb-robo/commits) and pick the appropriate release branch.

## Changes in 0.10.3

**Bugfixes***:

- daf35c9 improved checking account detection (DKB removed the "Cash im Shop" link)
- d40200e0 fix for faulty TAN handling reported in #18

## Changes in 0.10.2

**Bugfixes***:

- 14ba22c7 fix for "Kontoauszugsdownload"

## Changes in 0.10

**Features**:

- Ability do download documents from DKB Postbox
- Tan2go support

## Changes in 0.9

**Features**:

- MFA support limited to confirmation via DKB-app and TANs generated by ChipTan method
- Debug mode

## Changes in 0.8.3

**Bugfixes**:

- Some smaller bug-fixes in dkb_robo and unittests

## Changes in 0.8.2

**Bugfixes**:

- fix typos - thanks to tbm

## Changes in 0.8.1

**Features**:

- Transactions for checking accounts and credit cares are based on CSV file downloadable from website
- Support of non dkb-accounts in account overview and transaction list
