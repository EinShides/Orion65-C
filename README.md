A 65% keyboard PCB that supports standard and arrow key blocker layouts (such as the kbd67) and stepped caps lock. The PCB also features a flex cut for a softer typing experience. Uses USB type C and has a ESD protection diode. PCB is tested and working. A matching case model can be found here via the fusion 360 link: https://a360.co/2X7CGb7 (Though there is a name engraving for myself in the top right that needs to be changed if you don't want it).

![alt text](https://github.com/EinShides/Orion65-C/blob/main/PCB%20Renders/Front.png?raw=true)
![alt text](https://github.com/EinShides/Orion65-C/blob/main/PCB%20Renders/Back.png?raw=true)
![alt text](https://github.com/EinShides/Orion65-C/blob/main/PCB%20Renders/build.jpg?raw=true)


Application: KiCad
Version: (5.1.5)-3, release build
Libraries:
    wxWidgets 3.0.4
    libcurl/7.66.0 OpenSSL/1.1.1d (Schannel) zlib/1.2.11 brotli/1.0.7 libidn2/2.2.0 libpsl/0.21.0 (+libidn2/2.1.1) nghttp2/1.39.2
Platform: Windows 8 (build 9200), 64-bit edition, 64 bit, Little endian, wxMSW
Build Info:
    wxWidgets: 3.0.4 (wchar_t,wx containers,compatible with 2.8)
    Boost: 1.71.0
    OpenCASCADE Community Edition: 6.9.1
    Curl: 7.66.0
    Compiler: GCC 9.2.0 with C++ ABI 1013

Build settings:
    USE_WX_GRAPHICS_CONTEXT=OFF
    USE_WX_OVERLAY=OFF
    KICAD_SCRIPTING=ON
    KICAD_SCRIPTING_MODULES=ON
    KICAD_SCRIPTING_PYTHON3=OFF
    KICAD_SCRIPTING_WXPYTHON=ON
    KICAD_SCRIPTING_WXPYTHON_PHOENIX=OFF
    KICAD_SCRIPTING_ACTION_MENU=ON
    BUILD_GITHUB_PLUGIN=ON
    KICAD_USE_OCE=ON
    KICAD_USE_OCC=OFF
    KICAD_SPICE=ON
