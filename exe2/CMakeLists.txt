add_executable(exe2
        main.c
)

target_link_libraries(exe2
                     hardware_adc
                     pico_stdlib )
pico_add_extra_outputs(exe2)
