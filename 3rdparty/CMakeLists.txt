if (NOT SYSTEM_EXPAT)
	add_subdirectory(expat)
endif()

add_subdirectory(utf8)

if (ENABLE_DNS AND NOT SYSTEM_UDNS)
	add_subdirectory(udns)
endif()
