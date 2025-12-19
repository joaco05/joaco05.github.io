# Distributed under the OSI-approved BSD 3-Clause License.  See accompanying
# file Copyright.txt or https://cmake.org/licensing for details.

cmake_minimum_required(VERSION 3.31.6)

# Reject any attempt to use a toolchain file. We must not use one because
# we could be downloading it here. If the CMAKE_TOOLCHAIN_FILE environment
# variable is set, the cache variable will have been initialized from it.
unset(CMAKE_TOOLCHAIN_FILE CACHE)
unset(ENV{CMAKE_TOOLCHAIN_FILE})

# We name the project and the target for the ExternalProject_Add() call
# to something that will highlight to the user what we are working on if
# something goes wrong and an error message is produced.

project(opencv_package_emscripten-populate NONE)



include(ExternalProject)
ExternalProject_Add(opencv_package_emscripten-populate
                     "UPDATE_DISCONNECTED" "False" "DOWNLOAD_EXTRACT_TIMESTAMP" "ON" "EXTERNALPROJECT_INTERNAL_ARGUMENT_SEPARATOR" "URL" "https://github.com/pthom/imgui_bundle/releases/download/v1.3.0/opencv_4.9_no_pthread_emscripten_install.tgz" "URL_MD5" "2a9e65542123548bec1b80ee2cb6056e"
                    SOURCE_DIR          "/home/joaco/Documentos/imgui_bundle_template/build_emscripten/_deps/opencv_package_emscripten-src"
                    BINARY_DIR          "/home/joaco/Documentos/imgui_bundle_template/build_emscripten/_deps/opencv_package_emscripten-build"
                    CONFIGURE_COMMAND   ""
                    BUILD_COMMAND       ""
                    INSTALL_COMMAND     ""
                    TEST_COMMAND        ""
                    USES_TERMINAL_DOWNLOAD  YES
                    USES_TERMINAL_UPDATE    YES
                    USES_TERMINAL_PATCH     YES
)


