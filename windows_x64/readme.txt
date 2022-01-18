Windows 10 x64 rtl_433 Binary
-----------------------------

After searching for a precompiled windows binary for rtl_433 and discovering the newest version I could find online was 3 years old and didn't seem to work properly I decided to compile my own and share it here for anyone likewise searching for an up to date binary who doesn't have the inclination to compile it themselves.

This version of rtl_433 is from Git commit 32c1f4a65fd238be70dee4af7ef8c58cec7af554 branch master, from Mon Jan 10 18:07:31 2022.

It was compiled with Visual Studio 2022 targetting Windows 10 x64 and requires the provided libusb-1.0.dll and rtlsdr.dll to be present in the same directory as rtl_433.exe.

The latest January 29 2020 version of librtlsdr from https://github.com/winterrace/librtlsdr was used and the latest version of libusb-1.0 has also been used which is compatible with USB3 ports, unlike some older versions of this library which only seem to work with a device connected to a USB2 port.

It has only been tested with an RTL-SDR.COM V3 adaptor on Windows 10 x64, so please use at your own risk.
---------------------------------------------------------------------------------------------------------

Simon Byrnand
