# filipfogel.github.io

This repo is the root of https://filipfogel.github.io/.

It holds `app-ads.txt`, which AdMob reads to verify the Android app
[Twinkle Twist](https://filipfogel.github.io/twinkle-twist/). Ad networks only look for that file
at the root of the domain, so it cannot live in the game's own repo, which is served under
`/twinkle-twist/`.

To add another ad network, add its line to `app-ads.txt`. Do not rename or move the file.
