Terminix stores it's configuration in dconf and you should be able to use the dconf tool to migrate settings. To dump the setting:

dconf dump /com/gexperts/Terminix/ > terminix.dconf
To load this file back into dconf on a different machine:

dconf load /com/gexperts/Terminix/ < terminix.dconf

