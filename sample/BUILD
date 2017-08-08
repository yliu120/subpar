py_binary(
    name = "version_check_py2",
    srcs = ["version_check_py2.py"],
    default_python_version = "PY2",
)

py_binary(
    name = "version_check_py3",
    srcs = ["version_check_py3.py"],
    default_python_version = "PY3",
    srcs_version = "PY2AND3",
)

py_test(
    name = "version_test_py2",
    srcs = ["version_test_py2.py"],
    default_python_version = "PY2",
)

py_test(
    name = "version_test_py3",
    srcs = ["version_test_py3.py"],
    default_python_version = "PY3",
    srcs_version = "PY2AND3",
)
