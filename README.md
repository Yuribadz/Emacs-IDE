# Emacs-IDE

Hello.
If you are here, you are probably looking how you can configure your Emacs as 
C++ IDE. You can adjust any options as you like.
Custom keybind for autocompletion is configured to CTRL+ENTER.

Once you opened C++ file, you should have C++ mode, FlyCheck Mode, Helm Mode.
To enable autocompletion you should enable company-mode.

Emacs to be used with this config is 25.2 or newer.
If you have older please consider compiling/installing it on your system.

For autocompletion this configuration is using LLVM >= 3.8.2.
This configuration is using Projectile as project manager and cmake-ide plugin.

## Installation
`init.el` or its content should be placed in your `emacs.d` folder.
Then you should start installing packages using `M-X package install [package])` to install 
all required packages from `MELPA` repository. 

Here's list of packages used by this configuration:


`1. req-package`
`2. irony`
`3. company`
`4. company-irony`
`5. irony company-c-headers`
`6. rtags`
`7. company-rtags`
`8. zenburn-theme (optional)`
`9. cmake-ide`
`10. helm-projectile`
`11. projectile`
`12. flycheck`
`13. flycheck-rtags`
`14. helm-rtags`
`15. irony-eldoc`
`16. flycheck-irony `
`17. el-get`

Install irony server for your emacs configuration by running `M-X irony-install-server`.
After installing irony configure rtags instance aka rdm  server. There is 2 possible ways :

1. Install from Emacs. Might not work, but should be given a try first.
2. Install from source. Works for most users.

Detailed instruction for rtags is available on [rtags Github](https://github.com/Andersbakken/rtags/wiki/Installing-RTags)

