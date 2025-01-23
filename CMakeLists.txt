cmake_minimum_required (VERSION 3.13)
project (ayatana-greeter-badges VERSION 0.3 LANGUAGES NONE)

if(CMAKE_INSTALL_PREFIX_INITIALIZED_TO_DEFAULT)
    SET(CMAKE_INSTALL_PREFIX "/usr" CACHE PATH "..." FORCE)
endif(CMAKE_INSTALL_PREFIX_INITIALIZED_TO_DEFAULT)

include(GNUInstallDirs)

add_subdirectory(data)
