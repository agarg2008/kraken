cmake_minimum_required(VERSION 3.3)
project(src)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    classify.cpp
    db_shrink.cpp
    db_sort.cpp
    kraken_headers.hpp
    krakendb.cpp
    krakendb.hpp
    krakenutil.cpp
    krakenutil.hpp
    make_seqid_to_taxid_map.cpp
    quickfile.cpp
    quickfile.hpp
    seqreader.cpp
    seqreader.hpp
    set_lcas.cpp)

add_executable(src ${SOURCE_FILES})