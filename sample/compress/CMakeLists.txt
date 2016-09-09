project(compress)

list(APPEND SRC
	stream_compress.c
	)

list(APPEND LIBS
	quicklz
    )
	
add_executable(${PROJECT_NAME} ${SRC})
target_link_libraries(${PROJECT_NAME} ${LIBS})
