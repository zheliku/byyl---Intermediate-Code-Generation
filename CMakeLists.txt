cmake_minimum_required(VERSION 3.20)
project(zjdmsc_1 C)

set(CMAKE_C_STANDARD 11)

add_executable(zjdmsc_1 main.c semantics.c symbols.c translate.c tree.c ir_buffer.c ir_buffer.h translate.h symbols.h translate.h
        syntax.tab.h syntax.tab.c lex.yy.c main.c log.h log.c)
