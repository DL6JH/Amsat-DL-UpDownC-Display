/*<br>
* **Amsat-DL Up -and Down-Converter Display for Windows, macOS, Linux and Raspberry Pi**<br>
* =========================================================================<br>
* Author: (c) **DL6JH**<br>
*<br>
*   This program is free software; you can redistribute it and/or modify<br>
*   it under the terms of the GNU General Public License as published by<br>
*   the Free Software Foundation; either version 2 of the License, or<br>
*   (at your option) any later version.<br>
*<br>
*   This program is distributed in the hope that it will be useful,<br>
*   but WITHOUT ANY WARRANTY; without even the implied warranty of<br>
*   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the<br>
*   GNU General Public License for more details.<br>
*<br>
*   You should have received a copy of the GNU General Public License<br>
*   along with this program; if not, write to the Free Software<br>
*   Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.<br>
* <br>
*/

## Function

Show information of the Amsat-DL UpConverter and DownConverter in a window running on Windows, macOS, Linux or Raspberry Pi.

## Software Requirements

**Windows**<br>
32-bit and 64-bit versions of Windows are supported.<br>
Windows 10<br>
Windows 8.1<br>
Windows 7 SP11<br>

**macOS**<br>
macOS Catalina 10.15.x<br>
macOS Mojave 10.14.x<br>
macOS High Sierra 10.13.x<br>
macOS Sierra 10.12.x<br>
OS X El Capitan 10.11.x<br>
OS X Yosemite 10.10.5<br>

**Linux**<br>
32-bit and 64-bit versions of Linux are supported.<br>
Linux Mint 16 or later<br>
CentOS 7.0 or later<br>
Ubuntu 14.04 LTS or later<br>
Debian 6.0 or later<br>
OpenSUSE 11.3 or later<br>
Fedora 13 Desktop or later<br>

**Raspberry PI**<br>
Pi 2, 3 and 4 running:<br>
Raspbian Jessie<br>
Raspbian Jessie with Pixel<br>
Raspbian Stretch<br>
libunwind8 library<br>

## Hardware Requirements

Use one or two Serial/USB converter with 3.3V level. A cheap CP210x Chip will do the job.<br>
9600 Baud and 8N1 is used by the Up -and Down-Converter.<br><br>
*Note: Do not use a normal RS232 to USB adapter, it will not work.*<br><br>
You have the choice to use only one serial connection as proposed by Amsat. In this case the messages of the DownConverter are looped through the UpConverter. But no debug messages of the DownConverter will be seen, they are suppressed by the UpConverter.<br>
If you want to see all messages, you can use two serial connections instead, one for the UpConverter, and one for the DownConverter.<br>
This is especially useful for setup or debugging the equipment.

## Supported Boards
Amsat-DL UpConverter6W, V4.2 or V4.3.<br>
Amsat-DL DownConverter V3d<br>
Other board versions may also work, but are not tested.

## Software installation

There is no need to install the software. Unzip the file and all its subdirectories to a folder of your choice (e.g. „programs“ or USB-stick) and run the executable.<br>
Please don't touch the structure of the subdirectories and files, take it as it is. Of course you may define an Alias of the executable as you like.<br>
On exit, size/position of the window and the actual settings are preserved.

## Program Manual...

…doesn’t exist. The Program is self explanatory. Please move the mouse cursor over the desired item, wait 1 second and read the tool tip.

*73 de DL6JH*<br>


