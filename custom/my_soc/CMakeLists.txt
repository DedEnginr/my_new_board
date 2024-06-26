# Copyright (c) 2021 Yonatan Schachter
# SPDX-License-Identifier: Apache-2.0


zephyr_sources(soc.c)


include_directories(${ZEPHYR_BASE}/ext/hal/cmsis/Include)

set(SOC_LINKER_SCRIPT ${ZEPHYR_BASE}/include/zephyr/arch/arm/cortex_m/scripts/linker.ld CACHE INTERNAL "")
