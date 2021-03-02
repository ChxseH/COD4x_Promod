# Promod for CoD4X
Basically what it says on the tin.

Notes:

**When you are ready to use this mod on a server, take your already compiled version and distribute that through FastDL, or any way you want. This is required.**

* I ship some weird defaults in `promod_ruleset/custom_public.gsc` which you should change before using this mod.

* There are ads in places, you *can* change them, but I'd appreciate if you left them;)
```
./promod_ruleset/custom_public.gsc: setDvar( "promod_hud_website", "chse.xyz/donate" ); // (avoid "//" here)
./ui_mp/main.menu: text "chse.xyz/donate"
```

* Recommended server.cfg settings:
```
set promod_mode "custom_public" // promod mode, for a list of promod modes see attached readme
set promod_enable_scorebot "0" // match-modes only
```

Compiling:

To compile this mod, simply place the `Mod_Files` contents into a new folder in your `Mods` folder, then run compile.bat. The compiled mod should spit out in `mods/promod_rc`.
