cmake_minimum_required(VERSION 4.1)
project(ProgettoSO_mensa C)

set(CMAKE_C_STANDARD 11)

add_executable(ProgettoSO_mensa main.c
        common.h
        common.c
        responsabile_mensa.c
        operatore.c
        operatore_cassa.c
        utente.c)
