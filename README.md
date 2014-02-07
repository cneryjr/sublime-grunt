sublime-grunt-tekton
====================

A Grunt task runner specific for Tekton (Softbox Co) for Sublime Text

## Installation

sublime-grunt-tekton can be installed via [Sublime Package Control](https://sublime.wbond.net/). In Package Control, it is called **GruntTekton**. Please refer to the offical Package Control documentation to learn how to install packages.

Alternatively, you can also clone the [sublime-grunt-tekton repository](https://github.com/cneryjr/sublime-grunt-tekton/) into your Sublime Text packages folder.

## Usage

Open the command palette using Ctrl+Shift+P (or Cmd+Shift+P on Mac, respectively)
and choose the "Grunt" command.

The plugin expects to find a Gruntfile (`Gruntfile.Tekton.js`) in an open folder.
It displays a sorted list of available Grunt tasks out of this Grunt file.
If it finds more than one Gruntfile, it first provides a list for selection.

As of version 0.2, there is also a command to kill running tasks, for example
`watch` tasks.

## Settings

The file `SublimeGruntTekton.sublime-settings` is used for configuration.

You may override your `PATH` environment variable as follows:

```
{
    "exec_args": {
        "path": "/bin:/usr/bin:/usr/local/bin"
    }
}
```

## Releases

* 0.1 Initial release

## Thanks

Thanks for some contributions go to

* [Tim von Oldenburg](https://github.com/tvooo)
