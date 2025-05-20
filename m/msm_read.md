# Function: <code>msm_read</code>

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
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/msm_serial.c (ffff8000108a327c)
Location: drivers/tty/serial/msm_serial.c:196
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_tx_empty
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/msm_serial.c (c099bf48)
Location: drivers/tty/serial/msm_serial.c:196
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_tx_empty
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
</details>
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
