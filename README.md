# ProcessMigratePadloperToPWCommerce
Process Module to help migrate Padloper to ProcessWire Commerce

# Requirements

1. Existing install of Padloper 011. Older versions might work.
2. Writeable /site/templates/.

# Migrate

## Important Read

This tool will migrate your Padloper shop to ProcessWire Commerce shop. Please carefully read and action the following notes!

1. Usage of this tool is at your own risk.
2. Create a **whole backup of your site before getting started**.
3. **DO NOT MANUALLY UNINSTALL Padloper!** This tool will do that for you. It will also uninstall all related Modules and Fields and preserve existing fields data.
4. **DO NOT MANUALLY INSTALL ProcessWire Commerce!** This tool will do that for you. It will also install related Modules and Fields and import existing fields data. Otherwise, you risk losing all your data (pages deleted).
5. Download and unzip ProcessWire Commerce to `/site/modules/`.
6. **Do a Modules Refresh** so that ProcessWire will see ProcessWire Commerce modules. Make sure you see notices about 'found new module...'.
7. Preferably, **test a migration on a test server first**.
8. If the tests pass, it is still advisable to create a duplicate of your production site, run the migration there, create a database dump of the migrated site and use that to update your real production site.
9. Install this module, go to its dashboard (`Migrate Padloper to PWCommerce`) and follow the instructions.
10. You might have to manually uninstall/install some Padloper/ProcessWire Commerce modules.
11. Once all pending manual tasks are completed, you can delete Padloper modules from your system.

# License 

```
The MIT License (MIT)

Copyright 2025 Francis Otieno

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the “Software”), to deal in the
Software without restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```