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
| **name**        |  **Example:**`"Alvin Lawson"` Allows the caller to have their own username. |
| **thanksmessage** |  **Example:**`"Purpose"`Allows the caller to post a "thanks" message to their own username.|
| *thanksmessage(optionals)*| **Example:** `"mindfulness"`, `“balance”`, `“clarity”`, `“empowerment”`, `“reality”` or `“play”` These are the optional **thanksmessage** values you can use.|

## Create the "thanks" message:

|`POST /users/thanksmessages`|
|---------------|

Creating a new **"thanksmessage"** is easier now POSTing to the new `/users/thanksmessages` endpoint. You can post the positive **"thanksmessage"** value to your significant other that you desire. A caller is required to use one of these given **"thanksmessage"** values: `"Purpose"`,`"mindfulness"`, `“balance”`, `“clarity”`, `“empowerment”`, `“reality”`,and`“play”`.

## Return the "thanks" message:

|`GET /users/thanksmessages`|
|---------------|

Returns the full "thanks" message that a caller POSTed.

![image of return thanksmessage](https://raw.githubusercontent.com/al11588/AsanaDeveloperAdvocateAssignment/master/Screen%20Shot%202018-09-30%20at%206.44.40%20PM.png?token=AFM1uAX-r785Ub_s64dbIaCawEfIMokNks5buo2iwA%3D%3D)

## Example Code:

[Click Here]

[Asana]:https://asana.com/developers/api-reference/users
[Sublime Text]:https://www.sublimetext.com/
[Atom]:https://atom.io/
[Visual Studio Code]:https://code.visualstudio.com/
[Click Here]:https://github.com/al11588/AsanaDeveloperAdvocateAssignment/blob/master/thanksmessagecode.json
