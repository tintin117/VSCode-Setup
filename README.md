# VSCode setup

Date Created: Oct 21, 2019 8:35 PM
Status: To Do

# General

1. Python
2. vscode-icons
3. psioniq File Header
4. Linux Themes for VS Code
5. setting.json:
```json
    {	"python.pythonPath": "G:\\P4V\\DevLine\\python-3.7.2.amd64",
        "workbench.statusBar.visible": true,
        "editor.renderWhitespace": "all",
        "editor.renderControlCharacters": true,
        "workbench.sideBar.location": "left",
        "workbench.activityBar.visible": true,
    	"window.zoomLevel": 0,
        "editor.fontSize": 17,
        "workbench.colorTheme": "United Ubuntu",
        "psi-header.lang-config": [{
            "language": "python",
    			"begin": "###",
    			"prefix": "# ",
    			"end": "###",
    			"blankLinesAfter": 0,
    			"beforeHeader": [
    				"#!/usr/bin/env python",
                    "# -*- coding:utf-8 -*-"
                ]
        }],
        "psi-header.config": {
    		"forceToTop": true,
    		"blankLinesAfter": 6,
    		"license": "Custom"
    	},
    	"psi-header.changes-tracking": {
    		"isActive": true,
    		"modAuthor": "Modified By: ",
    		"modDate": "Last Modified: ",
    		"modDateFormat": "date",
    		"include": [],
    		"exclude": [
    			"markdown",
    			"json"
    		],
    		"excludeGlob": [
    			"out/**",
    			"src/**/*.xyz"
    		],
    		"autoHeader": "manualSave"
    	},
        "psi-header.templates": [
    		{
    			"language": "*",
    			"template": [
    				"File: <<filepath>>",
    				"Project: <<projectpath>>",
    				"Created Date: <<filecreated('dddd, MMMM Do YYYY, h:mm:ss a')>>",
    				"Author: <<author>>",
    				"-----",
    				"Last Modified: ",
    				"Modified By: ",
    				"-----"
    			],
    			"changeLogCaption": "HISTORY:",
    			"changeLogHeaderLineCount": 2,
    			"changeLogEntryTemplate": [
    				"<<dateformat('YYYY-MM-DD')>>\t<<initials>>\t"
    			]
            }
    	],
    	"search.location": "panel",
    	"workbench.iconTheme": "vscode-icons",
    	"terminal.integrated.shell.windows": "C:\\Windows\\System32\\cmd.exe",
    	"vsicons.dontShowNewVersionMessage": true,
    	"perforce.activationMode": "always",
    	"files.associations": {
    		"*.cgfx": "hlsl"
    	},
    	"dart.flutterSdkPath": "G:\\__RandD\\Flutter\\flutter",
    }
```
# Additional

1. Dart
2. Flutter
3. Perforce for VS Code
4. MayaCode
5. MEL
6. MayaPort
