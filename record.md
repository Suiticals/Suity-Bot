# How to record transactions

Please note that syntaxes using `< >` indicate a required parameter. Input your details in the command without the use of `< >`.

## Getting Verified

In order to begin submitting transactions to the bot you must verify your RSN. `.pct verifyhelp` also shows this information.

To verify you must use `.pct verify <screenshot> <RSN>`

The verification screenshot must:

* Show the in-game chatbox with your Runescape screen-name clearly visible.
* Include a public chat message asking for verification and today's date.
* The RSN in the screenshot must match the one provided when applying.
* You may use a number of image hosts to upload your screenshot to including `gyazo` `imgur` or even `discord`

This is an example of an acceptable screenshot:

![image](https://user-images.githubusercontent.com/39773562/164458007-2133ebb9-d07c-492b-ac5f-b7f028923cea.png)

The example command for verification using this screenshot would be: `.pct verify https://i.imgur.com/XdspFz3.png suity`

Your verification will either be `approved` or `denied`. Once you are verified, you may submit trades to the bot. You may be denied for one or more of the following reasons:

* `The screenshot provided is invalid` - The screenshot you provided is inaccessible or is a broken link.
* `The RSN provided does not match the RSN in the screenshot`
* `There is no public chat message in-game requesting verification`
* `The verification message in public chat does not include the date the application was submitted`

## Submitting a trade

* `inb` - Instant bought. Once you confirm your Grand Exchange offer, if the item is immediately bought it is classed as instant.
* `ins` - Instant sold. Once you confirm your Grand Exchange offer, if the item is immediately sold it is classed instant.
* `nib` - Not instant bought. Once you confirm your Grand Exchange offer, if the item is not immediately bought it is classed as non-instant. Please take into consideration the possibility that [you may be on your buy limit](https://runescape.wiki/w/Grand_Exchange#Buying_limits).
* `nis` - Not instant sold. Once you confirm your Grand Exchange offer, if the item is not immediately sold it is classed as non-insant. Item sales are not subject to your buy limit.

## Issues and conflicts

If you have an issue with recording, command usage, verification or conflict with a recent transaction submitted to the bot, please use the `issues` channel to open a ticket in the [SuityBot support server](https://discord.gg/hTxdyhjUmG). Alternatively you may contact using `.contact <message>`

## Record stream


