
SET( SCRIPT_EDITOR_SRC

    include/script_editor.h
    
    src/script_editor.cpp
    )

add_library(scripteditor STATIC ${SCRIPT_EDITOR_SRC})

target_link_libraries(scripteditor Qt5::Widgets )
