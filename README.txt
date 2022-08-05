# How to use Additional Languages for Craftopia

1. Subscribe to Craftopia Mod Loader (BepInEx)
2. Subscribe to this mod (probably you have already finished this step!)
3. Launch Craftopia once and quit.
4. Overwrite steamapps\workshop\content\1307550\2519948110\BepInEx\config\budgiemods_additionallangs.cfg:

    language = None
to
    language = Spanish
,
    language = Russian
,
    language = French
,
    language = Korean
,
    language = German
,
    language = Portuguese
or
    language = Brazilian

Note that, "Portuguese" setting leads to pt-PT, so choose "Brazilian" if you want to play in pt-BR.

5. Launch Craftopia and enjoy!

# Caution

If you notice some display bugs or mistranlations, please tell them to the author through:
https://forms.gle/apomreMKTWA1Luxb7 (Google Forms)

Please do not try to contact PocketPair Inc. unless the bugs remain after removing this mod.

Please do not re-distribute this mod. If you recommend this to your friends, tell them to subscribe to this through Steam Workshop.

FAQ

Q. The config file does not appear

A. There might be a crash problem.
   - If you have installed any other mods and they crash, the Mod Loader stop loading and cannot reach this mod.
   - If you have installed XUnity.AutoTranslator, this mod is not compatible with it.
   - If your Craftopia version and/or mod version is not appropriate, they can cause conflicts. This mod only supports stable version.
   To specify the problem, see C:\Users\(Account Name)\AppData\LocalLow\PocketPair\Craftopia\Player.log.
   The address is independent of Steam settings and always in Users.
   Note that AppData is hidden by default and you have to change settings or write the path on the address bar.
   After removing mods with problem or alpha setting, try to verify the integrity of your game files in Steam (see https://help.steampowered.com/ja/faqs/view/0C48-FCBD-DA71-93EB).
