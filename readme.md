<div align="center">
	<div>
		<img src="media/logo.png" alt="Awesome Ricing">
	</div>
	<br>
	<p> A curated list of awesome tools and technologies to make your Operating System look beautiful ❤️ </p>
	<img src="https://awesome.re/badge.svg" alt="Awesome Badage">
</div>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Packages](#packages)
  - [window-managers](#window-managers)
      - [Tiling wms](#tiling-wms)
      - [Stacking and floating wms](#stacking-and-floating-wms)
      - [Dynamic tiling wms](#dynamic-tiling-wms)
      - [MacOS wms](#macos-wms)
  - [Show off scripts](#show-off-scripts)
  - [Terminals](#terminals)
    - [Other](#other)
  - [Bars and Panels](#bars-and-panels)
  - [CLI Tools](#cli-tools)
    - [System Monitors](#system-monitors)
    - [audio visualizers](#audio-visualizers)
      - [cli](#cli)
      - [non-cli](#non-cli)
    - [File managers](#file-managers)
    - [Weather Tools](#weather-tools)
    - [Fetches](#fetches)
    - [RSS/Atom Feed Readers](#rssatom-feed-readers)
    - [Misc Tools](#misc-tools)
    - [Informative](#informative)
  - [Colorschemes](#colorschemes)
    - [colorscheme-generators](#colorscheme-generators)
  - [Shells](#shells)
  - [Prompts](#prompts)
  - [Background setting utilities and generators](#background-setting-utilities-and-generators)
  - [resources (websites)](#resources-websites)
  - [Other](#other-1)
- [Communities](#communities)
  - [Reddit](#reddit)
- [TODO:](#todo)
- [Related lists](#related-lists)
- [Contributing](#contributing)
- [License](#license)

## Packages

### window-managers

##### Tiling wms

- [Bspwm](https://github.com/baskerville/bspwm) - A tiling window manager based on binary space partitioning. (C)
- [cocowm](https://github.com/tleino/cocowm) - Column Commander Window Manager for X11 Window System. (C)
- [dk](https://bitbucket.org/natemaia/dk) - tiling window manager taking inspiration from dwm, bspwm, and xmonad .(C)
- [PaperWM](https://github.com/paperwm/PaperWM) - Tiled scrollable window management for Gnome Shell .(JavaScript)
- [catwm](https://github.com/pyknite/catwm) - very simple tiling window manager. (C)
- [coma](https://github.com/jorisvink/coma) - My minimalistic X11 window manager. (C)
- [darwintiler](https://github.com/veryjos/darwintiler) - No frills, super easy tiling "window manager" for MacOS and x11/Linux. (C, Nim)
- [echinus](https://github.com/polachok/echinus) - a lightweight and easily configurable tiling window manager .(C)
- [endlesswm](https://github.com/peterfajdiga/EndlessWM) - A proof of concept of a scrolling window manager. (C)
- [exwm](https://github.com/ch11ng/exwm) - Emacs X window manager. (Emacs Lisp)
- [fpwm](https://github.com/sduverger/fpwm) - python tiling window manager .(python)
- [herbstluftwm](https://github.com/herbstluftwm/herbstluftwm) - A manual tiling window manager for X11. (C++,python)
- [howm](https://github.com/HarveyHunt/howm) - A lightweight, X11 tiling window manager that behaves like vim. (C)
- [i3](https://github.com/i3/i3) - A tiling window manager. (C , perl)
- [larswm](http://porneia.free.fr/larswm/larswm.html) - A tiling window manager based on 9wm. (C)
- [leftwm](https://github.com/leftwm/leftwm) - A tiling window manager for Adventurers. (rust)
- [marwind](https://github.com/patrislav/marwind) - A simple X11 tiling window manager .(go)
- [notion](https://github.com/raboof/notion) - Tiling tabbed window manager. (C,Lua)
- [pytyle1x](https://github.com/zehkira/pytyle1x) - Tiling manager which runs on top of EWMH window managers. (python)
- [qtile](https://github.com/qtile/qtile) - A full-featured, hackable tiling window manager written and configured in Python .(python)
- [quicktile](https://github.com/ssokolow/quicktile) - (Adds window-tiling hotkeys to any X11 desktop. (An analogue to WinSplit Revolution for people who don't want to use Compiz Grid (python)
- [ratpoison](https://www.nongnu.org/ratpoison/) - simple Window Manager with no fat library dependencies.(C)
- [sara](https://github.com/gitluin/sara) - Originally a fork of catwm, now an offspring of dwm with a streamlined featureset, plus some bspwm. (C)
- [sdorfehs](https://github.com/jcs/sdorfehs) - X11 Window manager. (C)
- [shellshape](https://github.com/timbertson/shellshape) - tiling window manager extension for gnome-shell .(typescript)
- [shod](https://github.com/phillbush/shod) - hybrid (floating and tiling) tabbed window manager. (C)
- [stumpwm](https://github.com/stumpwm/stumpwm) - X11 Window Manager written entirely in Common Lisp. .(Common Lisp)
- [subtle](https://github.com/MinasMazar/subtle) - A grid-based manual window manager .(C, ruby)
- [taowm](https://github.com/nigeltao/taowm) - The Acutely Opinionated Window Manager .(go)
- [tidalwm](https://github.com/rustysec/tidalwm) - Simple and sane tiling window manager for Gnome Shell .(JavaScript)
- [wmderland](https://github.com/aesophor/wmderland) - X11 tiling window manager using space partitioning trees .(C++)
- [wmii](https://github.com/0intro/wmii) - A small, scriptable window manager, with a 9P filesystem interface and an acme-like layout. (C)
- [xoat](https://github.com/seanpringle/xoat) - An obstinate, asymmetric, tiling, window manager for X. (C)

##### Stacking and floating wms

- [2bwm](https://github.com/venam/2bwm) - A fast floating WM written over the XCB library and derived from mcwm. (C)
- [9wm](https://github.com/9wm/9wm) - X11 Window Manager inspired by Plan 9's rio. (C)
- [Iwm](http://www.jfc.org.uk/software/lwm.html) - window manager for X that tries to keep out of your face. (C)
- [aewmpp](https://github.com/frankhale/aewmpp) - a small window manager for X11 based originally off aewm . (C++)
- [afterstep](https://github.com/afterstep/afterstep) - Super configurable, extra lightweight, and fluidly fast Window Manager for X. (C)
- [berry](https://github.com/JLErvin/berry) - A healthy, byte-sized window manager. (C)
- [blackbox](https://github.com/bbidulock/blackboxwm) - A window manager for X11 (C++)
- [bouncy-window-manager](https://github.com/expectocode/bouncy-window-manager). A toy X11 window manager that bounces windows around. (rust)
- [compiz](https://gitlab.com/compiz/compiz-core) - OpenGL compositing manager . (C)
- [cswm](https://github.com/ajnewlands/cswm) - A simple X11 window manager. (C#)
- [cwm](https://github.com/leahneukirchen/cwm) - portable version of OpenBSD's cwm(1) window manager (C)
- [eggwm](https://code.google.com/archive/p/eggwm) - A lightweight QT4/QT5 window manager. (C++)
- [evilwm](https://github.com/nikolas/evilwm) - A really great window manager that's usable without writing a 20 line configuration file. (C)
- [footwm-chez](https://github.com/akce/footwm-chez) - Implementation of footwm in chez scheme. (scheme)
- [fluxbox](https://github.com/fluxbox/fluxbox) - a windowmanager for X that was based on the Blackbox. (C++)
- [flwm](https://github.com/bbidulock/flwm) - fast light window manager. (C)
- [fvwm3](https://github.com/fvwmorg/fvwm3) - FVWM version 3 -- the successor to fvwm2. (C)
- [gala](https://github.com/elementary/gala) - beautiful window manager for Pantheon. (vala)
- [goomwm](https://github.com/seanpringle/goomwwm) - Get out of my way, Window Manager! . (C)
- [HOTDOG](https://github.com/arthurchoung/HOTDOG) - X11 Window Manager with Windows 3.1 Hot Dog Stand, Amiga Workbench, Atari ST GEM, and Classic Mac UI. (objective-c)
- [icewm](https://github.com/bbidulock/icewm) - A window manager designed for speed, usability, and consistency. (C++)
- [lcarswm](https://github.com/lcarsde/lcarswm) - carswm (LCARS Window Manager) is a window manager that is supposed to look like an LCARS interface. It's written in Kotlin and utilizing XLib. (kotlin)
- [jbwm](https://github.com/jefbed/jbwm) - Tiny and powerful window manager for X11. (C)
- [jwm](https://github.com/joewing/jwm) - Joe's window manager. (C)
- [karmen](http://karmen.sourceforge.net/) - A window manager with support for docks and hidpi displays. (C)
- [kwin](https://github.com/KDE/kwin) - Easy to use, but flexible, X Window Manager and Wayland Compositor. (C++)
- [marco](https://github.com/mate-desktop/marco) - mate's default wm. (C)
- [metacity](https://gitlab.gnome.org/GNOME/metacity) - Gnome 2 wm . (C)
- [miniwinwm](https://github.com/miniwinwm/miniwinwm) - Open source embedded window manager with overlapped windows. (C)
- [muffin](https://github.com/linuxmint/muffin/) - The window management library for the Cinnamon desktop (libmuffin) and its sample WM binary (muffin) . (C)
- [mutter](https://gitlab.gnome.org/GNOME/mutter/) - A Wayland display server and X11 window manager and compositor library.
- [no-wm](https://github.com/patrickhaller/no-wm) - Use X11 without a window manager . (C)
- [octopus-window-manager](https://github.com/ghjp/octopus-window-manager) - Low resource X11 Window manager using libcairo. (C)
- [openbox](https://github.com/danakj/openbox) - Highly configurable, next generation window manager with extensive standards support. (C)
- [pawm](https://sites.google.com/site/pleyadestest/david/projects/pawm) - a minimalistic window manager for the X Window System. (C)
- [pekwm](https://github.com/pekdon/pekwm) - X11 window manager .(C++)
- [starwm](https://github.com/StarWM/StarWM) - an extensible, floating and tiling, X window manager for linux (rust)
- [sowm](https://github.com/dylanaraps/sowm) - An itsy bitsy floating window manager (220~ sloc!) .(C)
- [tinywm](https://github.com/mackstann/tinywm) - The tiniest window manager. (C)
- [twm](https://github.com/freedesktop/twm) - Timeless Windows Manager . (C)
- [ukwm](https://github.com/ukui/ukwm/) - ukui window manager . (C)
- [uwm](https://github.com/dreamos82/uwm)- Useless window manager - Not a window manager!!! Just window manager experiments... (C)
- [waimea](https://github.com/bbidulock/waimea) - An X11 window manager designed for maximum efficiency. (C++)
- [windowlab](https://github.com/nickgravgaard/windowlab) - A small and simple window manager of novel design . (C)
- [windowmaker](http://www.windowmaker.org/) - X11 window manager originally designed to provide integration support for the GNUstep Desktop Environment . (C)
- [vswm](https://github.com/fehawen/vswm) - A very stupid window manager. (C)
- [worm](https://github.com/codic12/worm) A floating, tag-based window manager. (nim)
- [wm2](https://www.all-day-breakfast.com/wm2/) - a window manager for X. (C)
- [xfwm3](https://gitlab.xfce.org/xfce/xfwm4) - xfce's window manager. (C)
- [xwm](https://github.com/mcpcpc/xwm) - A tiny XCB floating window manager. (C)

##### Dynamic tiling wms

- [adwm](https://github.com/bbidulock/adwm) - advanced dynamic window manager. (C)
- [Alopex](https://github.com/TrilbyWhite/alopex) - tabbed tiling window manager .(C)
- [awesome](https://github.com/awesomeWM/awesome) - awesome window manager .(lua)
- [chamferwm](https://github.com/jaelpark/chamferwm) - A tiling X11 window manager with Vulkan compositor. (C++)
- [dwm](https://dwm.suckless.org/) - dynamic window manager. (C)
- [frankenwm](https://github.com/sulami/FrankenWM) - Fast dynamic tiling X11 window manager. (C)
- [instantwm](https://github.com/instantOS/instantWM)- window manager for instantOS . (C)
- [kranewm](https://github.com/deurzen/kranewm) - An ICCCM & EWMH compliant X11 reparenting, dynamic window manager. (C++)
- [monsterwm](https://github.com/c00kiemon5ter/monsterwm) - tiny but monstrous tiling window manager. (C)
- [nwm](https://github.com/mixu/nwm) - A dynamic window manager for X11 written with Node.js. (Javascript)
- [sawfish](https://github.com/SawfishWM/sawfish) - Sawfish Window-Manager (Common Lisp)
- [spectrwm](https://github.com/conformal/spectrwm) - A small dynamic tiling window manager for X11. (C)
- [sxwm](https://github.com/jasonmxyz/sxwm) - Superior X Window Manager. (C)
- [velox](https://github.com/michaelforney/velox) - Window manager inspired by dwm and xmonad. (C)
- [wingo](https://github.com/BurntSushi/wingo) - A fully-featured window manager. (go)
- [wzrd](https://github.com/deurzen/wzrd) - An ICCCM & EWMH compliant X11 reparenting, dynamic window manager. (rust)
- [xmonad](https://github.com/xmonad/xmonad) - a small but functional ICCCM-compliant tiling window manager . (Haskell)  

##### MacOS wms

- [yabai](https://github.com/koekeishiya/yabai) - A tiling window manager for macOS based on binary space partitioning. (C)
- [Amethyst](https://github.com/ianyh/Amethyst) - Automatic tiling window manager for macOS à la xmonad. (Swift)

#### Other

- [vioarr](https://github.com/Meulengracht/vioarr) - Open source, cross-platform window manager. Default window manager for Vali/MollenOS. (C)

---

### Show off scripts

- [cmatrix](https://github.com/abishekvashok/cmatrix) - Simple terminal matrix implementation. (C)
- [pipes.sh](https://github.com/pipeseroni/pipes.sh) - Script which generates animated colorful pipes. (shell)
- [cbonsai](https://gitlab.com/jallbrit/cbonsai) - Tree growing animation with your own text. (C)
- [tty-clock](https://github.com/xorg62/tty-clock) - Customizable clock in terminal. (C)

---

### Terminals

- [Alacritty](https://github.com/alacritty/alacritty) - A cross-platform, GPU-accelerated terminal emulator. (rust)
- [cool-retro-term](https://github.com/Swordfish90/cool-retro-term) - A good looking terminal emulator which mimics the old cathode display. (qml)
- [CRTerm](https://github.com/bolner/CRTerm) - CRT Terminal emulator (OpenGL). (java)
- [Contour](https://github.com/christianparpart/contour) - Modern C++ Terminal Emulator. (C++)
- [darktile](https://github.com/liamg/darktile) - a GPU rendered terminal emulator designed for tiling window managers. (go)
- [deepin-terminal](https://github.com/linuxdeepin/deepin-terminal) - Terminal for deepin DE. (C++)
- [eterm](https://github.com/mej/Eterm) - Eterm terminal emulator , made as a replacement for xterm. (C)
- [Extraterm](https://github.com/sedwards2009/extraterm) - The swiss army chainsaw of terminal emulators. (typescript)
- [Flterm](https://github.com/yongchaofan/FLTerm) - fast light terminal emulator. (C++)
- [finalterm](https://github.com/p-e-w/finalterm) - At last – a modern terminal emulator. (vala)
- [Guake](https://github.com/Guake/guake) - Drop-down terminal for GNOME. (python)
- [Hyper](https://github.com/zeit/hyper) - A terminal built on web technologies. (javascript)
- [Konsole](https://konsole.kde.org/) - Konsole is a terminal emulator for the K Desktop Environment. (c++)
- [Kitty](https://github.com/kovidgoyal/kitty) - The fast, featureful, GPU based terminal emulator. (c, python)
- [Lilyterm](https://github.com/Tetralet/LilyTerm) - A lightweight, but functional terminal emulator. (C)
- [Lilt](https://github.com/MurphyMc/lilt) - a simple and portable terminal emulator. (c)
- [lite](https://github.com/TerminalStudio/lite) - terminal written in dart. (dart)
- [lwt](https://github.com/mewkiz/lwt) - lightweight terminal emulator based on the VTE and GTK libraries. (C)
- [Lxterminal](https://github.com/lxde/lxterminal) - VTE terminal emulator written in GTK. (c)
- [KMSCON](https://github.com/dvdhrm/kmscon) - Linux KMS/DRM based virtual Console Emulator. (C)
- [moonterm](https://github.com/sodomon2/moonterm) - A minimalist and customizable terminal in lua. (lua)
- [notty](https://github.com/withoutboats/notty) virtual terminal like xterm, gnome-vte,rxvt. (rust)
- [Pantheon](https://github.com/elementary/terminal) - Terminal emulator designed for elementary OS. (vala)
- [pyxterm](https://github.com/mitotic/pyxterm) - a terminal written in javaScript with a python backend. (javascript)
- [qterminal](https://github.com/lxqt/qterminal) lightweight Qt terminal emulator based on QTermWidget. (c++)
- [quickterminal](https://github.com/trollixx/quickterminal) - Lightweight terminal emulator. (C++)
- [Roxterm](http://roxterm.sourceforge.net/) - ROXTerm is a terminal emulator intended to provide similar features to gnome-terminal. (c)
- [rxvt-unicode](http://software.schmorp.de/pkg/rxvt-unicode.html) - rxvt-unicode is a fork of the well known terminal emulator rxvt. (c)
- [st](https://st.suckless.org/) - st is a simple terminal implementation for X. (c)
- [Sakura](https://launchpad.net/sakura) - Simple but powerful libvte based terminal emulator. (c)
- [Tabby](https://github.com/Eugeny/tabby) - A terminal for a more modern age. (typescript)
- [Terminology](https://github.com/billiob/terminology) - The best terminal emulator based on the Enlightenment Foundation Libraries. (c)
- [Termite](https://github.com/thestinger/termite/) - A keyboard-centric VTE-based terminal. (c++)
- [Termit](https://github.com/nonstop/termit) terminal emulator based on VTE library with Lua scripting. (c)
- [Termkit](https://github.com/unconed/TermKit) - Experimental Terminal platform built on WebKit + node.js that aims to construct aspects of the GUI . (javascript)
- [Termonad](https://github.com/cdepillabout/termonad) - Terminal emulator configurable in Haskell. (Haskell)
- [Tilix](https://gnunn1.github.io/tilix-web/) - A keyboard-centric VTE-based terminal. (d)
- [Tilda](https://github.com/lanoxx/tilda) - A Gtk based drop down terminal for Linux and Unix. (c)
- [Terminator](https://gnometerminator.blogspot.com/p/introduction.html) - Terminal with the ability to create multiple terminals in one window and faster your work progress. (java)
- [Tym](https://github.com/endaaman/tym) - Lua-configurable terminal emulator. (C)
- [Upterm](https://github.com/railsware/upterm) - A terminal emulator for the 21st century. (typescript)
- [uterm](https://github.com/refi64/uterm) - A WIP terminal emulator, written in C++11 using Skia, libtsm, and GLFW. (C)
- [viter](https://github.com/Kharacternyk/viter) - A Vim-ish terminal emulator written and expandable in Python. (python)
- [wterm](https://sourceforge.net/projects/wterm/) - another light weight color terminal emulator based on rxvt project. (C)
- [Wezterm](https://github.com/wez/wezterm) - A GPU-accelerated cross-platform terminal emulator and multiplexer. (Rust)
- [xfce4-terminal](https://github.com/xfce-mirror/xfce4-terminal) - Xfce Terminal is a lightweight and easy to use terminal emulator with advanced features (c)
- [Xiate](https://www.uninformativ.de/git/xiate/file/README.html) lightweight VTE-based terminal. (c)
- [Xterm](http://invisible-island.net/xterm/) - The xterm program is a terminal emulator for the X Window System. (c)
- [xtermSharp](https://github.com/migueldeicaza/XtermSharp) - XTerm emulator as a .NET library . (C#)
- [xterm.dart](https://github.com/TerminalStudio/xterm.dart) - xterm.dart is a fast and fully-featured terminal emulator for Flutter, with support for mobile and desktop platforms. (dart)
- [Yakuake](https://www.kde.org/applications/system/yakuake/) - Yakuake is a drop-down terminal emulator based on KDE Konsole technology. (c++)
- [yat](https://github.com/jorgen/yat) - Terminal Emulator written in C++ and qml. (C++)

#### Other

- [GateOne](https://github.com/liftoff/GateOne) - Gate One is an HTML5-powered terminal emulator and SSH client. (javaScript)
- [JQuery.terminal](https://terminal.jcubic.pl/) - A plugin for creating command line interpreters. (javascript)
- [Xterm](https://github.com/termux/termux-app) - Android terminal and Linux environment. (java)
- [Xterm.js](https://xtermjs.org/) - Xterm.js is a terminal front-end component written in JavaScript that works in the browser. (typescript)
- [kterminal](https://github.com/heatherhaks/kterminal) - A terminal display emulator using libKTX and libGDX. (kotlin)
- [fbpad](https://github.com/aligrudi/fbpad) - A small Linux framebuffer virtual terminal. (C)
- [fauxterm](https://github.com/isdampe/fauxTerm) - A lightweight (~2KB), faux, terminal-like emulator for the web in javascript. (JavaScript)

---

### Bars and Panels

[Courtesy = @siduck76]

- [barmaid.lua](https://github.com/ColumPaget/barmaid.lua) - A status-bar generation program for dzen2, lemonbar, or the terminal. (lua)
- [barr](https://github.com/OkayDave/barr) - Barr is a status line style generator for LemonBar. (ruby)
- [bevelbar](https://www.uninformativ.de/git/bevelbar/file/README.html) - Draw an X11 status bar with fancy schmancy 1985-ish beveled borders. (C)
- [blockbar](https://gitlab.com/sambazley/blockbar) - Blocks based status bar for X window managers. (C)
- [bmpanel](https://github.com/nsf/bmpanel) - lightweight, netwm compliant, x11 panel with desktop switcher, taskbar, systray and clock. (C)
- [bumblebee-status](https://github.com/tobi-wan-kenobi/bumblebee-status) - A modular, theme-able status line generator for the i3wm. (python)
- [cnx](https://github.com/mjkillough/cnx) - A simple X11 status bar for use with simple WMs. (rust)
- [dwmbar-powerline](https://github.com/Leomv55/dwmbar-powerline) - dwmbar with powerline look. (go)
- [dwmbar](https://github.com/thytom/dwmbar) - A Modular Status Bar for dwm. (shell)
- [dzenbar](https://github.com/qbbr/dzenbar) - dzen2 bar w multiple monitors support. (shell)
- [eww](https://github.com/elkowar/eww) - ElKowar's wacky widgets. (rust)
- [fbpanel](https://github.com/aanatoly/fbpanel) - lightweight X11 desktop panel. (C)
- [gobar](https://github.com/distatus/gobar) - minimalistic X status bar. (go)
- [goblocks](https://github.com/davidscholberg/goblocks) - Fast, lightweight i3status . (go)
- [goi3bar](https://github.com/denbeigh2000/goi3bar) - Configurable, extensible replacement . (go)
- [i3blocks](https://github.com/vivien/i3blocks) - A flexible scheduler for your i3bar blocks. (C)
- [i3status-rust](https://github.com/greshake/i3status-rust) - Very resourcefriendly and feature-rich replacement for i3status. (rust)
- [i3status](https://github.com/i3/i3status) - Generates status bar to use with i3bar, dzen2 or xmobar. (C)
- [lemonbar](https://github.com/LemonBoy/bar) - A featherweight, lemon-scented, bar based on xcb. (C)
- [luastatus](https://github.com/shdown/luastatus) - universal status bar content generator. (C)
- [lxpanel](https://github.com/lxde/lxpanel) - Lightweight X11 desktop panel. (C)
- [mate-panel](https://github.com/mate-desktop/mate-panel) - MATE panel. (C)
- [monky](https://github.com/monky-hs/monky) - Universal status bar content generator. (Haskell)
- [mowedline](https://github.com/retroj/mowedline) - A X status bar program. (scheme)
- [oxbar](https://github.com/ryanflannery/oxbar) - configurable X11 status bar for OpenBSD. (C)
- [perlpanel](https://savannah.nongnu.org/projects/perlpanel/) - Panel made for X11 wms like openbox , icewm. (perl)
- [polybar](https://github.com/polybar/polybar) - A fast and easy to use bar. (C++)
- [polydock](https://github.com/folke/polydock) - A shiny and hackable application dock. (typescript)
- [py3status](https://github.com/ultrabug/py3status) - py3status is an extensible i3status wrapper. (python)
- [pypanel](http://pypanel.sourceforge.net) - lightweight panel/taskbar for X11 wms (python , C)
- [quobar](https://github.com/tv42/quobar) - X11 status bar. (go)
- [rust-dwm-status](https://github.com/pierrechevalier83/rust-dwm-status) - A status bar for dwm .(rust)
- [statbar](https://github.com/pzl/statbar) - A Linux status bar, supporting multiple lightweight clients (multi-head). (C)
- [statusbar](https://github.com/l3pp4rd/statusbar) - Statusbar for linux window manager. (go)
- [taffybar](https://github.com/taffybar/taffybar) - A gtk based status bar for tiling window managers such as XMonad. (Haskell)
- [tianbar](https://github.com/koterpillar/tianbar) - A status bar for XMonad using WebKit for rendering. (Haskell)
- [tint2](https://gitlab.com/o9000/tint2) - A lightweight panel/taskbar for Linux and BSD. (C)
- [tint3](https://github.com/jmc-88/tint3) - rewrite of the tint2 panel. (C)
- [tinto-panel](https://github.com/chigoncalves/tinto-panel) - Tiny X11 panel. (C)
- [unixbar](https://github.com/unrelentingtech/unixbar) - Rust library for creating output for UNIX-style desktop bars like i3bar/swaybar, dzen2, lemonbar. (rust)
- [vala-panel](https://gitlab.com/vala-panel-project/vala-panel) - Vala rewrite of SimplePanel. (C)
- [vbar](https://github.com/AndrewVos/vbar) - A lightweight bar written .(go)
- [waybar](https://github.com/Alexays/Waybar) - Highly customizable Wayland bar for Sway and Wlroots based compositors. (C++)
- [winbar](https://github.com/jmanc3/winbar) - A familiar X11 panel/dock to ease new linux users transitio. (C++)
- [wingpanel](https://github.com/elementary/wingpanel) - Stylish top panel that holds indicators and spawns an application launcher. (vala)
- [xfce4-panel](https://gitlab.xfce.org/xfce/xfce4-panel) - A panel made for xfce , should work on most stacking wms too. (C)
- [xmobar](https://github.com/jaor/xmobar) - A minimalistic status bar. (Haskell)
- [yabar](https://github.com/geommer/yabar) - A modern and lightweight status bar for X window managers. (C)
- [yagostatus](https://github.com/burik666/yagostatus) - Yet Another i3status replacement. (go)
- [yambar](https://codeberg.org/dnkl/yambar) - Modular status panel for X11 and Wayland, inspired by polybar. (C)

---

### CLI Tools

#### System Monitors

- [Atop](https://github.com/Atoptool/atop) - System and process monitor for Linux. (C)
- [bashtop](https://github.com/aristocratos/bashtop) - Linux/OSX/FreeBSD resource monitor (bash)
- [btop](https://github.com/aristocratos/btop) - Linux/OSX/FreeBSD resource monitor (C++)
- [bottom](https://github.com/ClementTsang/bottom) - Yet another cross-platform graphical process/system monitor. (rust)
- [Glances](https://github.com/nicolargo/glances) - Glances an Eye on your system. A top/htop alternative. (python)
- [Gotop](https://github.com/cjbassi/gotop) - A terminal based graphical activity monitor inspired by gtop and vtop. (go,C)
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for terminal. (js)
- [Htop](hisham.hm/htop/) - htop is an interactive text-mode process viewer for Unix systems. (C)
- [Nvtop](https://github.com/Syllo/nvtop) - NVIDIA GPUs htop like monitoring tool. (C)
- [sampler](https://github.com/sqshq/sampler) - Tool for shell commands execution, visualization and alerting. Configured with a simple YAML file. (go)
- [s-tui](https://github.com/amanusk/s-tui) - Terminal based CPU stress and monitoring utility. (python)
- [smterminal](https://github.com/gurayyarar/smterminal) - System monitoring for terminal on Linux, OSX and Windows. (typescript)
- [sysstat](https://github.com/sysstat/sysstat) - Performance monitoring tools for Linux. (C)
- [vtop](https://github.com/MrRio/vtop) - A graphical activity monitor for the command line. (js)
- [ytop](https://github.com/cjbassi/ytop) - A TUI system monitor. (rust)

#### audio visualizers

##### cli

- [barva](https://github.com/Kharacternyk/barva) - An audio visualizer that pulses the background of your terminal (or anything else). (python)
- [cava](https://github.com/karlstav/cava) - Console-based Audio Visualizer for Alsa. (C)
- [catnip](https://github.com/noriah/catnip) - terminal audio visualizer for linux/unix/macOS/windblows. (go)
- [cli-visualizer](https://github.com/dpayne/cli-visualizer) - CLI based audio visualizer. (C++)
- [ReVidia-Audio-Visualizer](https://github.com/GhostNaN/ReVidia-Audio-Visualizer) - A highly customizable real time audio visualizer on Linux/Windows. (python)
- [xava](https://github.com/nikp123/xava) - X11 Audio Visualizer for ALSA. (C)

##### non-cli

- [audio-visualizer](https://github.com/JonathanZWhite/audio-visualizer) - Processing program for visualizing music and sounds. (java)
- [audio-visualizer-screenlet](https://github.com/ninlith/audio-visualizer-screenlet) - Cross-platform audio visualization desktop widget. (python)
- [desktop-visualizer](https://github.com/TheBITLINK/desktop-visualizer) - Linux Desktop Music visualizer made with SFML. (C++)
- [electron-music-visualizer](https://github.com/mak-thevar/electron-music-visualizer) - A desktop music visualizer using electronjs. (JavaScript)
- [glava](https://github.com/jarcode-foss/glava) - GLava - OpenGL audio spectrum visualizer. (C)
- [panon](https://github.com/rbn42/panon) - An Audio Visualizer Widget in KDE Plasma. (QML)
- [recidia-audio-visualizer](https://github.com/GhostNaN/recidia-audio-visualizer) - A highly customizable real time audio visualizer on Linux (C++)
- [Realtime_PyAudio_FFT](https://github.com/aiXander/Realtime_PyAudio_FFT) - Realtime audio analysis in Python, using PyAudio and Numpy to extract and visualize FFT features from streaming audio. (python)
- [visualizer](https://github.com/GuidoFe/visualizer) - Transforms cava music visualizer in a cool desktop decoration. (shell)
- [visualizers](https://github.com/efyang/visualizers) - An audio visualizer for linux based on impulse. (rust)

#### File managers

[Courtesy - @siduck76]

- [cfiles](https://github.com/mananapr/cfiles) - A ncurses file manager written in C with vim like keybindings. (C)
- [cfm](https://github.com/willeccles/cfm) - Simple and fast TUI file manager with no dependencies. (C)
- [clifm](https://github.com/leo-arch/clifm) - a completely CLI-based, shell-like and KISS file manager , lightweight as hell. (C)
- [clifm](https://github.com/pasqu4le/clifm) - Command Line Interface File Manager. (Haskell)
- [dfm](https://github.com/cglindkamp/dfm) - Dynamic File Manager. (C)
- [fff](https://github.com/dylanaraps/fff) - A simple file manager written in bash. (shell)
- [fm](https://github.com/mreyoud/fm) - c99 ncurses file manager for posix. (C)
- [hund](https://github.com/miahuoe/hund) - A minimalistic terminal file manager. (C)
- [joshuto](https://github.com/kamiyaa/joshuto) - ranger-like terminal file manager. (rust)
- [lf](https://github.com/gokcehan/lf) - Terminal file manager inspired by ranger. (go)
- [mc](https://github.com/MidnightCommander/mc) - A free cross-platform orthodox file manager. (C)
- [mfm](https://gitlab.com/dron2065/mfm) - Minimal File Manager with multiple tabs and no dependencies. (C)
- [nav](https://github.com/jollywho/nav) - hackable ncurses file manager. (C)
- [ncursesFM](https://github.com/FedeDP/ncursesFM) - Ncurses File Manager for linux. (C)
- [nnn](https://github.com/jarun/nnn) - n³ The unorthodox terminal file manager. (C)
- [noice](https://git.2f30.org/noice/) - small file browser. (C)
- [ranger](https://github.com/ranger/ranger) - A VIM-inspired filemanager for the console. (python)
- [rover](https://github.com/lecram/rover) - simple file browser for the terminal. (C)
- [sfm](https://github.com/afify/sfm/) - similar file manager. (C)
- [sheeetfm](https://github.com/sug0/sheeetfm) - A sheeet file manager for sheeet computers. (C)
- [vifm](https://github.com/vifm/vifm) - Terminal file manager. (C)
- [xplr](https://github.com/sayanarijit/xplr) - A hackable, minimal, fast TUI file explorer. (Rust)

#### Weather Tools

- [ansiweather](https://github.com/fcambus/ansiweather) - Weather in terminal, with ANSI colors and Unicode symbols
- [Sky](https://gitlab.com/ceda_ei/sky) - A simple weather monitor server for your terminal based on curl
- [wego](https://github.com/schachmat/wego) - weather app for the terminal written in Go.
- [wttr.in](https://github.com/chubin/wttr.in) - The right way to check the weather

#### Fetches

- [afetch](https://github.com/13-CF/afetch) - Simple system info . (C)
- [afetch](https://github.com/sticky-tea/afetch) - A command-line system information tool. (assembly)
- [archfetch](https://github.com/xxczaki/archfetch) - Simple CLI system information tool for Arch Linux. (shell)
- [bfetch](https://github.com/NNBnh/bfetch) - Dynamic fetch displayer that SuperB. (shell)
- [bitfetch](https://gitlab.com/bit9tream/bitfetch) - simple cli system information tool . (C)
- [boxfetch.py](https://github.com/Endlassy/boxfetch.py) - Minimal Fetch in a Box. (python)
- [bunnfetch](https://github.com/elenapan/dotfiles/blob/master/bin/bunnyfetch) - tiny fetch. (shell)
- [bunny](https://github.com/Luvella/Bunnyfetch) - Tiny system info fetch utility. (rust)
- [bugfetch](https://github.com/RustemB/bugfetch) - System Information Fetcher. (raku)
- [cinfo](https://github.com/mrdotx/cinfo) - a fast and minimal system information tool for linux-based operating systems. (C)
- [cfetch](https://github.com/clieg/cfetch) - A simple system information tool for Linux. (shell)
- [cppfetch](https://github.com/Phate6660/cppfetch) - A neofetch-esque program written in CPP. (C++)
- [cpufetch](https://github.com/Dr-Noob/cpufetch) - Simple yet fancy CPU architecture fetching tool. (C)
- [crfetch](https://github.com/Phate6660/crfetch) - A WIP neofetch-like program. (cyrstal)
- [disfetch](https://github.com/q60/disfetch) - Yet another \*nix distro fetching program, but less complex. (shell)
- [elefetch](https://github.com/burntcarrot/elefetch) - Cross-platform alternative for neofetch. (go)
- [erlfetch](https://github.com/vereis/erlfetch) - A screenfetch / neofetch clone written in Erlang/OTP. (erlang)
- [gentoofetch](https://github.com/DmitryHetman/gentoofetch.sh) - System information script for Gentoo GNU/Linux. (shell)
- [ghfetch](https://github.com/bwac2517/ghfetch) - neofetch but for github. (typescript)
- [gf](https://github.com/Smirnov-O/gf) - Go Fetch - small fetch written on Golang. (go)
- [Hilbifetch](https://github.com/Hilbis/Hilbifetch) - Simple and small fetch. (lua)
- [Hyperfetch](https://github.com/ralseiii/hyperfetch) - a multi-threaded system information tool written in posix sh. (shell)
- [hfetch](https://github.com/gentoo-btw/hfetch) - yet another fetch written in bash. with fortune. (shell)
- [Kat-OH](https://github.com/70xH/Kat-OH) - A huge fetch. (go)
- [lfetch](https://github.com/TheUpBeat/lfetch) - Yet another fetch program. (C)
- [fastfetch](https://github.com/LinusDierheimer/fastfetch) - Like neofetch, but much faster because written in c. Only Linux. (c)
- [ferris-fetch](https://github.com/irevenko/ferris-fetch) - A system information tool for Rustaceans.(rust)
- [fetch](https://github.com/aeosynth/fetch) - polyglot fetch. (javaScript,rust,go)
- [fetch-master-6000](https://github.com/anhsirk0/fetch-master-6000) - Simple Dilbert themed system info-fe A system information tool for fetching tool. (perl)
- [fet.sh](https://github.com/6gk/fet.sh) - a fetch written in posix shell without any external commands. (shell)
- [fetcheya](https://github.com/ferhatgec/fetcheya) - Fegeya Fetcheya is Scrift's System Information Tool. (C++)
- [fetcher](https://github.com/ferhatgec/fetcher) - Fegeya Fetcher, pretty & cute system-information-tool. Written in FlaScript. (shell)
- [fetch.scm](https://github.com/KikyTokamuro/fetch.scm) - System information fetcher written in GNU Guile (scheme)
- [freshfetch](https://github.com/K4rakara/freshfetch) - a fresh take on neofetch. (rust)
- [frenzch.sh](https://github.com/FrenzyExists/frenzch.sh) - A cozy fetch
- [fsi](https://github.com/MustafaSalih1993/fsi). FSI (Fetch System Info) cli tool. (rust)
- [fsfetch](https://github.com/Phate6660/fsfetch) - A neofetch type program. (F#)
- [jfetch](https://github.com/Jimmysit0/jfetch) - A minimal Linux fetch script. (shell)
- [lovefetch](https://github.com/oppsec/lovefetch) - A CLI System Information Too. (Python)
- [lunafetch](https://github.com/SugarBlank/LunaFetch) - Returns system information fast. (C++)
- [luafetch](https://github.com/Phate6660/luafetch) - Info fetch program. (lua)
- [macchina](https://github.com/Macchina-CLI/macchina) - A system information fetcher, with an emphasis on performance and minimalism. (rust)
- [mafetch](https://github.com/fikriomar16/mafetch) - System info for Unix-like operating systems. (shell)
- [mfetch](https://github.com/depsterr/mfetch) - minmal fetch. (shell)
- [neofetch](https://github.com/dylanaraps/neofetch) - A command-line system information tool written in bash 3.2+ . (shell)
- [nerdfetch](https://github.com/ThatOneCalculator/NerdFetch) - A POSIX nix fetch script using Nerdfonts. (shell)
- [onefetch](https://github.com/o2sh/onefetch) - Git repository summary on your terminal. (rust)
- [paleofetch](https://github.com/ss7m/paleofetch) - neofetch, but written in (C).
- [pepefetch](https://github.com/Sigmw/pepefetch) - The pepe frog fetch. (rust)
- [perlfetch](https://github.com/Phate6660/perlfetch) - Think neofetch but in (perl)
- [phpfetch](https://github.com/Phate6660/phpfetch) - An info fetch tool written in PHP. Because why not. /shrug
- [pokefetch](https://github.com/rmccorm4/Pokefetch) - Command-line tool similar to neofetch for looking up pokemon in terminal. (python)
- [pfetch](https://github.com/dylanaraps/pfetch) - A pretty system information tool written in POSIX sh. (shell)
- [profetch](https://github.com/RustemB/profetch) - System Information Fetcher Written in GNU/Prolog. (Prolog)
- [rktfetch](https://github.com/mythical-linux/rktfetch) - System fetch program. (racket)
- [rsfetch](https://github.com/rsfetch/rsfetch) - Fast (~1ms execution time) and somewhat(?) minimal fetch program. (rust)
- [rsfetch](https://github.com/Phate6660/rsfetch) - A WIP rewrite of rsfetch from scratch. (rust)
- [rxfetch](https://github.com/Mangeshrex/rfetch) - minimal and pretty fetch. (shell)
- [sfetch](https://github.com/HenryDawson123/sfetch) - A simple fetch program. (C++)
- [sheen](https://github.com/digitalsurvival/sheen) - Cross-platform desktop screenshot boasting tool (neo/screenFetch reimplemented). (python)
- [sysfetch](https://github.com/mebesus/sysfex) - Another system information tool. (C++)
- [tuatara](https://github.com/q60/tuatara) - Ziggidy nix system info fetcher. (zig)
- [tfetch](https://github.com/Endlassy/tfetch) - Tree view like fetch. (python)
- [screenfetch](https://github.com/KittyKatt/screenFetch) - Fetches system/theme information in terminal for Linux desktop screenshots. (shell)
- [ufetch](https://gitlab.com/jschx/ufetch) - Tiny system info for Unix-like operating systems. (shell)
- [uwufetch](https://github.com/TheDarkBug/uwufetch) - A meme system info tool for Linux, based on nyan/uwu trend on r/linuxmasterrace. (C)
- [vfetch](https://github.com/Lorago/vfetch) - A simple fetch tool for Linux . (python)
- [winfetch](https://github.com/lptstr/winfetch) - A command-line system information utility.Like Neofetch, but for Windows. (Powershell)
- [winfetch](https://github.com/M4cs/winfetch) - Neofetch/Screenfetch Alternative. (go)
- [wfetch](https://github.com/freddie-nelson/wfetch) - A neofetch like cli tool for windows. (go)
- [yafetch](https://github.com/yrwq/yafetch) - yet another shell. (C)
- [yayfetch](https://github.com/golota60/yayfetch) - Multi-platform screenfetch. (typescript)
- [skyfetch](https://github.com/justleoo/skyfetch) - Simple system fetch information. (rust)

#### RSS/Atom Feed Readers

- [newsboat](https://github.com/newsboat/newsboat) - An RSS/Atom feed reader forked from Newsbeuter. (C++/Rust)
- [Sfeed](https://codemadness.org/sfeed-simple-feed-parser.html) - A very minimal and lightweight RSS/Atom Reader. (C)
- [snownews](https://github.com/msharov/snownews) - A text-mode RSS/Atom aggregator. (C)
- [ureader](https://github.com/pxqr/ureader) - A minimalistic cli RRS reader with unicode and color support. (Haskell)

#### Misc Tools

- [Cbonsai](https://gitlab.com/jallbrit/cbonsai) - grow bonsai trees in your terminal. (C)
- [Chalk-Animation](https://github.com/bokub/chalk-animation) - Colorful animations on terminal. (javascript)
- [Console-Services](https://github.com/chubin/awesome-console-services) - A curated list of awesome console services.
- [Exa](https://github.com/ogham/exa) - A modern replacement for 'ls' with icons and colors. (Rust)
- [genact](https://github.com/svenstaro/genact) - A nonsense activity generator. (Rust)
- [Lolcat](https://github.com/busyloop/lolcat) - Rainbows and unicorns. (ruby)
- [mpv](https://github.com/mpv-player/mpv) - Command Line Media Player
- [musikcube](https://github.com/clangen/musikcube) - a cross-platform, terminal-based music player. (C++)
- [No-More-Secrets](https://github.com/bartobri/no-more-secrets) - A command line tool that recreates the famous data decryption effect. (C)
- [pywal](https://github.com/dylanaraps/pywal) - Generate and change color-schemes on the fly. (python)
- [Themer](https://github.com/mjswensen/themer) - themer takes a set of colors and generates themes for your apps. (javascript)
- [tdrop](https://github.com/noctuid/tdrop) - A glorified WM-independent dropdown creator. (Shell)

#### Informative

- [Getnews.tech](https://github.com/omgimanerd/getnews.tech) - A web server that fetches data from the News API and formats it for display in the terminal. (javascript)
- [Howdoi](https://github.com/gleitz/howdoi) - instant coding answers via the command line. (python)
- [Wtf](https://github.com/wtfutil/wtf) - The personal information dashboard for your terminal. (go)
- [Wttr](https://github.com/chubin/wttr.in) - The right way to check the weather on terminal. (python)
- [Wego](https://github.com/schachmat/wego) - Another weather app for terminal with cool ascii art. (go)

---

### Colorschemes

- [base16-builder](https://github.com/base16-builder/base16-builder) - nimble command-line tool that generates themes for your favourite programs.
- [base16 family](https://github.com/chriskempson/base16) - a collection of multiple color-schemes.
- [bash-full-of-colors](https://github.com/slomkowski/bash-full-of-colors) - Advanced .bashrc and .bash_profile coming together with colorful output
- [Dracula](https://github.com/dracula/dracula-theme) - A Dark theme for all the things!.
- [everforest](https://github.com/sainnhe/everforest) - Comfortable & Pleasant Color Scheme.
- [Flatui](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Flat UI colors for Terminal and iTerm.
- [geometry](https://github.com/geometry-zsh/geometry) - a minimal, fully customizable and composable zsh prompt theme
- [Gogh](https://github.com/Mayccoll/Gogh) - Color Scheme for Gnome Terminal and Pantheon Terminal
- [gruvbox](https://github.com/morhetz/gruvbox-contrib) - Retro groove color scheme.
- [Nord](https://github.com/arcticicestudio/nord) - An arctic, north-bluish color palette.
- [OneDark](https://github.com/nathanbuchar/atom-one-dark-terminal) - Atom One Dark theme for Terminal
- [rainglow](https://github.com/rainglow) - A collection of over 320 different color themes for various terminals and editors.
- [rose-pine](https://github.com/rose-pine/rose-pine-theme) - All natural pine, faux fur and a bit of soho vibes for the classy minimalist.
- [tokyo-night](https://github.com/ghifarit53/tokyonight-vim) - A clean, dark colorscheme that celebrates the lights of downtown Tokyo at night.
- [UwU](https://github.com/Mangeshrex/uwu.vim) - A dark and independent colorscheme purrying >,<

#### colorscheme-generators

- [oomox](https://github.com/themix-project/oomox) - Graphical application for generating different color variations of a Materia and Oomox themes (GTK2, GTK3 and others). (python)
- [wpgtk](https://github.com/deviantfero/wpgtk) - a colorscheme, wallpaper and template manager for \*nix. (python)

---

### Shells

- [Ammonite](https://github.com/com-lihaoyi/Ammonite) - Scripting with Scala. (scala)
- [Bash](https://www.gnu.org/software/bash/) - Well known GNU Bourne Again SHell. (C)
- [Dash](http://gondor.apana.org.au/~herbert/dash/) - POSIX-compliant implementation of /bin/sh that aims to be as small as possible. (C)
- [Elvish](https://github.com/elves/elvish) - Expressive Programming Language + Versatile Interactive Shell. (Go)
- [Es](https://github.com/wryun/es-shell) - a shell with higher-order functions. (C)
- [Fish](https://github.com/fish-shell/fish-shell) - The user-friendly command line shell. (C++)
- [gosh](https://github.com/cezarmathe/gosh) - primitive shell. (go)
- [gsh](https://github.com/AdaCore/gsh) - A POSIX shell for Windows. (C, ada)
- [Hilbish](https://github.com/Hilbis/Hilbish) - a nice lil shell for lua people made with go and lua. (go)
- [Ion](https://github.com/redox-os/ion) - modern system shell that features a simple, yet powerful, syntax. (Rust)
- [Jsh](https://github.com/jovanbulck/jsh) - A basic UNIX shell implementation. (C)
- [ksh93](https://github.com/att/ast) - Korn Shell. (C)
- [Mish](https://github.com/hoomanist/mish) - minimalistic shell. (C)
- [Mksh](https://github.com/MirBSD/mksh) - MirBSD Korn Shell. (C)
- [Murex](https://github.com/lmorg/murex) - Bash-like $SHELL designed for greater commandline productivity and safer shell scripts. (go)
- [Mrsh](https://github.com/emersion/mrsh) - A minimal POSIX shell. (C)
- [Nash](https://github.com/madlambda/nash) - a shell inspired by plan9 rc. (go)
- [Nushell](https://github.com/nushell/nushell) - A new type of modern shell. (Rust)
- [Nsh](https://github.com/nuta/nsh) - command-line shell like fish, but POSIX compatible. (rust)
- [Oksh](https://github.com/ibara/oksh) - Portable OpenBSD ksh, based on the Public Domain Korn Shell. (C)
- [Oh](https://github.com/michaelmacinnis/oh) - A new Unix shell. (go)
- [Oil](https://github.com/oilshell/oil) - A Bash compatible, with modern Unix shell. (Python)
- [pdksh](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/bin/ksh/) - Public Domain Korn Shell. (C)
- [Powershell](https://github.com/PowerShell/PowerShell) - A cross platform shell for automation and configuration. (C#)
- [rc](http://doc.cat-v.org/plan_9/4th_edition/papers/rc) - plan 9 shell. (C)
- [sesh](https://github.com/anaskhan96/sesh)- a very simple elegant shell. (go)
- [shirt](https://github.com/jstorimer/shirt) - SHell In Ruby? Totally! (ruby)
- [Shell++](https://github.com/alexst07/shell-plus-plus) - (C++)
- [tcsh](https://www.tcsh.org/) - C shell with file name completion and command line editing. (C)
- [ubsh](https://github.com/ks0n/ubsh) - UnBloated (or Undefined Behavior...) shell. A small and lightweight non-POSIX shell. (C)
- [Xiki](https://github.com/trogdoro/xiki) - a shell console with gui features. (ruby)
- [Xonsh](https://github.com/xonsh/xonsh) - Python-powered, cross-platform, Unix-gazing shell. (Python)
- [Yash](https://yash.osdn.jp/) - yet another shell is a POSIX shell with features like Global aliases, arrays, socket etc. (C)
- [Zsh](http://zsh.sourceforge.net/) - Z-shell for power users. (C)

### Prompts

- [angel-PS1](https://github.com/dolmen/angel-PS1) - Your fancy shell prompt fed by your guardian angel. (perl)
- [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - An informative and fancy bash prompt for Git users
- [bash-powerline](https://github.com/riobard/bash-powerline) - Powerline-style Bash prompt in pure Bash script.
- [bashed-on-a-feeling](https://github.com/yedhink/bashed-on-a-feeling) - fast and minimalistic git prompt written in bash
- [bronze](https://github.com/reujab/bronze) - A cross-shell customizable powerline-like prompt with icons. (go)
- [candypaint](https://github.com/anxiousmodernman/candypaint) - candy coated prompts for the ion shell. (rust)
- [emojify](https://github.com/mrowa44/emojify) - Emoji on the command line.
- [git-prompt](https://github.com/lvv/git-prompt) - bash prompt with GIT, SVN and HG modules
- [Hydro](https://github.com/jorgebucaran/hydro) - Minimal, lag-free prompt with async Git status.
- [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & Zsh
- [MiniPrompt](https://github.com/kdav5758/MiniPrompt) - Minimalist Prompt, a decluttered and lightning fast, yet, feature rich, bash prompt!
- [Mooji](https://github.com/rodrigobdz/mooji) - Minimal, informative and fast fish prompt
- [Mshp](https://github.com/nn1ks/mshp) - Minimal and fast prompt. (rust)
- [Pokemon](https://github.com/LazoCoder/Pokemon-Terminal) - Pokemon terminal themes
- [polygot](https://github.com/agkozak/polyglot) - Color, ASCII-only Git prompt for zsh, bash, ksh93, mksh, pdksh, dash, and busybox ash.
- [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Legacy prompt for ZSH
- [Powerlevel10k](https://github.com/romkatv/powerlevel10k) - A Zsh theme revolves around customization and speed
- [Powerline](https://github.com/b-ryan/powerline-shell) - A beautiful and useful prompt for your shell. (python)
- [Powerline-rust](https://github.com/cirho/powerline-rust) - powerline-shell written in Rust
- [Pure](https://github.com/sindresorhus/pure) - Pretty, minimal and fast ZSH prompt
- [Purer](https://github.com/DFurnes/purer) - Single-line ZSH prompt, based on "Pure".
- [Promptus](https://github.com/willeccles/promptus) - Very quick shell prompt that supports multiple shells. (C)
- [robbyrussell](https://github.com/denysdovhan/robbyrussell-node) - Cross-shell robbyrussell theme written in JavaScript
- [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) - Bash prompt with colors, git statuses, and git branches.
- [silver](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt with icons. (rust)
- [shellby](https://github.com/athul/shelby) - Shelby is a fast zap , lightweight ,minimal shell prompt. (go)
- [Spaceship](https://github.com/denysdovhan/spaceship-prompt) - A Zsh prompt for Astronauts
- [Starship](https://github.com/starship/starship) - The minimal, blazing-fast, and infinitely customizable prompt for any shell! 
- [Synth-shell](https://github.com/andresgongora/synth-shell) - improves your terminal experience and productivity through a combination of small bash scripts
- [Tide](https://github.com/IlanCosman/tide) - A modern prompt manager for Fish.
- [wish](https://gitlab.com/ceda_ei/wish) - A customizable, extensible, themable bash prompt

---

### Background setting utilities and generators

- [auto_background_changer](https://github.com/AlvinJian/auto_background_changer) - A simple wallpaper changer supporting various desktop environments and window managers for Linux. (python)
- [azote](https://github.com/nwg-piotr/azote) - Wallpaper and colour manager for Sway, i3 and some other WMs. (python)
- [BashDynamicPaper](https://github.com/wtheisen/BashDynamicPaper) - Dynamic wallpaper setter.(shell)
- [battery-wallpaper](https://github.com/adi1090x/battery-wallpaper) - Simple bash script to set wallpaper according to battery percentage with charging animations. (shell)
- [bing-desktop-wallpaper-changer](https://github.com/UtkarshGpta/bing-desktop-wallpaper-changer) - Automatically changes desktop wallpaper to Bing Photo of the Day for Linux with Gnome. (shell) !!
- [canvas](https://github.com/adi1090x/canvas) - A Gradient / Blured Wallpaper Generator And Setter. (shell)
- [chwall](https://git.umaneti.net/chwall/about/) - tiny automatic wallpaper changer. (python)
- [dynamic-wallpaper](https://github.com/adi1090x/dynamic-wallpaper) - A simple bash script to set wallpapers according to current time, using cron job scheduler .(shell)
- [fbsetbg](https://github.com/hboetes/fbsetbg) - Set your wallpaper with the best available application. (C)
- [komorebi](https://github.com/cheesecakeufo/komorebi) - A beautiful and customizable wallpapers manager for Linux. (vala)
- [lean](https://github.com/vineetred/flowy) - A lean, privacy-preserving dynamic wallpaper changer. (rust)
- [izulu](https://github.com/onli/izulu) - weather-aware desktop background images. (shell)
- [feh](https://github.com/derf/feh) - a fast and light image viewer / setter. (C)
- [Nitrogen](https://github.com/l3ib/nitrogen) - Background browser and setter for X windows. (c++)
- [Nathans-wallpaper](https://github.com/step-/nathans-wallpaper) - Desktop wallpaper setter. (shell)
- [quickwall](https://github.com/deepjyoti30/QuickWall) - Set latest wallpapers from Unsplash from the commandline. (python)
- [setroot](https://github.com/ttzhou/setroot) - simple X background setter inspired by imlibsetroot and feh. (C)
- [Unsplash-Random-Wallpaper-Setter](https://github.com/tymscar/Unsplash-Random-Wallpaper-Setter) - simple script that changes your wallpaper to a random image from unsplash.it (shell)
- [Vallpaper](https://github.com/lehklu/Vallpaper) - Plasma5 wallpaper for different desktops. (QML)
- [xwallpaper](https://github.com/stoeckmann/xwallpaper) - wallpaper setting utility for X . (C)
- [xwinwrapl](https://github.com/ujjwal96/xwinwrap) - My fork of xwinwrap. Xwinwrap allows you to stick most of the apps to your desktop background. (C)
- [wallpaper-generator](https://github.com/timozattol/wallpaper-generator) - A simple wallpaper generator. (python)
- [wallset](https://github.com/terroo/wallset) - A wallpaper manager that makes it possible to put videos as wallpaper. (shell)
- [wallsetter](https://github.com/Creator54/wallsetter) - A live wallpaper setter for linux. (shell)

### resources (websites)

- [Alpha Coders](https://www.alphacoders.com/) - A site with wallapapers, art, gifs, and a lot of other interesting media.
- [UnSplash](https://unsplash.com/) - Website with thousands for freely-usable images.
- [SimpleDesktops](http://simpledesktops.com/) - Wallpaper site specfically for Miniamal and Simple Wallpapers.
- [wallhaven](https://wallhaven.cc) - Massive walpaper website with an active comminuty.
- [Wallpaper Cave](https://wallpapercave.com) - Wallpaper site with a larger focus on user-submitted categories for wallpapers.

### Other

- [ArchWiki](https://wiki.archlinux.org/) - The Bible of linux configuration/resources.
- [Guide to Switching to Ubuntu on Reddit](https://www.reddit.com/r/linux4noobs/comments/ejsz3v/still_on_windows_7_dont_want_windows_10_consider/) - A Beginner-frendly guide on how to switch to Ubuntu as a Daily Driver.

## Communities

### Reddit

- [r/findmeadistro](https://www.reddit.com/r/FindMeADistro/) - The Distro-hunting Subreddit.
- [r/linux4noobs](https://www.reddit.com/r/linux4noobs) - A community for those new to the Linux Operating System. The Wiki contains a wealth of information for new users to get started in Linux.
- [r/unixporn](https://www.reddit.com/r/unixporn/) - A coumminty all about Ricing up Linux.
- [r/terminal_porn](https://www.reddit.com/r/terminal_porn/) - The unixporn of terminals.

### Ricing related public groups

- [r/unixporn Discord](https://discord.com/invite/unixporn) - The official r/unixporn Discord server.
- [DE_WM](https://t.me/DE_WM) - Friendly Ricing community on telegram.
- [dotfiles_IN](https://t.me/dotfiles_id) - Dotfiles Indonesia ( not EN ).
- [r/unixporn tg](https://t.me/joinchat/BQ8MHUbhQXRlB4d4MzxgOA) - r/unixporn telegram group.

## TODO:

- More color palette
- Add wallpaper sources
- Add Resources(Tutorials and Articles)
- Add More Resources

## Related lists

- [terminals are sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list of Terminal frameworks, plugins & resources for CLI lovers.

**[⬆ back to top](#table-of-contents)**

## Contributing

Your contributions are always welcome! Please take a look at our [contribution guidelines](https://github.com/Sparkenstein/awesome-ricing/blob/master/contributing.md) and [code of conduct](https://github.com/Sparkenstein/awesome-ricing/blob/master/code-of-conduct.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sparkenstein](https://github.com/Sparkenstein) has waived all copyright and related or neighboring rights to this work.

<div align="center"> Made with ❤️  by the community </div>
