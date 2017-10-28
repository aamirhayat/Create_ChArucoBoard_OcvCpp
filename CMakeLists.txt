# ----------------------------------------------------------------------------
#   Basic Configuration
# ----------------------------------------------------------------------------
cmake_minimum_required(VERSION 2.8)
project( create_board_charuco )
set(OpenCV_FOUND 1)
set ("OpenCV_DIR" "/home/iit/opencv/build")
find_package( OpenCV REQUIRED )
add_executable( create_board_charuco create_board_charuco.cpp )
target_link_libraries( create_board_charuco ${OpenCV_LIBS} )
message ("Make the Charuco Board by giving the arguments")
message ("Example: reate_board_charuco board2.png –bb=100 -d=10 -h=9 --ml=100 -si=true --sl=300 -w=7")
# ----------------------------------------------------------------------------




