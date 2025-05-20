# Function: <code>serial_port_out</code>

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
In drivers/tty/serial/8250/8250_core.c (ffffffff8150494d)
Location: include/linux/serial_core.h:257
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81505ecb)
Location: include/linux/serial_core.h:257
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509e10)
Location: include/linux/serial_core.h:257
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81556061)
Location: include/linux/serial_core.h:259
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8155b26c)
Location: include/linux/serial_core.h:259
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155bdc0)
Location: include/linux/serial_core.h:259
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffffffff815827f8)
Location: include/linux/serial_core.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815879fc)
Location: include/linux/serial_core.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff815885a0)
Location: include/linux/serial_core.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81596bf6)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159be8c)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159ca20)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffffffff815fb851)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81601162)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81601d33)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81634b91)
Location: include/linux/serial_core.h:264
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8163a3ba)
Location: include/linux/serial_core.h:264
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163b00c)
Location: include/linux/serial_core.h:264
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81652ded)
Location: include/linux/serial_core.h:276
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816586ea)
Location: include/linux/serial_core.h:276
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81659221)
Location: include/linux/serial_core.h:276
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81687836)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168dbb1)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8168f720)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816a9ee6)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b0101)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b20f0)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8175d0a1)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e4be)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:probe_baud
  - drivers/tty/serial/8250/8250_port.c:probe_baud
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81765e62)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81777f71)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177933e)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:probe_baud
  - drivers/tty/serial/8250/8250_port.c:probe_baud
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81780dc2)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8175b9f1)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761e8d)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81764732)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffff817df80b)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e5eed)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e7a47)
Location: include/linux/serial_core.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/serial_core.c (ffffffff819171c5)
Location: include/linux/serial_core.h:268
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_xchar_out
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8191e9e7)
Location: include/linux/serial_core.h:268
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81925410)
Location: include/linux/serial_core.h:268
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
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
In drivers/tty/serial/serial_core.c (ffffffff81a72615)
Location: include/linux/serial_core.h:591
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_xchar_out
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7aa08)
Location: include/linux/serial_core.h:591
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a81d40)
Location: include/linux/serial_core.h:591
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
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
In drivers/tty/serial/serial_core.c (ffffffff81abced5)
Location: include/linux/serial_core.h:596
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_xchar_out
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac6287)
Location: include/linux/serial_core.h:596
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acd340)
Location: include/linux/serial_core.h:596
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
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
In drivers/tty/serial/serial_core.c (ffffffff81b0fcc5)
Location: include/linux/serial_core.h:675
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_xchar_out
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b192b7)
Location: include/linux/serial_core.h:675
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b20410)
Location: include/linux/serial_core.h:675
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
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
In drivers/tty/serial/8250/8250_core.c (ffff8000108842e8)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088b570)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088d714)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff80001089276c)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (c09836dc)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (c09890a0)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (c098b6f8)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098dac8)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
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
In drivers/tty/serial/8250/8250_core.c (c00000000092b290)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (c000000000933f78)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (c000000000935f6c)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffe00054fe94)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe0005551e4)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe0005578ac)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8166f946)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81675b71)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81677b60)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8164ea76)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81654c51)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81656c40)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8169dd26)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a3f41)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a5f30)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816b81f6)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816be3d1)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c0390)
Location: include/linux/serial_core.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
</details>
</li>
</ul>

## Differences
