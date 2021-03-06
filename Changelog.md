# SiXROM Changelog
<center><img src="https://lh3.googleusercontent.com/-eDjTo5PZfGE/AAAAAAAAAAI/AAAAAAAAABw/HAUDdfWoxHc/w360-h203-p-rw/photo.jpg" height="60%" width="60%;"/></center>

### NOTE: This is my personal rom for the Nexus 6, and will update it on my free time.
### SiXROM is made for me, with just what i find to be usefull...NO FEATURE REQUESTS.
### Thank You and Enjoy!!!

### CHANGES v2.6 INTERNAL
- Shamu: Upstream Kernel to 108
- Shamu: Change kernel for BL4CKB1RD-v4.0

### CHANGES v2.5 INTERNAL
- Add Busybox
- Add Battery Bar
- Add Poor man battery style tweaks
- Stop showing Heads-Up notifications when selected applications is on top
- Fix Lockscreen crash on devices without FP
- Fix NPE when AOSP ambient display preference is removed
- Fix SysUI fc on rotation
- Fix Wrong actionbar title sticking around after exit
- Fix Battery tile to show charging state
- Fix Time does not change after rotating device
- Fix Wrong switch state set in DevelopmentSettings
- Fix Wi-Fi list adds same AP repeatedly
- Fix PrivateVolumeSettings being launched repeatedly
- Fix Hide Substratum package filter
- Fix Refresh payment preference while resume
- Fix Navbar media arrows code
- Fix Navbar keyboard cursors
- Fix Security settings FC
- Fix Category with no titles in settings
- Fix Settings force close in monkey test
- Hide the "show/hide overlays" when no overlay installed
- Use separate icon for flashlight power usage
- Set title for empty category in lang and input
- Launcher3: Cleanup PredictiveApps implementation
- Launcher3: Top widget toggle fixes and improvements
- Launcher3: Allow to put shortcuts in the top area if top widget is removed
- Launcher3: Go straight to home when exiting from launcher settings
- Launcher3: Hide apps menu: save on app check/uncheck
- Launcher3: Suppress a IllegalStateException crash
- Launcher3: Materialize icons
- Launcher3: Widget resizing
- Launcher3: Fix top widget hide
- Launcher3: Checks for available OmniJaws
- Launcher3: Short press on empy weather should refresh
- Launcher3: Integrate Hidden apps option into Settings
- Launcher3: Add config to place search bar above or below hotseat
- Launcher3: Add config to show current day in top widget
- Launcher3: Add display period config for events
- Launcher3: Add bottom search bar
- Update Substratum to v912
- Misc Clean up

### CHANGES v2.4
- Update to 8.0.0 r31 (OPR5.170623.011)
- MISC CLEAN UP
- EVERYTHING IS WORKING
- FINAL BUILD OF SIXROM OREO AND NOUGAT
- NOTE: DEVELOPMENT WILL BE DEAD AFTER NEW YEARS
- IM MOVING ON FROM ANDROID SINCE IS NOT A FUN HOBBY ANYMORE
- THANK YOU EVERYONE THAT HAS SUPPORTED MY STUFF THRU THE YEARS
- HAPPY HOLIDAYS AND STAY SAFE...
- OH AND TO ALL MY HATERS, WELL YA KNOW....FUCK YOU!!!

### CHANGES v2.3
- Fix Security pin crashing settings
- Remove Display network name in statusbar
- Remove show version information without tap

### CHANGES v2.2
- Add '24 hours' as an option for snoozing notifications
- Add Display network name in status bar
- Add Roboto Condensed Medium to fonts.xml
- QS: Avoid expand indicators shortly showing on edit
- Fix NPE with LightBarController dump
- Vectorized the power menu sound panel selector
- Switch to Pixel2XL 8.1 sounds
- NfcTile: use Oreo style
- Show full/proc/version information
- Shamu: Move 'no srgb settings' overlay from SettingsProvider to Settings
- Shamu: Add hw-binder-aware gatekeeper HAL
- Shamu: Remove ShamuLayout
- Shamu: Revove factory image and self-extractor support
- Shamu: Remove HW encryption leftovers
- Shamu: Set Pixel theme as default
- Shamu: Changes to sixkernel

