# Specification file for the CMake build system
#
# Laurence R. McGLashan
# 22 June 2011

project (CHEMKINREADER)

add_library(chemkinreader SHARED
            stringFunctions.cpp
            element.cpp 
            transport.cpp
            species.cpp
            thermo.cpp 
            reaction.cpp
            thermoParser.cpp 
            transportParser.cpp
            reactionParser.cpp
            chemkinReader.cpp)
