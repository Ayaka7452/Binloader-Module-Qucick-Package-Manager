# Intro
an android package manager with quickly freezing / unfreezing ability
# Usage
 QPM - Android Quick Package Manager<br>
 Usage: qpm [operation] [parameter1] [...2]<br>
 Parameter defines:<br>
    spn - short package name is specified by user, it related to a full package name.<br>
    rpn - real package name of a android package, such as com.android.phone.<br>
    pgn - package group name is specified by user, it contains a bunch of spns.<br>
 Operations:<br>
    auto [spn] - Set specified package to opposed state.<br>
    ag [pgn] - Set specified group to opposed state.<br>
    ena [spn] - Set package state as enable.<br>
    disa [spn] - Set package state as disable.<br>
    addgrp [pgn] - Add a new package group using specified name.<br>
    addcfg [pgn] [spn] [fpn] - Add a package into exist group.<br>
    rmcfg [pgn] [spn] - Remove a package config in group.<br>
    rmgrp [pgn] - Remove a group and its contents.<br>
    lsgrp - List all groups.<br>
    dg [pgn] - Disable the whole package group.<br>
    eg [pgn] - Enable the whole package group.<br>
    catcfg [pgn] [spn] - display full package name of a config.<br>
    rngrp [old_pgn] [new_pgn] - Rename a package group.<br>
    rncfg [pgn] [old_spn] [new_spn] - Rename a short package config.<br>
    lscfg [pgn] - List configs in group.<br>
 
