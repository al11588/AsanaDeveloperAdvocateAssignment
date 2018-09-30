# Asana API 

## Overview:

The new [Asana] API endpoint allows for a caller to post a "thanks" message to a user in the system.

## Prerequisites:

Before you begin this guide, you need the following:

* You need to set up a local development environment for Terminal.

* A text editor that you will be comfortable using: [Sublime Text], [Atom], [Visual Studio Code]. 

* You need an Asana API key.

## Users:

The user account object allows for a caller to create their own "thanks" message.

Users who are the callers have these fields:

| Field         |                               Description                              |
|:---------------|:----------------------------------------------------------------------:|
| **id**            |  **Example:**`"6789"` Allows the caller to have their own unique ID.      |
| **name**        |  **Example:**`"Alvin Lawson"` Allows the caller to have their own user name. |
| **thanksmessage** |  **Example:**`"Purpose"`Allows the caller to post a "thanks" message to the their own user name.|
| *thanksmessage(optional)*| **Example:** `"mindfulness"`, `“balance”`, `“clarity”`, `“empowerment”`, `“reality”` or `“play”` These are some other optional **thanksmessage** you can use.|

## Create a "thanks" message:

|`POST /thanksmessages`|
|:---------------|


[Asana]:https://asana.com/developers/api-reference/users
[Sublime Text]:https://www.sublimetext.com/
[Atom]:https://atom.io/
[Visual Studio Code]:https://code.visualstudio.com/
