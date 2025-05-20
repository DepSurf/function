# Function: <code>serial_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8150455f)
Location: drivers/tty/serial/8250/8250.h:100
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81505a16)
Location: drivers/tty/serial/8250/8250.h:100
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509cff)
Location: drivers/tty/serial/8250/8250.h:100
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81556089)
Location: drivers/tty/serial/8250/8250.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8155b0fd)
Location: drivers/tty/serial/8250/8250.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155bcad)
Location: drivers/tty/serial/8250/8250.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81582820)
Location: drivers/tty/serial/8250/8250.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815878af)
Location: drivers/tty/serial/8250/8250.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8158848c)
Location: drivers/tty/serial/8250/8250.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81596c1e)
Location: drivers/tty/serial/8250/8250.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159bd35)
Location: drivers/tty/serial/8250/8250.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_fifos
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_fifos
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c8e6)
Location: drivers/tty/serial/8250/8250.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff815fb885)
Location: drivers/tty/serial/8250/8250.h:114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81600fff)
Location: drivers/tty/serial/8250/8250.h:114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_fifos
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_fifos
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81601bf6)
Location: drivers/tty/serial/8250/8250.h:114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81634bc2)
Location: drivers/tty/serial/8250/8250.h:114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8163a264)
Location: drivers/tty/serial/8250/8250.h:114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163af01)
Location: drivers/tty/serial/8250/8250.h:114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff816526b3)
Location: drivers/tty/serial/8250/8250.h:114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81658508)
Location: drivers/tty/serial/8250/8250.h:114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81659114)
Location: drivers/tty/serial/8250/8250.h:114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff816870e3)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168da55)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e584)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff816a9793)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816affa5)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0b54)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175c333)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175fa37)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:do_set_rxtrig
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_8250
  - drivers/tty/serial/8250/8250_port.c:autoconfig_8250
  - drivers/tty/serial/8250/8250_port.c:autoconfig_8250
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763f8a)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81777203)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177a807)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:do_set_rxtrig
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_8250
  - drivers/tty/serial/8250/8250_port.c:autoconfig_8250
  - drivers/tty/serial/8250/8250_port.c:autoconfig_8250
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177eed6)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175acb3)
Location: drivers/tty/serial/8250/8250.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761cd7)
Location: drivers/tty/serial/8250/8250.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81762834)
Location: drivers/tty/serial/8250/8250.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff817de613)
Location: drivers/tty/serial/8250/8250.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e5d37)
Location: drivers/tty/serial/8250/8250.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e6903)
Location: drivers/tty/serial/8250/8250.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8191d1a3)
Location: drivers/tty/serial/8250/8250.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81925177)
Location: drivers/tty/serial/8250/8250.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81925e92)
Location: drivers/tty/serial/8250/8250.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192a252)
Location: drivers/tty/serial/8250/8250.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81a79223)
Location: drivers/tty/serial/8250/8250.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a81a98)
Location: drivers/tty/serial/8250/8250.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a828e2)
Location: drivers/tty/serial/8250/8250.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a869a2)
Location: drivers/tty/serial/8250/8250.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac4903)
Location: drivers/tty/serial/8250/8250.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acd088)
Location: drivers/tty/serial/8250/8250.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acdf10)
Location: drivers/tty/serial/8250/8250.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad2032)
Location: drivers/tty/serial/8250/8250.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b17903)
Location: drivers/tty/serial/8250/8250.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b2015d)
Location: drivers/tty/serial/8250/8250.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_has_efr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20fe0)
Location: drivers/tty/serial/8250/8250.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b25f82)
Location: drivers/tty/serial/8250/8250.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffff80001088506c)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088b2e8)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bfa0)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff8000108925b0)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (c0982d74)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (c0988f48)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (c0989994)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098d804)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_flow_ctrl
```
```
In drivers/tty/serial/omap-serial.c (c099e738)
Location: drivers/tty/serial/omap-serial.c:184
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset
  - drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_console_putchar
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_put_char
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_break_ctl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_unthrottle
  - drivers/tty/serial/omap-serial.c:serial_omap_throttle
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_rx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_enable_ms
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (c00000000092a62c)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (c000000000933db8)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934ad4)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffe00054f838)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000555112)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe000555828)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8166f1f3)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81675a15)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816765c4)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8164e323)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81654aef)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816556a4)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8169d5d3)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a3de5)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a4994)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff816b7aa3)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816be275)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816bedf4)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
</ul>

## Differences
