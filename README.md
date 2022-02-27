# Automated installation of Python and GDAL

This repository contains the script for automated download, installation and set-up of Python and GDAL. The details are mentioned in a Medium post titled [**Python and GDAL Installation Automated for Windows 10**](https://towardsdatascience.com/python-and-gdal-installation-automated-for-windows-10-f22686595447).<br/>

Please take care of the following three things while using the script:<br/>
1. Download the relevant version, i.e. 32-bit or 64-bit depending on your system. <br/>
2. Run the .bat file with administrative privilege. <br/>
3. Shorten the Python installation directory to "C:\Python37". <br/>

## YouTube tutorial: [link1](https://www.youtube.com/watch?v=kVoWcBRPVKI) [link2](https://youtu.be/1G2tkMaoS8Q)

If you are facing issues in using this, please check the [debugger](debugger) section. If your error is not listed, please crate a GitHub issue with conceise title and all the relevant details.

## Fixing "ModuleNotFoundError: No module named '\_gdal'"
On some machines, you may get this error after running the whole thing. Do not worry, you are almost there. Follow 2-3 extra steps mentioned [here](./debugger) and your installation would successfully complete.