### CHANGES v2.1
- Add support for overriding default time format value
- Add Unlimited Google HD Photos
- Reduce hwui CPU time by using glDrawRangeElements
- Smoother system bars color transition
- Halt notification ticker when entering Ambient display
- Fix FC on Notification ticker
- Tweaks for faster animation
- Enable all available quick settings tiles in Settings
- Remove gap between QS bottom and notification top
- Remove demo mode / quick settings option
- Remove setting option for Wallpaper
- Change encryption preference's summary accordingly
- Update CalendarGooglePrebuilt
- Remove WallpaperPickerGooglePrebuilt

### CHANGES v2.0
- Add Status bar notification ticker
- Add Increasing ring feature
- Add Dialer Lookup
- Add OmniSwitch activity
- Upstream sixkernel to 3.10.107
- Changes to sixkernel v2.0
- Fix NFC
- Fix empty recents view in multi window mode
- Changes to Power menu settings
- Misc cleanup

### CHANGES v1.9
- Add Power menu animations
- Add Rotation anim to power and reboot menus
- Add Powermenu Torch option
- Add Power menu customizations
- Show full alarm info
- Move Gestures to their own menu under System settings
- Remove extra preference for Auto Brightness
- Break out status bar icon from extdesk icon
- Remove extra cell broadcast settings
- Remove setting for screen timeout under 'Battery'
- Disable 'model & hardware' dialog
- Kill log spam in InstalledAppDetails
- Center empty textview for BT
- Fix crash while entering in DevelopmentSettings
- Fix memory leak when used WifiManager
- Fix Title being different after tapping "Memory used by apps"
- Fix Settings crash when setting only decimal point to data usage warning
- Fix PremiumSmsAccess memory leak
- Fix memory leak in Bluetooth settings
- Fix Black screen appears after tapping the back key
- Fix wrong label for Desktop backup password
- Fix a crash in ChooseLockGenericFragment
- Fix BT stop searching after rotating screen
- NFC: Reset Tap&pay summary text if default payment is not set

### CHANGES v1.8
- Add OmniSwitch recents/launcher
- Add MicroG support for signature spoofing
- Add Haptic Feedback to tiles
- Add three-fingers-swipe to screenshot
- Add Power notifications tuner activity
- Add membar to recents options
- Add Force Expanded Notifications
- Add READ_PHONE_STATE to manifest
- Add clearPrivateFlags for WindowManager
- Add Missing Back buttons in CB settings
- Fix Ambient Wake while screen-off bug 
- Fix Netflix playback DRM issue
- Fix weeknight and weekend days arrays
- Fix NPE with void VelocityTracker
- Recents: Allow closing empty view via tapping
- Remove duplicate permissions
- SettingsProvider: Update icon
- Bluetooth: Change disconnected icon to be 40% transparent
- DocumentsUI: Change launcher icon to a nicer image 
- Increase available volume levels
- Volumes in dialog same order as in settings
- Shamu: Update blobs to N6F27M
- Shamu: Update bluetooth config
- Enable ro.opa.eligible_device in vendor six

### CHANGES v1.7
- Update to 8.0.0 r17
- Force disable OTA and enable Dev settings for some Google apps
- Notification lights: use default resources for color on and off
- Audioservice: Set BT_SCO status
- Lockscreen bottom shortcuts fixes
- SystemUI: thread protect keyguard callbacks
- Recents: allow single tap on app icon to show app info overlay
- Fully enable system round icons
- Statusbar UserHandle cleanup
- SystemUI: add volume tones and toggle back
- NFC adapter is always available when needed (placeholder)
- Show NFC tile (placeholder)
- Add a hide config to left and right shortcut
- Remove NFC for now
- Disable Always ON Ambient feature (useless)
- Telephony: Add backwards compatibility with pre-oreo blobs
- Fix non-protected broadcast from supersu, qcril and fm
- Fix AddAccountSettings memory leak
- Changes to SiXKernel
- Use correct icon for sim card
- Move Gestures options to their own menu under System settings
- Partially revert Remove the Automatic ota check
- Shamu: Add HotworkEnrollment.apk (testing)
- Shamu: update sound trigger to support hotsound
- Shamu: Update sound trigger configuration
- Shamu: Add sound_trigger mixer info and path
- Shamu: Add listen platform information file
- Shamu: Add the missing permission for google now listening everywhere
- Angler: Increase MAX_FAILED_ATTEMPTS
- Av: Don't override possible overlayed header
- Av: stagefright: omx: Don't signal dataspace change on legacy QCOM
- Av: Allow devices to load custom CameraParameter code
- Av: audiopolicy: make audio policy extensible
- Audio: Use tinycompress with kernel headers
- Audio: Use kernel headers
- Audio: Use project pathmap

