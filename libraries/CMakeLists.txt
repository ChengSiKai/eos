add_subdirectory( fc )
add_subdirectory( builtins )
add_subdirectory( softfloat )
add_subdirectory( chainbase )
add_subdirectory( wasm-jit )
add_subdirectory( appbase )
add_subdirectory( chain )
add_subdirectory( testing )

#turn these off for now
set(BUILD_TESTS OFF CACHE BOOL "Build GTest-based tests")
set(BUILD_TOOLS OFF CACHE BOOL "Build wabt tools")
set(RUN_RE2C OFF CACHE BOOL "Run re2c")
add_subdirectory( wabt )
