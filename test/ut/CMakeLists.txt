find_package(Catch2 CONFIG REQUIRED)
add_executable(asyncio_ut selector_test.cpp task_test.cpp result_test.cpp counted.h)
target_link_libraries(asyncio_ut Catch2::Catch2WithMain asyncio)
