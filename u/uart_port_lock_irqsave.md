# Function: <code>uart_port_lock_irqsave</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b1612d)
Location: include/linux/serial_core.h:614
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_update_mctrl
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serial/serial_port.c (ffffffff81b17744)
Location: include/linux/serial_core.h:614
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_runtime_suspend
  - drivers/tty/serial/serial_port.c:serial_port_runtime_resume
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b18a54)
Location: include/linux/serial_core.h:614
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1fffc)
Location: include/linux/serial_core.h:614
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20605)
Location: include/linux/serial_core.h:614
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:dma_rx_complete
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2cdad)
Location: include/linux/serial_core.h:614
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
