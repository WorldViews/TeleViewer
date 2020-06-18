# TeleViewer
The Cesium based viewer that had been in WVS repo, extracted into simpler form

To run this, just clone the repo, install python3 and start a python server.
On windows, the server is started by

    runPythonServer

Or just directly issue this command

    python -m http.server --cgi 8000

Then to see the televiewer, open the URL

    http://localhost:8000/static/TeleViewer.html

Note that this repo has a copy of Cesium already present in the static directory

