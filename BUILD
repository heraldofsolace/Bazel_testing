py_binary(
    name = "main",
    srcs = ["main.py"],
    deps = [
        "//lib:lib_prime"
    ],
)

py_test(
    name = "test_main",
    srcs = [ "test_main.py" ],
    deps = [
        ":main"
    ]
)