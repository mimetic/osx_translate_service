# osx_translate_service
An AppleScript service to translate the current selected text. 


Before you begin:

- You must fill in a working Google API key
- You can change the source and target languages in the AppleScript code

To Install:
- In Apple's OS X Automator app, create a new "Service".
- Add a "Run Applescript" entry
- The service will receive text from any application, and check "Output replaces selected text."
- Paste the AppleScript from this git into the AppleScript.
- Fill in your own Google API key.
- Save

See: https://cloud.google.com/translate/v2/translating-text-with-rest

Before running this sample, take the following steps:

Select or create a Cloud Platform Console project.

GO TO THE PROJECTS PAGE

Enable billing for your project.

ENABLE BILLING

Click Continue to enable the API and any related services.

On the Credentials page, get an API key.

Note: If you have an existing API key, you can use that key.

You must fill in your Google API key into the code, near the top.

This code borrows a JSON encoder from:
https://github.com/KAYLukas/applescript-json

The URL encode is from here:
https://developer.apple.com/library/content/documentation/LanguagesUtilities/Conceptual/MacAutomationScriptingGuide/EncodeandDecodeText.html#//apple_ref/doc/uid/TP40016239-CH51-SW1

