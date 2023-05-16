cmake_minimum_required(VERSION 3.5)

idf_component_register(
  SRCS
    "PN532_I2C/PN532_I2C.cpp"
    "PN532_HSU/PN532_HSU.cpp"
    "PN532_SPI/PN532_SPI.cpp"
    "PN532_SWHSU/PN532_SWHSU.cpp"
    "PN532/PN532.cpp"
    "PN532/llcp.cpp"
    "PN532/mac_link.cpp"
    "PN532/snep.cpp"
    "PN532/emulatetag.cpp"
  INCLUDE_DIRS
    "PN532"
    "PN532_HSU"
    "PN532_I2C"
    "PN532_SPI"
    "PN532_SWHSU"
)
