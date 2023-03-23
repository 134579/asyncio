add_executable(sched_test sched_test.cpp)
find_package(Catch2 CONFIG REQUIRED)
target_link_libraries(sched_test PRIVATE Catch2::Catch2WithMain nanobench::nanobench asyncio)
