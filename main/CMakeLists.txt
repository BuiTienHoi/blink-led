idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES driver esp_wifi nvs_flash Project_wifi)
