#
# Copyright (c) 2021 - 2022 Advanced Micro Devices, Inc. All rights reserved.
#
#-------------------------------------------------------------------------------------------------
set(project "DisplayHDCP")

set(all_file
  "mainDisplayHDCP.cpp"
  ${CMAKE_SOURCE_DIR}/../../SDK/ADLXHelper/Windows/Cpp/ADLXHelper.h
  ${CMAKE_SOURCE_DIR}/../../SDK/ADLXHelper/Windows/Cpp/ADLXHelper.cpp
  ${CMAKE_SOURCE_DIR}/../../SDK/platform/Windows/WinAPIs.cpp
 )

add_executable (${project} ${all_file})