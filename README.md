# imhotep-pep8

`imhotep-pep8` is a plugin for
[`imhotep`](https://github.com/justinabrahms/imhotep), which provides bindings
to the pep8 linter. For information on how to setup and run imhotep, [see it's
docs](https://github.com/justinabrahms/imhotep).


## Installation & Usage
Install the plugin with:

```
pip install imhotep-pep8
```

To use the plugin, you'll have to pass a path to the linter in question to the
imhotep runtime.

```
python imhotep/main.py --linter=imhotep_pep8.plugin:Pep8Linter # other args here
```
