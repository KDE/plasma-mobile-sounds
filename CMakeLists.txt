# Copyright 2021 Devin Lin <devin@kde.org>
#
# SPDX-License-Identifier: GPL-2.0-or-later


cmake_minimum_required(VERSION 3.16)
project(plasma-mobile-sounds)
set(PROJECT_VERSION "1.0")

include(GNUInstallDirs)

install(DIRECTORY plasma-mobile DESTINATION ${CMAKE_INSTALL_DATADIR}/sounds)
