# SlimSaber 5.1.1 Bacon - WiFi drop out issue log

06-02 23:41:43.706 E/libsuspend(  828): Error writing to /sys/power/state: Device or resource busy
06-02 23:44:21.558 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:44:21.563 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:44:21.652 I/GCM     ( 1868): GCM message com.google.android.talk 0:1433285060872808%5a539273f9fd7ecd:dr:com.google.android.talk:dr:<email omitted>:dr:0:1433285060872808%5a539273f9fd7ecd
06-02 23:44:21.663 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:44:21.668 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:44:36.711 I/Babel   ( 6239): Account Redacted-25 is valid for babel:true
06-02 23:44:36.711 I/Babel   ( 6239): Account Redacted-25 matches participantId: true
06-02 23:44:36.711 I/Babel   ( 6239): RTCS will handle all server updates.
06-02 23:44:36.717 I/Babel   ( 6239): Creating RTCS
06-02 23:44:36.924 I/Babel   ( 6239): Destroying RTCS
06-02 23:44:54.120 W/wpa_supplicant( 5890): wlan0: WPA: EAPOL-Key Replay Counter did not increase - dropping packet
06-02 23:44:55.044 W/wpa_supplicant( 5890): wlan0: WPA: EAPOL-Key Replay Counter did not increase - dropping packet
06-02 23:44:55.970 W/wpa_supplicant( 5890): wlan0: WPA: EAPOL-Key Replay Counter did not increase - dropping packet
06-02 23:44:57.204 W/wpa_supplicant( 5890): wlan0: WPA: EAPOL-Key Replay Counter did not increase - dropping packet
06-02 23:45:10.493 V/BackupManagerService(  828): Running a backup pass
06-02 23:45:10.499 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:45:10.504 V/BackupManagerService(  828): clearing pending backups
06-02 23:45:10.531 D/Tethering(  828): InitialState.processMessage what=4
06-02 23:45:10.532 I/wpa_supplicant( 5890): wlan0: CTRL-EVENT-DISCONNECTED bssid=20:0c:c8:70:9d:b0 reason=6
06-02 23:45:10.534 E/WifiConfigStore(  828): saveWifiConfigBSSID Setting BSSID for "VM477994-5G"-WPA_PSK to any
06-02 23:45:10.534 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:45:10.536 D/Tethering(  828): sendTetherStateChangedBroadcast 0, 0, 0
06-02 23:45:10.555 D/CommandListener(  269): Clearing all IP addresses on wlan0
06-02 23:45:10.658 E/WifiStateMachine(  828): WifiStateMachine: Leaving Connected state
06-02 23:45:10.662 D/WifiNetworkAgent(  828): NetworkAgent: NetworkAgent channel lost
06-02 23:45:10.849 V/PerformBackupTask(  828): Beginning backup of 1 targets
06-02 23:45:10.856 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:45:10.872 D/LBSSystemMonitorService(  828): handleMessage what - 8
06-02 23:45:10.872 D/Wiper_jni(  828): Send Wifi Supplicant info
06-02 23:45:10.878 E/LocSvc_LBSApiV02(  828): E/virtual int lbs_core::LBSApiV02::wifiAttachmentStatusInject(const WifiSupplicantInfo&):653]: Error : st = 11, ind.status = -1226027020
06-02 23:45:10.889 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 120](  828): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
06-02 23:45:10.889 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 120](  828): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
06-02 23:45:10.889 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 120](  828): Disconnected - quitting
06-02 23:45:10.889 D/CSLegacyTypeTracker(  828): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 120] isDefaultNetwork=true
06-02 23:45:10.890 D/Tethering(  828): MasterInitialState.processMessage what=3
06-02 23:45:10.913 D/ConnectivityManager.CallbackHandler( 1312): CM callback handler got msg 524292
06-02 23:45:10.952 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:45:11.048 D/PhoneApp( 1712): mReceiver: ACTION_ANY_DATA_CONNECTION_STATE_CHANGED
06-02 23:45:11.048 D/PhoneApp( 1712): - state: DISCONNECTED
06-02 23:45:11.048 D/PhoneApp( 1712): - reason: dataEnabled
06-02 23:45:11.049 D/PhoneApp( 1712): mReceiver: ACTION_ANY_DATA_CONNECTION_STATE_CHANGED
06-02 23:45:11.049 D/PhoneApp( 1712): - state: DISCONNECTED
06-02 23:45:11.049 D/PhoneApp( 1712): - reason: dataEnabled
06-02 23:45:11.050 D/PhoneApp( 1712): mReceiver: ACTION_ANY_DATA_CONNECTION_STATE_CHANGED
06-02 23:45:11.050 D/PhoneApp( 1712): - state: DISCONNECTED
06-02 23:45:11.050 D/PhoneApp( 1712): - reason: dataEnabled
06-02 23:45:11.050 D/PhoneApp( 1712): mReceiver: ACTION_ANY_DATA_CONNECTION_STATE_CHANGED
06-02 23:45:11.050 D/PhoneApp( 1712): - state: DISCONNECTED
06-02 23:45:11.050 D/PhoneApp( 1712): - reason: dataEnabled
06-02 23:45:11.052 D/PhoneApp( 1712): mReceiver: ACTION_ANY_DATA_CONNECTION_STATE_CHANGED
06-02 23:45:11.052 D/PhoneApp( 1712): - state: DISCONNECTED
06-02 23:45:11.052 D/PhoneApp( 1712): - reason: dataEnabled
06-02 23:45:11.054 D/PhoneApp( 1712): mReceiver: ACTION_ANY_DATA_CONNECTION_STATE_CHANGED
06-02 23:45:11.054 D/PhoneApp( 1712): - state: DISCONNECTED
06-02 23:45:11.054 D/PhoneApp( 1712): - reason: dataEnabled
06-02 23:45:11.055 D/PhoneApp( 1712): mReceiver: ACTION_ANY_DATA_CONNECTION_STATE_CHANGED
06-02 23:45:11.055 D/PhoneApp( 1712): - state: DISCONNECTED
06-02 23:45:11.055 D/PhoneApp( 1712): - reason: dataEnabled
06-02 23:45:11.061 D/PhoneApp( 1712): mReceiver: ACTION_ANY_DATA_CONNECTION_STATE_CHANGED
06-02 23:45:11.061 D/PhoneApp( 1712): - state: DISCONNECTED
06-02 23:45:11.061 D/PhoneApp( 1712): - reason: dataEnabled
06-02 23:45:11.138 D/NetworkChangeNotifierAutoDetect(11815): Network connectivity changed, type is: 6
06-02 23:45:11.154 W/CursorWrapperInner(12624): Cursor finalized without prior close()
06-02 23:45:11.156 W/CursorWrapperInner(12624): Cursor finalized without prior close()
06-02 23:45:11.158 W/CursorWrapperInner(12624): Cursor finalized without prior close()
06-02 23:45:11.160 W/CursorWrapperInner(12624): Cursor finalized without prior close()
06-02 23:45:11.161 W/CursorWrapperInner(12624): Cursor finalized without prior close()
06-02 23:45:11.173 D/ConnectivityManager(20196): getMobileDataEnabled()+ subId=1
06-02 23:45:11.173 D/PhoneInterfaceManager( 1712): [PhoneIntfMgr] getDataEnabled: subId=1 phoneId=0
06-02 23:45:11.173 D/PhoneInterfaceManager( 1712): [PhoneIntfMgr] getDataEnabled: subId=1 retVal=false
06-02 23:45:11.175 D/ConnectivityManager(20196): getMobileDataEnabled()- subId=1 retVal=false
06-02 23:45:11.190 D/WeatherUpdateService(18596): Service started, but shouldn't update ... stopping
06-02 23:45:11.197 W/art     (  828): Long monitor contention event with owner method=boolean android.os.MessageQueue.enqueueMessage(android.os.Message, long) from MessageQueue.java:323 waiters=0 for 294ms
06-02 23:45:11.216 W/art     (  828): Long monitor contention event with owner method=void com.android.server.power.PowerManagerService.acquireWakeLockInternal(android.os.IBinder, int, java.lang.String, java.lang.String, android.os.WorkSource, java.lang.String, int, int) from PowerManagerService.java:825 waiters=1 for 237ms
06-02 23:45:11.219 D/Tethering(  828): MasterInitialState.processMessage what=3
06-02 23:45:11.232 I/iu.Environment(12624): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
06-02 23:45:11.530 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:45:11.530 D/ConnectivityManager(20196): getMobileDataEnabled()+ subId=1
06-02 23:45:11.531 D/PhoneInterfaceManager( 1712): [PhoneIntfMgr] getDataEnabled: subId=1 phoneId=0
06-02 23:45:11.532 D/PhoneInterfaceManager( 1712): [PhoneIntfMgr] getDataEnabled: subId=1 retVal=false
06-02 23:45:11.561 D/ConnectivityManager(20196): getMobileDataEnabled()- subId=1 retVal=false
06-02 23:45:11.583 I/Choreographer( 5701): Skipped 72 frames!  The application may be doing too much work on its main thread.
06-02 23:45:11.596 D/WifiService(  828): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@df60aba}
06-02 23:45:11.621 D/PerformBackupTask(  828): invokeAgentForBackup on @pm@
06-02 23:45:11.643 D/WeatherUpdateService(18596): Service started, but shouldn't update ... stopping
06-02 23:45:11.665 I/iu.Environment(12624): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
06-02 23:45:12.064 W/System.err( 8596): java.net.SocketException: setsockopt failed: ENODEV (No such device)
06-02 23:45:12.064 W/System.err( 8596): 	at libcore.io.IoBridge.setSocketOption(IoBridge.java:325)
06-02 23:45:12.064 W/System.err( 8596): 	at java.net.PlainDatagramSocketImpl.setOption(PlainDatagramSocketImpl.java:189)
06-02 23:45:12.064 W/System.err( 8596): 	at java.net.PlainDatagramSocketImpl.leave(PlainDatagramSocketImpl.java:141)
06-02 23:45:12.064 W/System.err( 8596): 	at java.net.MulticastSocket.leaveGroup(MulticastSocket.java:184)
06-02 23:45:12.064 W/System.err( 8596): 	at com.estrongs.android.pop.zeroconf.w.c(Unknown Source)
06-02 23:45:12.064 W/System.err( 8596): 	at com.estrongs.android.pop.zeroconf.w.b(Unknown Source)
06-02 23:45:12.064 W/System.err( 8596): 	at com.estrongs.android.pop.app.bh.run(Unknown Source)
06-02 23:45:12.064 W/System.err( 8596): 	at java.lang.Thread.run(Thread.java:818)
06-02 23:45:12.064 W/System.err( 8596): Caused by: android.system.ErrnoException: setsockopt failed: ENODEV (No such device)
06-02 23:45:12.064 W/System.err( 8596): 	at libcore.io.Posix.setsockoptGroupReq(Native Method)
06-02 23:45:12.064 W/System.err( 8596): 	at libcore.io.ForwardingOs.setsockoptGroupReq(ForwardingOs.java:144)
06-02 23:45:12.064 W/System.err( 8596): 	at libcore.io.IoBridge.setSocketOptionErrno(IoBridge.java:395)
06-02 23:45:12.064 W/System.err( 8596): 	at libcore.io.IoBridge.setSocketOption(IoBridge.java:323)
06-02 23:45:12.064 W/System.err( 8596): 	... 7 more
06-02 23:45:12.640 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:45:12.641 I/BackupRestoreController(  828): Getting widget state for user: 0
06-02 23:45:12.650 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:45:12.652 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:45:12.655 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:45:12.669 I/GmsBackupTransport( 1900): K/V backup for @pm@ aborted by rate limiter. next=1433328885405, current=1433285112668
06-02 23:45:12.669 D/PerformBackupTask(  828): starting agent for backup of BackupRequest{pkg=android}
06-02 23:45:12.671 D/BackupManagerService(  828): awaiting agent for ApplicationInfo{187b57ec android}
06-02 23:45:12.671 D/BackupManagerService(  828): agentConnected pkg=android agent=android.app.backup.BackupAgent$BackupServiceBinder@32ac5561
06-02 23:45:12.671 I/BackupManagerService(  828): got agent android.app.backup.BackupAgent$BackupServiceBinder@32ac5561
06-02 23:45:12.671 D/PerformBackupTask(  828): invokeAgentForBackup on android
06-02 23:45:12.676 D/BackupHelperDispatcher(  828): handling existing helper 'recents' android.app.backup.RecentsBackupHelper@3f6a1886
06-02 23:45:12.695 D/WifiService(  828): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@df60aba}
06-02 23:45:12.702 D/BackupHelperDispatcher(  828): handling existing helper 'wallpaper' android.app.backup.WallpaperBackupHelper@11497547
06-02 23:45:12.742 I/ActivityManager(  828): Killing 23501:system:ui/1000 (adj 15): empty #17
06-02 23:45:12.816 I/iu.UploadsManager(12624): num queued entries: 0
06-02 23:45:12.825 I/BackupRestoreController(  828): Getting widget state for user: 0
06-02 23:45:12.829 I/GmsBackupTransport( 1900): K/V backup for android aborted by rate limiter. next=1433383258508, current=1433285112829
06-02 23:45:12.830 I/BackupManagerService(  828): Backup pass finished.
06-02 23:45:12.858 I/iu.UploadsManager(12624): num updated entries: 0
06-02 23:45:12.893 I/iu.SyncManager(12624): NEXT; no task
06-02 23:45:16.260 I/ActivityManager(  828): Killing 24491:com.sharpregion.tapet/u0a89 (adj 15): empty #17
06-02 23:45:42.514 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:46:10.956 D/ConnectivityService(  828): Failed to find a new network - expiring NetTransition Wakelock
06-02 23:46:11.002 E/libsuspend(  828): Error writing to /sys/power/state: Device or resource busy
06-02 23:46:11.273 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:46:14.821 E/libsuspend(  828): Error writing to /sys/power/state: Device or resource busy
06-02 23:46:28.575 E/libsuspend(  828): Error writing to /sys/power/state: Device or resource busy
06-02 23:47:18.500 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:47:18.776 E/libsuspend(  828): Error writing to /sys/power/state: Device or resource busy
06-02 23:48:08.628 E/libsuspend(  828): Error writing to /sys/power/state: Device or resource busy
06-02 23:48:25.264 E/libsuspend(  828): Error writing to /sys/power/state: Device or resource busy
06-02 23:50:11.513 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:50:11.827 E/libsuspend(  828): Error writing to /sys/power/state: Device or resource busy
06-02 23:53:03.073 I/PowerManagerService(  828): Waking up from sleep (uid 1000)...
06-02 23:53:03.074 E/QCOM PowerHAL(  828): Failed to acquire lock.
06-02 23:53:03.074 I/QCOM PowerHAL(  828): Got set_interactive hint
06-02 23:53:03.097 I/DisplayPowerController(  828): Blocking screen on until initial contents have been drawn.
06-02 23:53:03.102 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:03.108 E/WifiStateMachine(  828): cancelDelayedScan -> 764
06-02 23:53:03.127 D/SurfaceFlinger(  262): Set power mode=2, type=0 flinger=0xb6482000
06-02 23:53:03.127 D/qdhwcomposer(  262): hwc_setPowerMode: Setting mode 2 on display: 0
06-02 23:53:03.133 I/DisplayManagerService(  828): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 63.0 fps, supportedRefreshRates [63.0], density 480, 403.411 x 403.041 dpi, appVsyncOff 7500000, presDeadline 11873016, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
06-02 23:53:03.225 D/LightsService(  828): Excessive delay setting light: 116ms
06-02 23:53:03.255 V/ActivityManager(  828): Display changed displayId=0
06-02 23:53:03.261 D/audio_hw_primary(  273): adev_set_parameters: enter: screen_state=on
06-02 23:53:03.412 I/Choreographer( 5701): Skipped 32 frames!  The application may be doing too much work on its main thread.
06-02 23:53:03.466 I/qdhwcomposer(  262): handle_blank_event: dpy:0 panel power state: 1
06-02 23:53:03.469 D/qdhwcomposer(  262): hwc_setPowerMode: Done setting mode 2 on display 0
06-02 23:53:03.469 D/SurfaceControl(  828): Excessive delay in setPowerMode(): 343ms
06-02 23:53:03.495 I/DisplayPowerController(  828): Unblocked screen on after 398 ms
06-02 23:53:03.526 W/art     (  828): Long monitor contention event with owner method=void com.android.server.am.BroadcastQueue.processNextBroadcast(boolean) from BroadcastQueue.java:548 waiters=1 for 140ms
06-02 23:53:03.546 D/Ulp_jni (  828): JNI:system_update. Event-0
06-02 23:53:03.573 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:03.575 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:03.588 D/ScreenOnOffReceiver( 1900): Received intent: Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }.
06-02 23:53:03.608 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:03.608 D/WifiService(  828): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@df60aba}
06-02 23:53:05.627 E/WifiStateMachine(  828): WifiStateMachine shouldSwitchNetwork  txSuccessRate=13799.50 rxSuccessRate=22083.88 delta 1000 -> 1
06-02 23:53:05.628 E/WifiStateMachine(  828): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
06-02 23:53:05.628 E/WifiStateMachine(  828): CMD_AUTO_CONNECT will save config -> "VM477994-5G" nid=0
06-02 23:53:05.628 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.628 D/LBSSystemMonitorService(  828): handleMessage what - 4
06-02 23:53:05.628 D/Wiper_jni(  828): Send Network Location.
06-02 23:53:05.638 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:05.640 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:05.645 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:05.646 E/WifiConfigStore(  828): Setting BSSID for "VM477994-5G"-WPA_PSK to any
06-02 23:53:05.646 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.646 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.646 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.647 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.647 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:05.647 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.647 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.648 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.648 E/WifiConfigStore(  828): will read network variables netId=0
06-02 23:53:05.649 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:05.649 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:05.653 E/WifiStateMachine(  828): CMD_AUTO_CONNECT did save config ->  nid=0
06-02 23:53:05.653 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.653 E/WifiConfigStore(  828): will read network variables netId=0
06-02 23:53:05.654 D/LBSSystemMonitorService(  828): handleMessage what - 7
06-02 23:53:05.654 D/Wiper_jni(  828): Send Passive Location.
06-02 23:53:05.658 I/wpa_supplicant( 5890): wlan0: Trying to associate with SSID 'VM477994-5G'
06-02 23:53:05.664 D/WifiService(  828): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@df60aba}
06-02 23:53:05.714 D/Coffee - GoogleTrustAgent( 1900): onUnlockAttempt true
06-02 23:53:05.714 I/TrustAgentApi - GoogleTrustAgentServiceImpl( 1900): GoogleTrustAgent received onUnlockAttempt.
06-02 23:53:05.750 D/Tethering(  828): sendTetherStateChangedBroadcast 1, 0, 0
06-02 23:53:05.751 I/wpa_supplicant( 5890): wlan0: Associated with 20:0c:c8:70:9d:b0
06-02 23:53:05.762 I/wpa_supplicant( 5890): wlan0: WPA: Key negotiation completed with 20:0c:c8:70:9d:b0 [PTK=CCMP GTK=TKIP]
06-02 23:53:05.762 I/wpa_supplicant( 5890): wlan0: CTRL-EVENT-CONNECTED - Connection to 20:0c:c8:70:9d:b0 completed [id=0 id_str=]
06-02 23:53:05.766 E/WifiConfigStore(  828): saveWifiConfigBSSID Setting BSSID for "VM477994-5G"-WPA_PSK to any
06-02 23:53:05.766 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.767 E/WifiConfigStore(  828): saveWifiConfigBSSID Setting BSSID for "VM477994-5G"-WPA_PSK to any
06-02 23:53:05.767 E/wifi_gbk2utf(  828): g_pItemList is NULL
06-02 23:53:05.771 D/CommandListener(  269): Setting iface cfg
06-02 23:53:05.771 E/WifiStateMachine(  828): Start Dhcp Watchdog 30
06-02 23:53:05.780 E/wpa_supplicant( 5890): wpa_driver_nl80211_driver_cmd: failed to issue private commands
06-02 23:53:05.781 E/WifiStateMachine(  828): Unexpected BatchedScanResults :null
06-02 23:53:05.781 E/wpa_supplicant( 5890): wpa_driver_nl80211_driver_cmd: failed to issue private commands
06-02 23:53:05.782 D/LBSSystemMonitorService(  828): handleMessage what - 8
06-02 23:53:05.782 D/Wiper_jni(  828): Send Wifi Supplicant info
06-02 23:53:05.786 E/LocSvc_LBSApiV02(  828): E/virtual int lbs_core::LBSApiV02::wifiAttachmentStatusInject(const WifiSupplicantInfo&):653]: Error : st = 11, ind.status = -1226027020
06-02 23:53:05.924 D/BluetoothAdapter( 1312): 1058078824: getState() :  mService = null. Returning STATE_OFF
06-02 23:53:05.924 D/BluetoothAdapter( 1312): 1058078824: getState() :  mService = null. Returning STATE_OFF
06-02 23:53:05.963 D/ScreenOnOffReceiver( 1900): Received intent: Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 }.
06-02 23:53:05.963 I/Coffee - PlaceTrustlet( 1900): User Present broadcast receiver action: android.intent.action.USER_PRESENT
06-02 23:53:05.963 I/Coffee - PlaceTrustlet( 1900): ready to fetch home
06-02 23:53:05.988 I/dhcpcd  (25296): version 5.5.6 starting
06-02 23:53:05.989 V/UserPresentBroadcastReceiver( 1900): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
06-02 23:53:05.993 W/ActivityManager(  828): Unable to start service Intent { act=com.google.android.gms.playlog.service.START pkg=com.google.android.gms } U=0: not found
06-02 23:53:05.994 W/ActivityManager(  828): Unbind failed: could not find connection for android.os.BinderProxy@53acf3b
06-02 23:53:05.994 E/GmsClient( 1900): unable to connect to service: com.google.android.gms.playlog.service.START
06-02 23:53:05.995 W/OneTimePlayLogger( 1900): logger connection failed
06-02 23:53:06.011 E/c       ( 5830): Send request failed
06-02 23:53:06.021 W/InputMethodManagerService(  828): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@27d06658 attribute=android.view.inputmethod.EditorInfo@32fa93b1, token = android.os.BinderProxy@8873748
06-02 23:53:06.024 I/dhcpcd  (25296): wlan0: rebinding lease of 192.168.0.5
06-02 23:53:06.047 I/Timeline( 5194): Timeline: Activity_idle id: android.os.BinderProxy@2d91f4b1 time:25873868
06-02 23:53:06.080 I/dhcpcd  (25296): wlan0: acknowledged 192.168.0.5 from 192.168.0.1
06-02 23:53:06.099 I/dhcpcd  (25296): wlan0: leased 192.168.0.5 for 86400 seconds
06-02 23:53:06.411 E/WifiStateMachine(  828): Did not find remoteAddress {192.168.0.1} in /proc/net/arp
06-02 23:53:06.431 E/ConnectivityService(  828): Unexpected mtu value: 0, wlan0
06-02 23:53:06.446 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 121](  828): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-02 23:53:06.446 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 121](  828): Connected
06-02 23:53:06.446 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 121](  828): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-02 23:53:06.446 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 121](  828): Checking <web url omitted> on "VM477994-5G"
06-02 23:53:06.449 D/CSLegacyTypeTracker(  828): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 121] isDefaultNetwork=true
06-02 23:53:06.449 D/ConnectivityManager.CallbackHandler( 1312): CM callback handler got msg 524290
06-02 23:53:06.451 D/Tethering(  828): MasterInitialState.processMessage what=3
06-02 23:53:06.478 D/NetworkChangeNotifierAutoDetect(11815): Network connectivity changed, type is: 2
06-02 23:53:06.483 D/ConnectivityManager(20196): getMobileDataEnabled()+ subId=1
06-02 23:53:06.484 D/PhoneInterfaceManager( 1712): [PhoneIntfMgr] getDataEnabled: subId=1 phoneId=0
06-02 23:53:06.484 D/PhoneInterfaceManager( 1712): [PhoneIntfMgr] getDataEnabled: subId=1 retVal=false
06-02 23:53:06.484 D/ConnectivityManager(20196): getMobileDataEnabled()- subId=1 retVal=false
06-02 23:53:06.498 D/WeatherUpdateService(18596): Service started, but shouldn't update ... stopping
06-02 23:53:06.512 I/iu.Environment(12624): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
06-02 23:53:06.512 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.532 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 121](  828): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Jun 2015 22:53:06 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1433285586532], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1433285586513]}
06-02 23:53:06.532 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 121](  828): Don't send network conditions - lacking user consent.
06-02 23:53:06.532 D/NetworkMonitor/NetworkAgentInfo [WIFI () - 121](  828): Validated
06-02 23:53:06.533 D/ConnectivityManager.CallbackHandler( 1312): CM callback handler got msg 524290
06-02 23:53:06.584 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.587 I/iu.UploadsManager(12624): num queued entries: 0
06-02 23:53:06.598 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.606 I/iu.UploadsManager(12624): num updated entries: 0
06-02 23:53:06.608 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.614 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.622 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.627 I/iu.SyncManager(12624): NEXT; no task
06-02 23:53:06.716 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.717 D/GCM     ( 1868): Connected
06-02 23:53:06.741 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.772 D/GCM     ( 1868): Message class com.google.f.a.a.p
06-02 23:53:06.781 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.783 D/ConnectivityManager.CallbackHandler( 1312): CM callback handler got msg 524295
06-02 23:53:06.783 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.793 I/GCM     ( 1868): GCM message com.whatsapp 0:1433285235216803%a3bffb5f00000031
06-02 23:53:06.801 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:06.804 D/PowerManagerService(  828): acquireWakeLock: ignoring request from com.google.android.gms
06-02 23:53:11.490 W/TRThreadPoolExecutor(11815): Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
06-02 23:53:11.714 D/QcrilMsgTunnelSocket( 3016): readRilMessage: Buffer = [B@260b1b7 HexData = [010000000404000011000000514f454d484f4f4bef0308000100000003]
06-02 23:53:11.714 D/QcrilMsgTunnelSocket( 3016): Rcvd UNSOL response with 28 bytes data for SUB0
06-02 23:53:11.714 D/QcrilMsgTunnelSocket( 3016): Response ID 525295 is not served in this process.
06-02 23:53:11.714 D/QcrilMsgTunnelSocket( 3016): To broadcast an Intent via the notifier to external apps
06-02 23:53:11.715 D/QcrilMsgTunnelIfaceManager( 3016): handleMessage what = 0
06-02 23:53:11.715 D/QcrilMsgTunnelIfaceManager( 3016): Broadcasting intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
06-02 23:53:13.310 E/WifiStateMachine(  828): WifiStateMachine L2Connected CMD_START_SCAN source -2 766, 767 -> obsolete
06-02 23:53:21.581 I/ActivityManager(  828): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10200000 cmp=com.teslacoilsw.launcher/.NovaLauncher} from uid 1000 on display 0
06-02 23:53:21.582 E/QCOM PowerHAL(  828): Failed to acquire lock.
06-02 23:53:21.646 W/IInputConnectionWrapper( 5194): showStatusIcon on inactive InputConnection
06-02 23:53:21.666 I/Timeline( 1747): Timeline: Activity_idle id: android.os.BinderProxy@a38c098 time:25889487
