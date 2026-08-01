idf_component_register(SRCS "Project_wifi.c"
                    INCLUDE_DIRS "."
                    REQUIRES driver esp_wifi nvs_flash)