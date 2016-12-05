# EclipseStyleKeyBindings
Eclipse Style KeyBindings For Xcode

Step 1:
> Edit `/Applications/Xcode.app/Contents/Frameworks/IDEKit.framework/Versions/A/Resources/IDETextKeyBindingSet.plist`,
add this code:
```
<key>Customized</key>
<dict>
    <key>Delete Current Line In One Hit</key>
    <string>selectLine:, delete:</string>
</dict>
```
above last`</dict>`tag.

Step 2:
> Copy `EclipseStyle.idekeybindings` to `~/Library/Developer/Xcode/UserData/KeyBindings/`.

Step 3:
> Open Xcode, `Preferences...`-`Key Bndings`-Secect `EclipseStyle`, then restart Xcode.
