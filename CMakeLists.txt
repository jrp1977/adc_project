cmake_minimum_required(VERSION 3.10)

project(ADC_Project C)

set(CMAKE_C_STANDARD 99)

add_executable(ADC_Project
        main.c
        adc.c
        io.c
        stats.c
        analysis.c
        report.c
        fault.c
)

target_link_libraries(ADC_Project m)