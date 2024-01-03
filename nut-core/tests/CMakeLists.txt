add_executable(test-hello-world test-hello-world.cpp)

target_link_libraries(test-hello-world nut-core)

add_test(NAME test-hello-world COMMAND test-hello-world)