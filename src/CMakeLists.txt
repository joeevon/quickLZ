project(quicklz)

list(APPEND SRC 
	quicklz.c
    )

list(APPEND LIBS
)

add_library(${PROJECT_NAME} ${SRC})
target_link_libraries(${PROJECT_NAME} ${LIBS})
