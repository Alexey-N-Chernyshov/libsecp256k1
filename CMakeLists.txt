#
# Copyright Soramitsu Co., Ltd. All Rights Reserved.
# SPDX-License-Identifier: Apache-2.0
#

cmake_minimum_required(VERSION 3.12)

project("libsecp256k1"
    LANGUAGES C
    )

include_directories(
    # project includes
    ${PROJECT_SOURCE_DIR}/include
)

add_subdirectory(src)
