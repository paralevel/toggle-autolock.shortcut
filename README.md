# Toggle Auto-Lock (shortcut)

[__Install latest version__](https://github.com/paralevel/toggle-autolock.shortcut/releases)
\
\
Shortcut for the control center on iOS that first takes you to the display auto-lock settings page, then when you have chosen a setting, the shortcut renames itself to reflect the new auto-lock status, and afterwards you are returned to where you launched the shortcut from (either the previous app or the home screen)

When adding it to the control center, make sure not to shrink it from widget size to icon size, or you won't be able see the current auto-lock status
<br><br>
Limitations
<br>
<ul>
  <li>If you launch the shortcut from anywhere else than the control center, or modify the auto-lock settings without going through the shortcut, the control center widget name won't be updated to reflect the new status – it will be corrected immediately the next time you launch the shortcut, though</li>
  <br>
  <li>The shortcut will stop working if you rename it to something else (unless you also edit all the name-related actions in the shortcut)</li>
  <br>
  <li>If you try to test run the shortcut from inside the iPhone Mirroring app on macOS, you won't be returned to the previous app since the Get Current App action currently doesn't work there</li>
</ul>
