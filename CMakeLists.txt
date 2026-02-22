cmake_minimum_required(VERSION 3.16)

project(rigol_vendor_bin C)

set(SOURCES
    rigol_vendor_bin.c
    rigol_vendor_bin.h
    aes.c
    aes.h
    xxtea.c
    crc32.c
    strings.c
)

add_executable(rigol_vendor_bin ${SOURCES})