### CHANGES v1.6
- Revert Bluetooth wake fix ( causing reboots )
- Add IME selector notification toggle
- Add Immersive Recents
- Add Longpress back to kill app
- Add AppOps to security preference
- Add Force burn in for navbar
- Allow run services without selinux domain
- Disable statusbar time refresh when screen off
- Misc changes

### CHANGES v1.5
- Dont use persist.sys.disable_rescue (might be causing a reboot issue)
- Add API to get IMS Registration Status based on subId
- Fix MobileNetworkSettings crash for multi-SIM device
- Show proper call duration
- Enable App Ops
- Rework AppOpsDetails to new AppHeaderController
- Check AppOps permissions safely
- Fix for google backup and restore
- BluetoothAdapter: disable logspew
- Messaging: Show snackbar instead of toast when deleting conversation
- Messaging Fix App crashing when storage memory is full
- Messaging: Swipe right to delete conversation
- Shamu: Move soundfx to vendor

### CHANGES v1.4
- Fix Bluetooth Doze while screen off
- Fix Notification lights blinking/pulse
- Fix AddAccountSettings memory leak
- Fix crash issue when multi-window on WifiCallingSettings
- Fix Default apps settings disappear when switching to secondary user
- Fix NPE crash in UsageAccessDetails
- Themes: Build ThemerInterfacer
- Themes: StrictMode and files under /data/system/theme/
- Themes: Hold "volume up" during boot to disable all overlays
- Themes: Force authorize all calling packages by Masquerade
- Themes: Add protected broadcast for app crash broadcast
- Themes: Introduce App Crash Intent
- Themes: Show/hide Substratum overlays
- Themes: Allow system effect sounds to be themed
- Themes: Add dynamic theme ShutdownAnimation support
- Themes: Add dynamic theme BootAnimation support
- SEPolicy: Allow interfacer to find content_service
- SEPolicy: Add policy to fix interfacer derp on boot
- SEPolicy: Allow system_server to set theme_prop
- SEPolicy: add file and domain trans to interfacer
- SEPolicy: Add Theme interfacer
- SEPolicy: Redo interfacer rules
- SEPolicy: Fix application of bootanimation
- SEPolicy: Allow interfacer to read and write theme assets
- SEPolicy: Rename interfacer domain and allow JobService in system_server
- SEPolicy: Initial policy edits for interfacer to operate rootless
- SEPolicy: Fix themed sounds
- SEPolicy: Fix themed boot animation
- SEPolicy: Introduce sepolicy exceptions for theme assets
- Framework: fix screenshot and rotation animation
- Framework: Enable power save config of system apps
- Add option to hide the navigation bar
- Add NavBar tile
- Add Vibrate on plug
- Add Zen option to refresh switch state on disabled/enabled
- Add Messaging app to managed provisioning
- Update headphones statusbar icon
- Update Substratum to v852
- Remove some device themes ( get from six center )
- Less annoying heads up code fixes and improvements
- Camera: Add feature extensions
- Camera: Don't throw exceptions when value pairs have spaces
- Audio: Add support for extended formats
- Activity: Add an helper to get its handler instance
- NetworkTraffic: Add paddings
- Increase Zenmode max hour limit from 12 to 24
- Optimised hwui rounded corners shader
- Reintroduce button-backlight (and respective inactivity timeout)
- InputMethodService: Disable fullscreen keyboard
- Misc fixes and cleanup

### CHANGES v1.3
- Update to 8.0.0 r12
- Add option to disable scrolling cache
- Add XuiMod Toast Animations
- Add AOKP custom system animations
- Add Notification light during DND option
- Add Wi-Fi Auto-connect support
- Add Unlink notification volume
- Add CPU info overlay
- Add Expanded Desktop QS Tile
- Add Sync QS Tile
- Add AlwaysOnDisplay switch to display settings
- Enable Round App Icons
- Enable Three icon switching within QS DND tile
- Change Recents fab icon
- Fix race condition when writing UidState of appops
- Reporting FULL_WAKE_LOCK to battery stats
- Avoid race condition during grayscale animation of QS tile
- PiP tile launch settings when long-press
- Show correct status when Auto-connect is off
- Enable Dessert Cake dream
- Misc fixes

### CHANGES v1.2
- Fix Hotspot tethering
- Add quickly open Running Services from QS panel
- Add Support recents task locking
- Add Option to disable auto brightness icon in slider
- Add Auto brightness toggle to Quick Settings
- Add customize notification led light
- Add Kill any app from recents panel in a safe way
- Use LineageOS implementation of liblights
- Misc changes to SiX Settings
- QS auto brightness toggle rework
- Speed up Recents show additional button delay
- Change power save mode color to sexy red

