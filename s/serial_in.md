# Function: <code>serial_in</code>

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
In drivers/tty/serial/8250/8250_core.c (ffffffff815044b9)
Location: drivers/tty/serial/8250/8250.h:95
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815059e6)
Location: drivers/tty/serial/8250/8250.h:95
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
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
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81556071)
Location: drivers/tty/serial/8250/8250.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815587d3)
Location: drivers/tty/serial/8250/8250.h:104
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81582808)
Location: drivers/tty/serial/8250/8250.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81584fe3)
Location: drivers/tty/serial/8250/8250.h:110
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81596c06)
Location: drivers/tty/serial/8250/8250.h:113
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159b3ec)
Location: drivers/tty/serial/8250/8250.h:113
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff815fb867)
Location: drivers/tty/serial/8250/8250.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8160063d)
Location: drivers/tty/serial/8250/8250.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81634ba7)
Location: drivers/tty/serial/8250/8250.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81638e22)
Location: drivers/tty/serial/8250/8250.h:109
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81652e03)
Location: drivers/tty/serial/8250/8250.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81657120)
Location: drivers/tty/serial/8250/8250.h:109
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8168784d)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168d52a)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816a9efd)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816afa7a)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8175d0b8)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81760d17)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81777f88)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177bd67)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_read_divisor_id
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8175ba08)
Location: drivers/tty/serial/8250/8250.h:113
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761967)
Location: drivers/tty/serial/8250/8250.h:113
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff817df822)
Location: drivers/tty/serial/8250/8250.h:113
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e59c7)
Location: drivers/tty/serial/8250/8250.h:113
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8191e9fd)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81921a73)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7aa1e)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7e2bc)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a81f52)
Location: drivers/tty/serial/8250/8250.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:dma_rx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac629d)
Location: drivers/tty/serial/8250/8250.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac98bc)
Location: drivers/tty/serial/8250/8250.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acd552)
Location: drivers/tty/serial/8250/8250.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:dma_rx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81b192cd)
Location: drivers/tty/serial/8250/8250.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1c99c)
Location: drivers/tty/serial/8250/8250.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20622)
Location: drivers/tty/serial/8250/8250.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:dma_rx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffff8000108842fc)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088ae90)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892588)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
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
In drivers/tty/serial/8250/8250_core.c (c09836f0)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (c0988a40)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098d7c4)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
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
```
```
In drivers/tty/serial/omap-serial.c (c099e670)
Location: drivers/tty/serial/omap-serial.c:178
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset
  - drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_tx_empty
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:check_modem_status
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
In drivers/tty/serial/8250/8250_core.c (c00000000092b2ac)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000093353c)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffe00054fea0)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000554d4c)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8166f95d)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816754ea)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8164ea8d)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816545ca)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8169dd3d)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a38ba)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816b820d)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bdd4a)
Location: drivers/tty/serial/8250/8250.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_modem_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
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
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:__enable_rsa
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/tty/serial/8250/8250_port.c:serial_icr_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:default_serial_dl_read
```
</details>
</li>
</ul>

## Differences
