#
# Copyright (c) 2021 - 2022 Advanced Micro Devices, Inc. All rights reserved.
#
#-------------------------------------------------------------------------------------------------
set(project "ImageSharpening")

set(all_file 
  "mainImageSharpening.c"
  ${CMAKE_SOURCE_DIR}/../../SDK/ADLXHelper/Windows/C/ADLXHelper.h
  ${CMAKE_SOURCE_DIR}/../../SDK/ADLXHelper/Windows/C/ADLXHelper.c
  ${CMAKE_SOURCE_DIR}/../../SDK/platform/Windows/WinAPIs.c
 )
 
add_executable (${project} ${all_file})
