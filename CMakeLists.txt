# # Menor versão com suporte a cross-compiling
cmake_minimum_required(VERSION 2.6)

idf_component_register(SRCS 
                        "uart.c"
                    INCLUDE_DIRS "include")
                    