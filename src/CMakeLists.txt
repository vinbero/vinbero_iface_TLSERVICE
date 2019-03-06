configure_file(
  "${PROJECT_SOURCE_DIR}/src/${PROJECT_NAME}.h.in"
  "${PROJECT_BINARY_DIR}/${PROJECT_NAME}.h"
  @ONLY
)

install(FILES "${PROJECT_BINARY_DIR}/${PROJECT_NAME}.h" DESTINATION include/vinbero)
