workspace(name = "wildcard_test_workspace")

local_repository(
    name = "my_libs",
    path = "libs/*"
)

new_local_repository(
    name = "external_tools", 
    path = "external/*",
    build_file = "BUILD.external"
)
