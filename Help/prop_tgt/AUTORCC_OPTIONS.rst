AUTORCC_OPTIONS
---------------

Additional options for ``rcc`` when using :prop_tgt:`AUTORCC`

This property holds additional command line options
which will be used when ``rcc`` is executed during the build via :prop_tgt:`AUTORCC`,
i.e. it is equivalent to the optional ``OPTIONS`` argument of the
:module:`qt4_add_resources() <FindQt4>` macro.

By default it is empty.

This property is initialized by the value of the variable
:variable:`CMAKE_AUTORCC` if it is set when a target is created.

The options set on the target may be overridden by :prop_sf:`AUTORCC_OPTIONS` set
on the ``.qrc`` source file.
