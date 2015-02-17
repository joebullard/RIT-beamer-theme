Author: Joe Bullard

#Description

This repo contains an RIT color scheme for Beamer which can be used with any
theme, as well as an actual stand-alone theme based on the standard PaltoAlto
theme that comes with Beamer. The latter includes a convenience command for
using the RIT tiger logo in this repo, as well as a command for making
bold/orange header text.

RIT logo image obtained freely from:

    https://www.rit.edu/upub/logos

under the following conditions:

    "The logos provided on this web site have been approved for use by RIT
    staff, faculty, and students or their agents for officially sanctioned
    purposes. Any third-party use of RIT logos must be with RIT's prior written
    consent. If you have questions regarding the proper usage of RIT logos or
    stock images, please download the RIT graphic standards and identity manual
    or contact Jeff Arbegast at 585-475-7940."

In other words, make sure you're usage complies with the above. I was using it
for my thesis defense and conference slides, which was fine.

#Usage

To use the color scheme with whatever theme you want, simply put
'beamercolorthemerit.sty' in your slide directory and add '\usecolortheme{rit}'
AFTER your '\usetheme' command in the preamble.

To use the PaltoAlto-based theme, simply place 'beamerthemeRIT.sty' in your
slide directory and put '\usetheme{RIT}' in your preamble.

NOTE: you do not need both files.

If you want to use the '\useritlogo' command in the theme, then you also need
to download the image, but note the info above about its usage.
