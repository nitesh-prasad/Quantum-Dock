# 🌌 QUANTUM DOCK for Rainmeter

Introducing Quantum Dock for Rainmeter. The most customizable, light-weight feature feature-rich dock for Windows PC.

![Windows](https://img.shields.io/badge/Windows-117DD1?style=for-the-badge&logo=windows) ![Rainmeter](https://img.shields.io/badge/Rainmeter-4.5%20or%20greater-009B72?style=for-the-badge&logo=Rainmeter) [![Downloads](https://img.shields.io/github/downloads/nitesh-prasad/Quantum-Dock/total?style=for-the-badge)](https://niteshprasad.gumroad.com/l/quantum-dock) 

![Quantum Dock](https://blogger.googleusercontent.com/img/a/AVvXsEh3GAvXppOA24ca1B6Nz8SHjI_yRp1DA59R77WEGYkNfcKHYmf_FYyK4yyQzUcut8eJh3EJVWAX9UwvZOvFGRoYEr6kTAHFWONNbBsvXzFOpR6t8snRF9-uEEEGkOLvEYvz8tal50OpolxhU2pQbABfIl68JdrcZbUnhJC0iV2HOKRsH_uJ70gmrd9V8w=s16000)

Best dock/launcher skin for Rainmeter. Lightweight with modern design. Highly customizable.

🌐 Official Product Page: <https://www.osbusters.net/2022/02/quantum-dock-rainmeter.html>

[![YouTube](https://img.shields.io/badge/osbusters-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/osbusters) [![Twitter](https://img.shields.io/badge/osbustersblog-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/osbustersblog) [![Instagram](https://img.shields.io/badge/osbustersblog-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/osbustersblog)

## Download

Download the full version of **Quantum Dock**:

[![Download](https://img.shields.io/badge/Free-DOWNLOAD-brightgreen?style=for-the-badge&logo=gumroad)](https://niteshprasad.gumroad.com/l/quantum-dock)



## Features of Quantum Dock
- Modern Design
- Multiple customization options
- Horizontal and Vertical modes
- Horizontal and Vertical Gaps
- Change padding of the dock
- Customize Icon Size and Icon Angle
- 60+ preloaded icons
- Gradient/Normal/Transparent background with support for custom colors
- Customizable gradient angle and background opacity
- Add remove entries easily
- Comprehensive documentation and guide

![Quantum Docks Icons](https://blogger.googleusercontent.com/img/a/AVvXsEgNzt3DoufW0upmg_axjjX-QlFTysiGmbDI2Pt9gq0w6yyo5QZzd6GSJx1RH-38a8Utjngd1i_Lw5us57-S4lYE71VKW0n1JBs4N69ZL0vYXRuuX9-WyY12rAysrCj8loouDYiOfZ0-t5E9AVZw3WlcGAza9ThEG145qv46VWG_DXEKxVoMBWTF9z-fJw=s16000)

## How to Customise Quantum Dock?

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/a/AVvXsEj0nE_oNsWNcY8weKpnBbvArJIa6PK-d88Vv7QveuVNAsUcbcmDV2ANN9XyGRnH-gQpVQXEt-Tcpqnyyf1exYXNUx6_4Q556bRkgFvNLFKGtzk7JT6WoQTE8t9UP2Pou5GOaNaMXtLWPylYN1KntxacfkJdur4vO0W3QLdul4KoUghN-pbo5deRzXI_cA=w640-h355" />
</p>

The skin consists of icons. Each icon uses the following structure:
```
[NAME]

Meter=Image

MeterStyle=Style

ImageName="ICON"

LeftMouseDoubleClickAction=[ACTION]

MouseOverAction=[!SetOption #CURRENTSECTION# ImageName "ICON HOVER"][!UpdateMeter #CURRENTSECTION#][!Redraw]

MouseLeaveAction=[!SetOption #CURRENTSECTION# ImageName "ICON"][!UpdateMeter #CURRENTSECTION#][!Redraw]
```


***Explanation:***

**NAME:** Unique name of the meter. (It shouldn't be used again in the file!)

**ACTION:** What should happen when the user clicks on the icon.

**ICON:** Standard icon location. (Valid file types: png, jpg, bmp, gif, tif, ico)

**ICON HOVER:** Hover icon location.

---

After editing the skin, right-click on it and choose "Refresh" for the modifications to take action!

To edit the skin's settings, right-click on it and choose "Settings..."!

You can find some preset icons located in "Quantum Dock\@Resources\Images"!



### Some examples of [ACTION] :



- To open a webpage : ["https://www.google.com"]
- To start an application : ["C:\Program Files\Blender Foundation\Blender 3.0\blender-launcher.exe"]
- Start windows settings : ["ms-settings:home"]  (for more info: <https://forum.rainmeter.net/viewtopic.php?t=22613>)
- Control Panel: ["Control"]
- This PC/ My Computer : [Shell:::{20D04FE0-3AEA-1069-A2D8-08002B30309D}]
- Recycle Bin : [Shell:::{645FF040-5081-101B-9F08-00AA002F954E}]
- Downloads : [Shell:::{374DE290-123F-4565-9164-39C4925E467B}]
- Documents : [Shell:::{A8CDFF1C-4878-43be-B5FD-F8091C1C60D0}]
- Pictures : [Shell:::{3ADD1653-EB32-4cb0-BBD7-DFA0ABB5ACCA}]
- Music : [Shell:::{1CF1260C-4DD0-4ebb-811F-33C572699FDE}]


For more codes visit: <https://docs.rainmeter.net/tips/launching-windows-special-folders/>

---
### Developer Information
- **Developer :** Nitesh Prasad
- **Website :** <https://www.osbusters.net/>
- **DeviantArt :** <https://www.deviantart.com/nitesh-prasad>

---
### Credits
Special thanks to Baleg00 for [Material Taskbar](https://www.deviantart.com/baleg00/art/Material-Taskbar-1-0-675421086)

Special thanks to @Kaelri for [RainRGB](https://github.com/Kaelri/Enigma/tree/master/Skins/Enigma/@Resources/Addons/RainRGB)


## 📷 Screenshots

![Quantum Dock Screenshot 1](https://blogger.googleusercontent.com/img/a/AVvXsEgLHo5oFCuI9nniIl4ihVc7BiKy_vM7bvN5hH0SB3UyRK6JNDeGKAzrDxiOCNrpzS9vNQt_1bm3-tBNNxh6XP_p9s43QF-8iCWRtExTzhTYWE0VY3jXHmhjBVLzgMgEiZxgMkDsAHjoxQ5W4-vIQlt88CEOJoxnIfK0vOKJjRmjTXGHhS8CCftxr0sITQ=s16000)
![Quantum Dock Screenshot 2](https://blogger.googleusercontent.com/img/a/AVvXsEgmTLHteuuFx3Ju61AxmfwnHgEec2kgHoNJSi-u9fRiudiwP8K-Y1_62JJi_LiL_WgKL6Uf8Ftl_384kWFNa-HZ_VV7zOc2soPFaiE2FkHJCuKDgIAsZ4nzwFdPsiPFLgDjmfd6_Ug20NdW5LgD40inTLZ7tHltF7MmmahjJbFm7cJX3F1sAnAbPaiXkw=s16000)
![Quantum Dock Screenshot 3](https://blogger.googleusercontent.com/img/a/AVvXsEi-vkFMSdjyEeUAqneJ0mXsF2L3wpGgbfKjj7g7QBHPGXFkybg6JSdsybJSCrhIOEgDeJZ5H8w3HQB8YtvPbk2KnTTXuP-NtbDAzbh5czs7oXB6qjco856eThd1j7FKkdjUtjUCmslXfv3ye5FFiBclZoEeJdlsj6zuw2j6cvWRUbqMm-X1paECDdWVlw=s16000)
![Quantum Dock Screenshot 4](https://blogger.googleusercontent.com/img/a/AVvXsEj3blzJJbFVnxTKV5dGQRkh0eWY9eCoZiA--pMjXnbUqwqkMjbVT24ix4PmI_U3KHW2dG8OiWwlAzNnFLgOIrAlKxOSxjCqDz0UkBBgASHpnFIFb6GYH5rZdydS1i66hTR8C4zIJGl_QGE3B2m1NHmamNOX2AL0CGonkU-opWSZIrc7F2tk66oGbXtG-A=s16000)