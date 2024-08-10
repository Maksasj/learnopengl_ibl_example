file(GLOB_RECURSE SRC_FILES *.cpp)

include_directories("./")
include_directories("../3dparty/glad/include")
include_directories("../3dparty/glfw/include")
include_directories("../3dparty/glm")
include_directories("../3dparty/stb")
include_directories("../3dparty/assimp/include")

add_executable(Example ${SRC_FILES})

target_link_libraries(Example glad)
target_link_libraries(Example glfw)
target_link_libraries(Example glm)
target_link_libraries(Example stb_image)
