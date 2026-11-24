# Chipsy sunset

This repository is where a Chipsy shutdown notice would be published, if Chipsy ever closes.

Chipsy (https://chipsy.app) 0.4.0 and later look for `sunset.txt` here, on get.chipsy.app, and on
the license server, but only when a copy can't be used (its license can't be checked). A notice
is signed with Chipsy's offline sunset key. Every copy that sees one turns its license check off
for good, so it keeps working without any of Chipsy's servers.

There is no `sunset.txt` here, which means Chipsy is running normally.
