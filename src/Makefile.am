#
# picotm-demo - A demo application for picotm
# Copyright (c) 2017-2018   Thomas Zimmermann <contact@tzimmermann.org>
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <https://www.gnu.org/licenses/>.
#
# SPDX-License-Identifier: GPL-3.0-or-later
#

bin_PROGRAMS = picotm-demo

picotm_demo_SOURCES = buf.c \
                      buf.h \
                      in.c \
                      in.h \
                      main.c \
                      proc.c \
                      proc.h \
                      queue.c \
                      queue.h \
                      recovery.c \
                      recovery.h \
                      ui.c \
                      ui.h

LDADD = @FORM_LIBS@ @CURSES_LIBS@

AM_CFLAGS = @CURSES_CFLAGS@
