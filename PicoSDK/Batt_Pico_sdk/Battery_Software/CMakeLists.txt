if (NOT PICO_NO_HARDWARE)
    add_subdirectory(lib)
    add_subdirectory(boot)
endif ()

target_include_directories(main PUBLIC lib)
target_include_directories(neopixel PUBLIC lib)
target_include_directories(tools PUBLIC lib)
target_include_directories(pysquared PUBLIC lib)
target_include_directories(ina219 PUBLIC lib)
target_include_directories(pct2075 PUBLIC lib)
target_include_directories(pca9685 PUBLIC lib)
target_include_directories(tca9548a PUBLIC lib)
target_include_directories(mcp9808 PUBLIC lib)
target_include_directories(veml7700 PUBLIC lib)
target_include_directories(drv2605 PUBLIC lib)
target_include_directories(ads1015 PUBLIC lib)
target_include_directories(functions PUBLIC lib)
target_include_directories(big_data PUBLIC lib)