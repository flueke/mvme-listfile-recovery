cmake_minimum_required(VERSION 3.0.0)
project(mvme_recover_listfile)

find_library(ZLIB z)

add_executable(mvme_recover_listfile mvme_recover_listfile_hack.c)
target_link_libraries(mvme_recover_listfile ${ZLIB})
