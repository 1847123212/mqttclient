aux_source_directory(. WARAPPER_SRCS)

add_library("wrapper" STATIC ${WARAPPER_SRCS})
target_link_libraries("wrapper" "platform")



