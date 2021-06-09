{
   // Use IntelliSense to find out which attributes exist for C# debugging
   // Use hover for the description of the existing attributes
   // For further information visit https://github.com/OmniSharp/omnishar...
   "version": "0.2.0",
   "configurations": [
       {
           "name": "Python: Current Dir (external)",
           "type": "python",
           "request": "launch",
           "cwd":"${fileDirname}",
           "program": "${file}",
           "console": "externalTerminal",
           "env": {"PYTHONPATH": "${workspaceRoot}"},
       },
       {
           "name": "Python: Current Dir (internal)",
           "type": "python",
           "request": "launch",
           "cwd":"${fileDirname}",
           "program": "${file}",
           "console": "integratedTerminal",
           "env": {"PYTHONPATH": "${workspaceRoot}"},
        },
       {
            "name": "Python: Current File (Integrated Terminal)",
            "type": "python",
            "request": "launch",
            "program": "${file}",
            "console": "integratedTerminal",
       }
   ]
}
