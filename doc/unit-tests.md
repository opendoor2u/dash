Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disabled.

After configuring, they can be run with `make check`.

To run the sphered tests manually, launch `src/test/test_sphere`.

To add more sphered tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the sphere-qt tests manually, launch `src/qt/test/test_sphere-qt`

To add more sphere-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
