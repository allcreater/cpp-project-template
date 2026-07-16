cmake_minimum_required (VERSION 4.2)

add_executable (MainModule
    "main.cpp"
)

target_compile_features(MainModule PRIVATE cxx_std_23 )
