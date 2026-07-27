cmake_minimum_required (VERSION 4.2)

add_executable (MainModule
    "main.cpp"
)

set_target_properties(MainModule PROPERTIES
        CXX_STANDARD 23
        CXX_STANDARD_REQUIRED ΟΝ
        CXX_MODULE_STD ON
        CXX_EXTENSIONS OFF
)
