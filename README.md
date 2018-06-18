# *gateone* module for Package Control

This provides the terminal from the GateOne project: https://github.com/liftoff/GateOne

## How to use *gateone* as a dependency

In order to tell Package Control
that you are using the *gateone* module
in your ST package,
create a `dependencies.json` file
in your package root
with the following contents:

```js
{
   "*": {
      "*": [
         "gateone-terminal"
      ]
   }
}
```

If the file exists already,
add `"gateone-terminal"` to the every dependency list.

Then run the **Package Control: Satisfy Dependencies** command
to make Package Control
install the module for you locally
(if you don't have it already).

After all this
you can use `import gateone`
in any of your Python plugins.

See also:
[Documentation on Dependencies](https://packagecontrol.io/docs/dependencies)


## License

The contents of the root folder
in this repository
are released
under the *public domain*.
The contents of the `all/` folder
fall under *their own bundled licenses*.


[pywinpty]: https://docs.python.org/3/library/pywinpty.html
[Package Control]: http://packagecontrol.io/
[Sublime Text]: http://sublimetext.com/
[pypi]: https://pypi.python.org/pypi/pywinpty
