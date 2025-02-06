idf_component_register(SRCS "./components/i2cdev/i2cdev.c"
                            "./components/ina219/ina219.c"
                       INCLUDE_DIRS "./components/esp_idf_lib_helpers/"
                                    "./components/i2cdev/"
                                    "./components/ina219/"
                       REQUIRES driver)