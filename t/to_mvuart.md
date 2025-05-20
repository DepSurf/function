# Function: <code>to_mvuart</code>

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
In drivers/tty/serial/mvebu-uart.c (0)
Location: drivers/tty/serial/mvebu-uart.c:138
Inline: True
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
In drivers/tty/serial/mvebu-uart.c (c09a1eec)
Location: drivers/tty/serial/mvebu-uart.c:138
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_putchar
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_put_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_get_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_shutdown
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_shutdown
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_isr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_isr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_isr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_tx
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
