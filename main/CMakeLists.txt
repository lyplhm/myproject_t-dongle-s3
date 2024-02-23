# idf_component_register(SRC_DIRS "."
#                     INCLUDE_DIRS ".")

idf_component_register(
    SRCS 
    "main.c"
    "hw/lv_port_disp.c"
                    
    INCLUDE_DIRS 
    "."
    )
