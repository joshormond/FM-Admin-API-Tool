FM-Admin API Tool
=================

Updated version for FileMaker 18! This replaces the older version that worked with FileMaker 17.

This file is presented as a learning tool for:

    1. Working with REST APIs from FileMaker Pro
    2. Working with the Admin API in FileMaker Server 18

The file is very much a work in progress, so you can use as a foundation to build your own solutions to administer your FileMaker Servers. 

This is provided as-is with no warranties, and it is up to you to add any needed security to your own files.

To use, create a new record and add your server URL, not including "http://" or "https://" and trailing ":16000/" at the end. In the "Authentication" panel, enter the username and password for a valid admin account for your FileMaker Server.

Once you have logged in, you can check status and manage your server, including changing several settings not available in the web based Admin Console, such as setting the cache size.

Scripts have been laid out to match the Admin API Docs, so you can follow along by reading through the server documentation.

Use the "Debug" popover in the lower right to view JSON responses and HTTP Headers returned from the server.

Updated to support managing more than one server. Added scripting and buttons to open, close, pause and resume databases. Added support for managing connected clients, send messages and disconnect.

Updated to work with v2 for FM 18, including multiple web publishing worker machines.

Also added some support for managing schedules. Full support for schedules are still in development.

Added some support for working with and testing the FM Data API. See the last layout in the sample file to explore functionality.

Read more here: <a href="https://www.soliantconsulting.com/blog/filemaker-18-admin-api/">https://www.soliantconsulting.com/blog/filemaker-18-admin-api/</a>

To Do:<ul>
   <li>Add and Edit schedules</li>
</ul>

Note: Version for working with FileMaker 17 servers is still available here, named "Admin API Tool_v17.fmp12". Note that this version of the admin api expires in September 2019.
