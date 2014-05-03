# Copyright 2005 <chaishushan{AT}gmail.com>. All rights reserved.
# Use of this source code is governed by a BSD-style
# license that can be found in the LICENSE file.

project(TINY)

add_executable(tiny
  ./src/tiny/tiny.c
)
add_executable(casl
  ./src/casl/casl.c
)
add_executable(comet
  ./src/comet/comet.c
)

