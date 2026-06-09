# The following lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.16)

# Greeting name on the dashboard. Override with:
#   idf.py build -- -DRLCD_GREETING_NAME="YourName"
set(RLCD_GREETING_NAME "" CACHE STRING "Greeting name for dashboard header")

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(qwen_token_monitor_ble)
