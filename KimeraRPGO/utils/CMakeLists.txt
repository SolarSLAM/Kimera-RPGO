# Add source code for KimeraRPGO
target_sources(KimeraRPGO
	PRIVATE
		"${CMAKE_CURRENT_LIST_DIR}/geometry_utils.h"
		"${CMAKE_CURRENT_LIST_DIR}/graph_utils.h"
		"${CMAKE_CURRENT_LIST_DIR}/graph_utils.cpp"
		"${CMAKE_CURRENT_LIST_DIR}/type_utils.h"
)
target_include_directories(KimeraRPGO PRIVATE ${CMAKE_CURRENT_LIST_DIR})
