# CMakeFiles.txt inside "RF433any" folder
cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "RF433any.cpp" "RF433Debug.cpp" "RF433Serial.cpp"
                    INCLUDE_DIRS "."
                    REQUIRES "arduino" # Library requires Arduino
                    )

project(RF433any)