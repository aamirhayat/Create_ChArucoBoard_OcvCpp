# Create_ChArucoBoard_OcvCpp
This project is to create a ChAruco board

### Steps to get Executable
* Modify the CMakeLists.txt file as per the Version of OpenCv used and the its location on the computer
* Create a build folder (mkdir build) in the project folder
* cd build >$ cmake .. >$ make
* The executblae will be present inside the build folder as per the name given in CMakeLists

## Terminal Command
```
./create_board_charuco board1.png –bb=100 -d=1 -h=9 --ml=60 -si=true --sl=100 -w=7
```
where 
  --bb - Number of bits in marker borders 
  -d   - Dictionary used
  -h   - Height of grid
  --ml - Marker length
  -si  - Status of image (=True :will show the image)
  --sl - Square grid length (sl>ml)
  -w   - width of the grid

### Output image
![Output Image](https://github.com/aamirhayat/Create_ChArucoBoard_OcvCpp/blob/master/board1.png)

Versions Required for above project:
* OpenCV Version 3.0
* CMake >= 1.8
