# Function: <code>imx_uart_writel</code>

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
In drivers/tty/serial/imx.c (ffff80001089a09c)
Location: drivers/tty/serial/imx.c:284
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_early_putchar
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_putchar
  - drivers/tty/serial/imx.c:imx_uart_rs485_config
  - drivers/tty/serial/imx.c:imx_uart_poll_put_char
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_break_ctl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_stop_rx
  - drivers/tty/serial/imx.c:imx_uart_stop_rx
  - drivers/tty/serial/imx.c:imx_uart_start_rx
  - drivers/tty/serial/imx.c:imx_uart_start_rx
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
In drivers/tty/serial/imx.c (c09960a4)
Location: drivers/tty/serial/imx.c:284
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_early_putchar
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_putchar
  - drivers/tty/serial/imx.c:imx_uart_rs485_config
  - drivers/tty/serial/imx.c:imx_uart_poll_put_char
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_break_ctl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_stop_rx
  - drivers/tty/serial/imx.c:imx_uart_stop_rx
  - drivers/tty/serial/imx.c:imx_uart_start_rx
  - drivers/tty/serial/imx.c:imx_uart_start_rx
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
