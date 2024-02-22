set(COMPONENT_SRCS "src/interpolation.cpp")
set(COMPONENT_ADD_INCLUDEDIRS "./include")

idf_component_register(
    SRC_DIRS ./src
    INCLUDE_DIRS ./include
    #REQUIRES ${req}
)
component_compile_options(-Wno-error=format= -Wno-format )



