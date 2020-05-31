# reflex-vty-test-host

This library extends the testing monad in [reflex-test-host](https://github.com/pdlla/reflex-test-host) to work in [reflex-vty](https://github.com/reflex-frp/reflex-vty)

Some examples can be found in test/Reflex/Vty/Test/Monad/HostSpec.hs

This library currently has the basic methods for testing your reflex-vty apps in the reflex-test-host monad.

There are some more features coming depending on if I can have my changes merged into reflex-vty or not. You can preview these features in [potato-flow-vty](https://github.com/pdlla/potato-flow-vty)

PRs are welcome, in particular, it would be great to have monadic testing examples of many of the methods in reflex-vty added, e.g. test/Reflex/Vty/WidgetSpec.hs
