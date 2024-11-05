New version Doload:
	http://www.yfvb.com/soft-48.htm
	https://yfvb.lanzouj.com/iwMXj2ed8foh
All Version DownLoad: https://yfvb.lanzoui.com/b01hid90j

BBS>: VFB IDE - freebasic.net
https://www.freebasic.net/forum/viewtopic.php?t=28522
==============================	

5.9.3
Correction: When software generated from a Chinese system is transferred to a non-Chinese system, App.Comments and other Chinese characters will print out garbled characters.
Improve the MyDrawWin control to add window menu display and related properties.
Added TrayIco control to add icon handle setting properties
Adjusted the text length limit for comments, descriptions, etc. in project properties to a maximum of 99 characters. Since it affects controls and plug-ins, all need to be updated
Added a help link to all control properties. Click to open the programming documentation for this control.
Update Spark Editor DLL updated to version 4.4, the original is version 4.0
Modification Change mb browser to IE browser to display help. The display is not normal under XP system (who still uses XP now) so that there is no need to bring dozens of MB mb.dll files.
Change: When creating a code window when opening a project, add a delay to avoid sometimes being unable to react and obtain control handles (especially when VFB is opened for the first time after booting and automatically loads many projects), causing some code windows to be uncontrollable.
New wide character dynamic variable length type StringW is added to replace CWSTR and related functions. (Mainly rely on the CW library to prepare for cross-platform)
Improvement: After compiling a control or plug-in, you will be asked to restart first. After selecting No, you will no longer be prompted to restart again after compiling.
New: When compiling errors or warnings, a small dot will be displayed on the compilation label.
Fixed the problem that after closing a project, it automatically switches to the previous project, but the compilation log shows that there is no switch.
Fixed keywords that should not be displayed in my code base such as prompts for class members.
Fix: When a file in my code library is opened and VFB is reopened, the code library will not be displayed in the library list.
Improvement: Expanding "My Code Library" for the first time in the library list will be slower, especially when there are many libraries. The expansion method has been optimized and can be expanded instantly.
Adjustments: Cancel the component manager, start VFB and no longer check for component updates.
Fixed the issue where all tool buttons in the function list are invalid
