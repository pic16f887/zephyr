# SPDX-License-Identifier: Apache-2.0

zephyr_library()
zephyr_library_sources_ifdef(CONFIG_SDMMC			sdmmc.c)
zephyr_library_sources_ifdef(CONFIG_SDMMC_STM32		sdmmc_stm32.c)
