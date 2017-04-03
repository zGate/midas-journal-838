message(STATUS "SplineDrivenImageSlicer: Building as a Remote VTK module")

set(Module_SRCS
  vtkFrenetSerretFrame.cxx
  vtkSplineDrivenImageSlicer.cxx  
)

vtk_module_library(SplineDrivenImageSlicer ${Module_SRCS})
