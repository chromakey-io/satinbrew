# satinbrew
Simple, soft, elegant developer and command line tools for CroSH

This is not a derivative work of chromebrew but a ground up implementation of a *real* package and dependency manager (that means you can actually un-install *all* of the dependencies related to your package you want to remove .... and delete  "oprhan" dependencies like you would with dnf or apt).

I'm still working out the core details.  Though we won't be using Sanskrit or ruby.

Package files will likely be written in either python or yaml, depending on how lazy I am.

Likewise there will be very strict requirements for the packages permitted in this repository.  No X11, Wayland, or attempts at creating UI-based tools in ChromeOS.  It's a clear violation of Google's intent and will be pointless to even attempt.  Current dev branches, Linux, apk, and web-bundles/PWAs work.  You want Atom, VSCode, or what-ever install it how google has intended you to, or if you like to live on the edge install crouton.

This project is built in the original spirit of homebrew, to vastly improve the command line developer experience in CroSH.  Multiple ruby, python, and node versions so you can match what you work with on your projects.  CLI tools that google doesn't provide ... and a package maanager that can manage everything thee *right* way.


Also, sorry but there won't be support for i686 or armv7.  There's ~5 devices still "supported" by google, I've no intention of supporting them here.
