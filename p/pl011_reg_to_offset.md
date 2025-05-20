# Function: <code>pl011_reg_to_offset</code>

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
In drivers/tty/serial/amba-pl011.c (ffff8000108944a0)
Location: drivers/tty/serial/amba-pl011.c:283
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_putchar
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown_channel
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_allocate_irq
  - drivers/tty/serial/amba-pl011.c:pl011_put_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_set_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_char
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_probe
  - drivers/tty/serial/amba-pl011.c:pl011_dma_probe
  - drivers/tty/serial/amba-pl011.c:pl011_read
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
In drivers/tty/serial/amba-pl011.c (c0990554)
Location: drivers/tty/serial/amba-pl011.c:283
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_putchar
  - drivers/tty/serial/amba-pl011.c:pl011_console_putchar
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_allocate_irq
  - drivers/tty/serial/amba-pl011.c:pl011_put_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_put_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_set_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_get_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_tx_empty
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_char
  - drivers/tty/serial/amba-pl011.c:pl011_tx_char
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_probe
  - drivers/tty/serial/amba-pl011.c:pl011_dma_probe
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
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
