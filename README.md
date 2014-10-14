UDB-WoD (Unified Database: Warlords of Draenor) for CMaNGOS-WoD
===============================================================
A Content Database for [CMaNGOS-WoD][1], and *World of Warcraft Client Patch
6.x.x* - It Is Compatible Only With Client 6.x.x (build XXXXX)

**UDB-WoD** is released under the GPL v2.  The file (`LICENSE.mdown`)
**must** be a part of any re-distributable packages made from this software.  No
licenses should be removed from this software if you are making re-distributable
copies.

Compatibility
-------------
The *UDB-WoD* database is compatible with [CMaNGOS-WoD][1] core only.

Getting started
---------------
The basic principle behind this database repository is to have a single SQL file
holding every table in the database. When something is changed into the database
the modification is done by adding small SQL update files placed into the `updates` directory.
Every time a user (that would be you or UDB Developers) wishes to change something into the database, he/she
have to create and add the right SQL file. This helps tracking what changes are made, when and where.

Installation
------------
**UDB-WoD** is the main content database for: `mangos` where the world is defined
with creatures, items, objects, quests, etc.

It must be applied after creating the `mangos` database from your CMaNGOS core distribution [CMaNGOS-WoD][1] from [CMaNGOS Project][2].

For Easy Installation Edit The Following Windows Batch File `./Windows_Install_Script.bat` if you are a Windows User and configure
the Installation Options Setting Your MYSQL Database Names, Passwords and Source Folders.

It will provide you a Menu With Various Installation Options and Configurations That Have Greatly Simplified The Process.

For a full installation guide, please refer to [CMaNGOS installation instructions][3].

And if something goes wrong?
----------------------------
The best way to submit an issue is to use the [Issue Tracker:][4].


[1]: https://github.com/cmangos "CMaNGOS-WoD Project"
[2]: https://github.com/cmangos "CMaNGOS Project"
[3]: https://github.com/cmangos/issues/wiki/Installation-Instructions "CMaNGOS installation instructions"
[4]: https://github.com/cmangos/issues "CMaNGOS Issue Tracker"
