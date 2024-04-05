SET(SOURCES components/ui_comp_dial.c
    components/ui_comp_gauge.c
    components/ui_comp.c
    screens/ui_Screen1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c
    images/ui_img_226560045.c
    images/ui_img_1004565353.c)

add_library(ui ${SOURCES})
