#idf_component_register(SRCS "psxcontroller.c" "spi_lcd.c"  # List all source files
#                       INCLUDE_DIRS ".")


idf_component_register(
    SRCS 
        "i2c_keyboard.c"
        "osd.c"
        "psxcontroller.c" 
        "spi_lcd.c"
        "video_audio.c"
    REQUIRES nofrendo driver
)