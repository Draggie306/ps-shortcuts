# ps-shortcuts
Repositiory of quick and easy-to-run Windows shortcuts that are designed to improve system performance, simplify monotonous tasks and reduce bloat. Useful for IT admins, network managers and people who want a quick way to improve their system, and save time.

# How to run
These shortcuts all use PowerShell. To run them, please inspect the code in the repository to confirm that they are what you want to run. Then, open a Windows Terminal/PowerShell window as administrator, the quickest way to do this is by using Windows + X, then pressing "A" as a keyboard shortcut.

As these are designed to be ran quickly so that you, as an IT administrator or network manager, the short `geog.uk` domain is being used, followed by a slash and the letter of what you want to run. 

The syntax of the command is as follows, using standard Windows practice:

```
irm https://geog.uk/<SHORTCUT_LETTER> | iex
```
(for even shorter writing, you can omit the `https://` and the space after the `|`, looking like `irm geog.uk/<SHORTCUT_LETTER> |iex`)


where:
- `irm` is short for "Invoke-RestMethod". This downloads the file from the URL.
- `| iex` is a pipe, followed by "Invoke-Expression"; this runs the shortcut that was downloaded.
- `<SHORTCUT_LETTER>` is replaced by the letter of the shortcut to run, e.g. `a`, so the overall script looks like: `irm geog.uk/a |iex` (in the shortest possible format).

# Shortcut List

- `a`
 - Shortcut for Chris Titus Tech's winutil, which is itself a wrapper for a range of installations, tweaks and settings.
- `b`
  - Quick installer for the Draggie Games Client and AutoUpdater.  


# Contributions
Please open a pull request or, using the issues tab, suggest something that would be beneficial to include on here! All projects and scripts must be valid and be from trustworthy sources to be considered.
