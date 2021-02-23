cmake_minimum_required(VERSION 3.9)

include("Release/cmake/HunterGate.cmake")
HunterGate(
        URL "https://github.com/anhydrous99/hunter/archive/master.zip"
        SHA1 "164f14b8c9e163d863d9bf315c429b61437d9f14"
)

project(cpprestsdk-root NONE)
enable_testing()
add_subdirectory(Release)
