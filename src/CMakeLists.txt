add_executable({{name}} hello.cpp)
target_link_libraries({{name}} PUBLIC fmt::fmt nlohmann_json::nlohmann_json spdlog::spdlog)