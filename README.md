windows-installer
=================

A WIX bootstrapper EXE with DigiDoc4 Client and package with various drivers and browser plugins.

1. Fetch the source

        git clone --recursive https://github.com/open-eid/windows-installer
        cd windows-installer

2. Download dependencies to packages folder
   * Digidoc4*x64.msi
   * ID-Updater*x64.msi
   * web-eid*x64.msi
   * AWP*x64*.msi

3. Run build.ps1 script, optional parameter -msiversion

        powershell -ExecutionPolicy ByPass -File build.ps1

4. Execute

        Open-EID.exe

## Support
Official builds are provided through official distribution point [id.ee](https://www.id.ee/en/article/install-id-software/). If you want support, you need to be using official builds. Contact our support via [www.id.ee](http://www.id.ee) for assistance.


Source code is provided on "as is" terms with no warranty (see license for more information). Do not file Github issues with generic support requests.
