# tests can only be dependencies of other tests in this directory
__dependents_rules__(("*", "/**", "!*"))

files(
    name="fixtures",
    sources=["fixtures/*.json"],
)

python_tests(
    name="tests",
    dependencies=[":fixtures"],
    skip_pylint=True,
)
