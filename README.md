UUID Generator/Decoder
======================

Generate UUIDs (v1/v3/v4/v5) or decode UUIDs without online tools. [DevUtils.app](https://devutils.app) allows you to quickly generate UUIDs and decode UUID without any internet connection. It supports all four versions of UUIDs, batch generate, and more.

<p align="center">
  <img src="https://devutils.app/assets/uuid-generator-decoder-dark.png" alt="DevUtils.app: UUID Generator/Decoder macOS app"/>
  <br/>
  <a href="https://devutils.app/">🚀  Download</a> | <a href="https://devutils.app/demo">🎬  Demo & Screenshots</a> | <a href="https://github.com/DevUtilsApp/DevUtils-app">📝  View source</a>
</p>

Quickly decode a UUID
---------------------

You can encode a UUID from anywhere in your macOS (terminal, in email, web browser,...). DevUtils will inspect your clipboard content and automatically select the UUID Decoder tool if the content contains a valid UUID. Activate the app by:

* Copy text ► Press ⌃⌥⌘Space `(Or your own customized hotkey, up to you)`
* Copy text ► Click to icon <img src="https://devutils.app/menu-icon-dark.png" alt="DevUtils.app status bar icon" width="28px" /> in the status bar
* Select text ► Right-click ► "Inspect in DevUtils.app" `(This menu appears after you install the app)`

### Input

Enter your UUID in the input textbox. If you already have the string in your clipboard, just click the "Clipboard" button, and the tool will use the content in your clipboard as input.

### Output

The tool will decode the UUID into the following components:

*   Standard String Format
*   Raw Contents
*   Version
*   Variant
*   For time-based UUID
    *   Time
    *   Clock ID
    *   Node

### Options

When you activate the app, DevUtils will inspect your clipboard content and automatically select the UUID Generator/Decoder tool if the content is a valid UUID. You can disable this automatic feature by unticking the option in the setting panel (the gear icon).

![DevUtils.app: UUID Generator/Decoder macOS app](https://devutils.app/assets/settings/setting-uuid-generator.png)

Generate UUIDs
--------------

You can generate (and batch generate) UUIDs using the UUID Generator feature of the tool. First, select the version of the UUID you want to generate. Then enter the number of UUIDs you want to generate. Finally, click "Generate".

For v3/v5 UUIDs, you will also need to enter the Namespace and Name. Note that if you batch generate multiple v3/v5 UUIDs, all of the generated UUIDs are the same since there is no random component in the UUIDs.

![DevUtils.app: UUID Generator/Decoder macOS app](https://devutils.app/assets/settings/uuid-generate-v3.png)

You can optionally choose the generated UUIDs to be in uppercase or lowercase by ticking/unticking the "lowercased" checkbox.
