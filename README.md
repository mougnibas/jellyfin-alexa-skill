```
Copyright (c) 2020 Yoann MOUGNIBAS

This file is part of jellyfin-alexa-skill.

jellyfin-alexa-skill is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

jellyfin-alexa-skill is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with jellyfin-alexa-skill.  If not, see <https://www.gnu.org/licenses/>.
```
# General

An unofficial Alexa skill for jellyfin.
This project isn't affilated to Jellyfin nor Amazon.

Jellyfin official project : https://jellyfin.org/

Amazon Alexa official project : https://developer.amazon.com/alexa

# For developers

## Project links

* Public project repository : https://github.com/mougnibas/jellyfin-alexa-skill

## Requirements

* Visual Studio Code (https://code.visualstudio.com/)
* OpenJDK 15.0.x (https://jdk.java.net/15/)
* Maven 3.6.3 (https://maven.apache.org/download.cgi)
* Java Extension Pack, provided by Microsoft (https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

## Sources convention

* "CR LF" line ending
* UTF-8 (without BOM)

## Build

`mvn clean package`

## Run (Windows)

`java -jar .\target\jellyfin-alexa-skill-1.0.0-SNAPSHOT.jar`
