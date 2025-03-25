target_sources(pslab-firmware.elf PRIVATE
  multimeter.c
  oscilloscope.c
)

target_include_directories(pslab-firmware.elf
  PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})

