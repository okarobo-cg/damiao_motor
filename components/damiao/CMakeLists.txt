set(requires "esp_driver_twai")
idf_component_register(SRC_DIRS "."
                    INCLUDE_DIRS "."
                    REQUIRES ${requires})