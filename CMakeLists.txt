include_directories("./")

set(SOURCE_FILES
	imconfig.h
	imgui.h
	imgui.cpp
	imgui_internal.h
	imgui_demo.cpp
	imgui_draw.cpp
	imgui_widgets.cpp
	imstb_rectpack.h
	imstb_textedit.h
	imstb_truetype.h
	
	backends/imgui_impl_glfw.h
	backends/imgui_impl_glfw.cpp
	
	misc/cpp/imgui_stdlib.h
	misc/cpp/imgui_stdlib.cpp
)

add_library(imgui STATIC ${SOURCE_FILES})