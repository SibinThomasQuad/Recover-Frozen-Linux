# Recover-Frozen-Linux

REISUB - the gentle Linux restart

According to Lifehacker a frozen Linux system that's not responding to the Ctrl-Alt-Delete three-finger-salute can be restarted more safely than by pushing the power button, which is usually the next step.

Holding down Alt and SysRq (which is the Print Screen key) while slowly typing REISUB will get you safely restarted. REISUO will do a shutdown rather than a restart.

Sounds like either an April Fools joke or some very strange magic akin to the old BIOS beeps we used to use to diagnose PC faults so bad that nothing would boot. Wikipedia comes to the rescue with an in-depth listing of all the SysRq keys.

    R: Switch the keyboard from raw mode to XLATE mode
    E: Send the SIGTERM signal to all processes except init
    I: Send the SIGKILL signal to all processes except init
    S: Sync all mounted filesystems
    U: Remount all mounted filesystems in read-only mode
    B: Immediately reboot the system, without unmounting partitions or syncing
