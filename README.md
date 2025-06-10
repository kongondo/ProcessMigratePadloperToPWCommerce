# ProcessMigratePadloperToPWCommerce
Process Module to help migrate Padloper to ProcessWire Commerce

# Requirements

1. Existing install of Padloper 011. Older versions might work.
2. Writeable /site/templates/.

# Migrate

## Important Read

This tool will migrate your Padloper shop to ProcessWire Commerce shop. Please carefully read and action the following notes!

1. Usage of this tool is at your own risk.
2. Create a whole backup of your site before getting started.
3. DO NOT MANUALLY UNINSTALL Padloper! This tool will do that for you. It will also uninstall all related Modules and Fields and preserve existing fields data.
4. DO NOT MANUALLY INSTALL ProcessWire Commerce! This tool will do that for you. It will also install related Modules and Fields and import existing fields data.
5. Preferably, test on test server.
6. If the tests pass, it is still advisable to create a duplicate of your production site, run the migration there, create a database dump of the migrated site and use that to update your real production site.
7. Do not uninstall Padloper until after this script has finished successfully. Doing so will delete all your Padloper pages!
8. Install this module, go to its dashboard (`Migrate Padloper to PWCommerce`) and follow the instructions.

```
The MIT License (MIT)

Copyright 2025 Francis Otieno

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the “Software”), to deal in the
Software without restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so,
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