# SPDX-License-Identifier: GPL-2.0-only

obj-$(CONFIG_CAN_MCP25XXFD) += mcp25xxfd.o

mcp25xxfd-objs := mcp25xxfd_base.o
mcp25xxfd-objs += mcp25xxfd_can.o
mcp25xxfd-objs += mcp25xxfd_can_fifo.o
mcp25xxfd-objs += mcp25xxfd_can_int.o
mcp25xxfd-objs += mcp25xxfd_can_rx.o
mcp25xxfd-objs += mcp25xxfd_can_tx.o
mcp25xxfd-objs += mcp25xxfd_clock.o
mcp25xxfd-objs += mcp25xxfd_cmd.o
mcp25xxfd-objs += mcp25xxfd_crc.o
mcp25xxfd-objs += mcp25xxfd_ecc.o
mcp25xxfd-objs += mcp25xxfd_int.o

mcp25xxfd-$(CONFIG_CAN_MCP25XXFD_DEBUG_FS) += mcp25xxfd_can_debugfs.o
mcp25xxfd-$(CONFIG_CAN_MCP25XXFD_DEBUG_FS) += mcp25xxfd_debugfs.o
mcp25xxfd-$(CONFIG_GPIOLIB) += mcp25xxfd_gpio.o
