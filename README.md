# Windows 10 Transformation Theme for Raspberry Pi OS

## Description
Make Raspberry Pi OS look as close to Windows 10 as possible. Installs an ``icon theme``, ``GTK theme``, ``bash mouse cursor``, ``openbox theme``, ``xcompmgr``, and ``custom panel``.
(Will soon get the [Windows 11](https://insider.windows.com/en-us/register) Update.)

[![badge](https://github.com/Botspot/pi-apps/blob/master/icons/badge.png?raw=true)](https://github.com/Botspot/pi-apps)

## The Story
This theme was originally designed by Botspot to change the look and feel of your Raspberry Pi OS but I redesigned it to intergrate more with your RaspiOS.

### To download:
```bash
git clone https://github.com/C-EO/Windows-10-Remastered.git
```
### To install:
```bash
/home/pi/Windows-10-Remastered/install
```
### To uninstall:
```bash
/home/pi/Windows-10-Remastered/uninstall
sudo apt purge xcompmgr gtk2-engines-murrine tint2 -y
```


## Contributing:
If you're looking forward to contribute to this project, please fork it, or download & edit its code, or even ask for Contributor permmissions to contribute to it.


## Support
If you need any help with the theme, please open an [issue](https://github.com/C-EO/Windows-10-Remastered/issues).


## Authors and acknowledgment
This project has been made possible by: [@C-EO](https://github.com/C-EO)

Other contributors who have sacrificed there time for its development are:


## License
This project uses the [GNU General Public License v3.0 (GPLv3)](https://gnu.org).
Do not redistribute any piece of this software (or software itself) without the license.
To obtain a copy of the license, please visit [GNU General Public License v3.0 (GPLv3)](https://gnu.org)


## Credit:
The icon theme is originally from the [B00merang project](https://github.com/B00merang-Artwork/Windows-10). Customizations were added by the [TwisterOS](https://twisteros.com) team. [Botspot](https://github.com/Botspot) further customized the icon theme to be compatible with Raspbian but [C-EO](https://github.com/C-EO) gave it this nice new look.

The ``GTK theme`` is based on the B00merang project. Botspot heavily modified it to work best with Raspbian. 
The mouse cursor theme is non-modified  Windows 8.1 mouse cursor theme, gotten from here.
The openbox theme was designed from scratch by Botspot and remastered by C-EO.
``Xcompmgr`` adds transparency and shadows to windows. Non-modified.
The '``custom panel``' is actually two panels, one over the other. The lower one is ``lxpanel``, and C-EO re-designed the entire theme from Botspot's original theme. The upper one is ``tint2``, and Botspot designed all the taskbar elements from scratch. This double-panel approach is necessary to better mimic Windows 10. No other Windows 10 theme for any Linux OS is as realistic as this theme.


## Project status
This project's development has slowed done due to problems arising with trying to intergrate it with other Linux Operating Systems. 
We deeply apologize if we have in any way inconvinienced you.
