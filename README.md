# EchoviewEcs.jl

[[Julia](http://julialang.org) package for reading [Echoview calibration
supplement (.ECS) files](http://support.echoview.com/WebHelp/Files,_filesets_and_variables/About_ECS_files.htm).


```
using EchoviewEcs
calibrations = load(filename)
```

`calibrations` is a `Vector` of `Dict` where `Dict` contains keys and
values being configuration parameters. SourceCal settings inherit from
FileSet settings but override such settings if specified explicitly.
