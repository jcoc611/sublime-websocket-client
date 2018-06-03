# sublime-websocket-client
Flattened, Sublime-ready websocket client dependency

Based on the websocket-client python project. See it on [Github](https://github.com/websocket-client/websocket-client), or on [PyPI](https://pypi.org/project/websocket-client/).

this repo | pypi
---- | ----
![latest tag](https://img.shields.io/github/tag/jcoc611/sublime-websocket-client.svg) | [![pypi](https://img.shields.io/pypi/v/websocket-client.svg)](https://pypi.python.org/pypi/websocket-client)


## Usage
Add the following to your `dependencies.json` in the directory of your package.
```json
{
  "*": {
      "*": [
      	"six",
        "websocket-client",
      ]
  }
}
```

## License
The contents of this repository are licensed under the GNU Lesser General Public License. A copy of such is available in `LICENSE`.
