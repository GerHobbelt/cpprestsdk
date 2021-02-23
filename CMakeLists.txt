cmake_minimum_required(VERSION 3.9)

include("Release/cmake/HunterGate.cmake")
HunterGate(
        URL "https://github.com/anhydrous99/hunter/archive/v0.23.295-arm.tar.gz"
        SHA1 "9e9534cb344f23dbb4deb84dcbae1e8e0472c963"
)

project(cpprestsdk-root NONE)
enable_testing()
add_subdirectory(Release)
