# Copyright 2021 Devin Lin <devin@kde.org>
#
# SPDX-License-Identifier: GPL-2.0-or-later


cmake_minimum_required(VERSION 3.16)
project(plasma-mobile-sounds)
set(PROJECT_VERSION "1.0")

find_package(ECM ${KF5_MIN_VERSION} REQUIRED CONFIG)
set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} ${ECM_MODULE_PATH})

include(KDEInstallDirs)
include(KDECMakeSettings)

install(DIRECTORY plasma-mobile DESTINATION ${KDE_INSTALL_SOUNDDIR})
