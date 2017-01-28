cmake_minimum_required (VERSION 2.6)

# This is the name of the project
PROJECT( IP_Codes  )

# This is for recursively searching for other directories.
# add_subdirectory (DirectoryName)

# sources to include
include_directories (.)

# where to get the libraries
link_directories (/usr/local/lib)

FIND_PACKAGE( OpenCV REQUIRED )

#ADD_EXECUTABLE( IP_Codes  IP1.cpp)
#TARGET_LINK_LIBRARIES( IP_Codes ${OpenCV_LIBS} )

