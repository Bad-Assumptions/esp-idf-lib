# The following four lines of boilerplate have to be in your project's CMakeLists
# in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.5)

set(EXTRA_COMPONENT_DIRS C:/Users/balano/Documents/GitHub/99-0002000/components/esp-idf-lib/components)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(example-encoders)
