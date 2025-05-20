# Function: <code>owl_uart_read</code>

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
In drivers/tty/serial/owl-uart.c (ffff8000108a6f0c)
Location: drivers/tty/serial/owl-uart.c:85
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_tx_empty
  - drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl
  - drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl
  - drivers/tty/serial/owl-uart.c:owl_uart_set_mctrl
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
In drivers/tty/serial/owl-uart.c (c09a2808)
Location: drivers/tty/serial/owl-uart.c:85
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_tx_empty
  - drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl
  - drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl
  - drivers/tty/serial/owl-uart.c:owl_uart_set_mctrl
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
