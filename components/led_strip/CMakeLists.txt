set(srcs "src/led_strip_rmt_ws2812.c")

idf_component_register(SRCS "${srcs}"
                    INCLUDE_DIRS "include"
                    PRIV_REQUIRES "driver"
                    )
