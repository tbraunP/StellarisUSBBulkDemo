project(libusbbulk)

add_executable(libusbbulk bulk.cpp)
target_link_libraries (libusbbulk m c usb-1.0)
install(TARGETS libusbbulk RUNTIME DESTINATION bin)