### CHANGES v1.1
- Update to 8.0.0 r11 OPR6.170623.017
- Add Show volume panel tile to QS
- Add Sound tile to Quick Settings
- Add PiP tile
- Add Ambient-LiftToWake tile
- Add Partial/full screenshot QS tile
- Add Caffeine qs tile
- Add Hide power menu on secure lockscreen
- Add Lockscreen quick unlock
- Add Lockscreen Charging info
- Add Launch Expanded Desktop to SiXSettings
- Add Dialer auto proximity speakerphone
- Add Make ringtone audio focus customizable
- Ask for pin when tapping Data/airplane tiles on secure lockscreen
- Add QS titles for tiles visibility
- Add Status network traffic
- Add Wake on plug
- Add WakelockBlocker
- Change hyperlinks
- Move device themes fragment higher
- Enable notifications led light by default

### CHANGES v1.0
- Fixed Bluetooth
- Fix KernelWakelockReader stop the panic
- Fix ParcelFileDescriptor stop the panic
- Fix Forceclose when entering navbar options
- Fix Forceclose when entering recents options
- Add Alarms blocker
- Add Recents Clear All Button
- Add Expanded Desktop
- Add font size in 5% steps from 80% to 130%
- Add Double tap to sleep on statusbar
- Add Prebuilt Google wallpaper picker
- Add Adb over Network and QS tile
- Add Less intrusive heads up option
- Add Lockscreen quick unlock
- Add Scramble pin layout when unlocking
- Add Local changelog to about phone
- Remove double Font & Display size settings
- Remove Dashboard suggestions and conditions
- Enable battery percentage in statusbar by default
- Update default material popup animations
- Move SystemUI Tuner to SiX Settings
- Updated Gapps
- Build all Theme Overlays
- *Orange 
- *Indigo
- *Amber
- *Purple
- *Pink
- *Green

### BUGS

### ROM FEATURES
- Revision 8.0.0 r4 (OPR6.170623)
- ROM Logo in About Phone
- SuperSU or Magisk
- No Forced Encryption ( Kernel )
- Disable Tether checks
- Oreo six bootanimation
- Pixel stock navigation bar icons
- Pixel system colors
- Pixel stock sounds
- AOSP Messaging
- AOSP Camera
- Eleven Music
- Show link to Google Play
- Gesture settings
- Allow sorting applications by size
- Improve app info screen
- SiXSettings dashboard
- Correctly align cursor
- Quick settings pull down with one finger
- Double tap to sleep on lockscreen
- Remove unused drawables
- Disable automatic update
- Remove unnecessary videos
- Option to use volume keys to control media volume anytime
- Allow to swap volume buttons rotation based
- Navbar double tap to sleep
- Advanced Power Menu
- NightLight lower temperatures
- Enable SysUI tuner by default
- Disable qs footer warnings 
- Toggle to change USB MTP/STORAGE default
- Toast icon switch
- Battery light customization
- Launch music player on headset/bt connect
- Doubletap or longpress power to toggle flashlight
- Allow to customize max SMS per minute limit
- Disable Lockscreen Media Art
- Volume rocker music control
- PhoneInfo in About Phone > status
- Additional Battery saver steps
- Set custom brightness for ambient display and liftToWwake
- Night Light brightness mode options
- Increase QS columns to 4
- Add/remove QS with one click
- Auto hiding IME cursors as left/right nav buttons
- Display bluetooth battery status when available
- Alarms  blocker
- Recents Clear All Button
- Expanded Desktop
- Font size in 5% steps from 80% to 130%
- Adb over Network and QS tile
- Less intrusive heads up option
- Lockscreen quick unlock
- Scramble pin layout when unlocking
- Local changelog in about phone
- Build prop tweaks
- Tons of fixes 
- AND MORE!!!


### CREDITS AND THANKS
- Beanstown106
- Daveyannihilation
- Vic Perriera
- Nobe1976
- Ezio84
- MikeyMopar
- REV3NTECH
- Dustin Rinne
- Randall Rushing
- Wrongway213
- Giovanni Bozzano
- Dwitherell
- David Hayes
- PureNexus Project
- BlackBird Kernel
- Team BlackOut
- Desolation
- ABC
- Omni
- Benzo
- UnholyDevs
- ScrewdAOSP
- OwnROM
- Google
