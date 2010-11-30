
# Create the extension library

ADD_LIBRARY(Extensions_OpenCL
  Meta/OpenCL.h
  Meta/OpenCL.cpp
  Meta/cl.hpp
)

TARGET_LINK_LIBRARIES(Extensions_OpenCL
    ${OPENCL_LIBRARY}
#    ${OPENCL_UTIL_LIBRARY}
)