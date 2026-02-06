# playing.uz
Game Server


# started with
cd ~/cs2server
./game/bin/linuxsteamrt64/cs2 -dedicated -console -tickrate 128 \
+map de_inferno +game_mode 1 +game_type 0 +maxplayers 10 \
+sv_setsteamaccount YOUR_GSLT_TOKEN -port 27020 -clientport 27005


-port range: 27015–27050
-clientport range: 27005–27030