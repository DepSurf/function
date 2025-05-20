# Function: <code>sccnxp_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8150e786)
Location: drivers/tty/serial/sccnxp.c:220
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81561e23)
Location: drivers/tty/serial/sccnxp.c:220
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8158e593)
Location: drivers/tty/serial/sccnxp.c:220
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff815a2622)
Location: drivers/tty/serial/sccnxp.c:220
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81608427)
Location: drivers/tty/serial/sccnxp.c:216
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81641a57)
Location: drivers/tty/serial/sccnxp.c:216
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165e7a0)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
ffffffff8165e7a0-ffffffff8165e7de: sccnxp_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81693d90)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
ffffffff81693d90-ffffffff81693dcb: sccnxp_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816b6930)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
ffffffff816b6930-ffffffff816b696b: sccnxp_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8176be4f)
Location: drivers/tty/serial/sccnxp.c:235
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81786a2f)
Location: drivers/tty/serial/sccnxp.c:235
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8176a38f)
Location: drivers/tty/serial/sccnxp.c:235
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff817eefca)
Location: drivers/tty/serial/sccnxp.c:235
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
**Symbols:**

```
ffffffff817ed670-ffffffff817ed6d2: sccnxp_write (STB_LOCAL)
ffffffff81cfa4ae-ffffffff81cfa4cd: sccnxp_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8192f0fa)
Location: drivers/tty/serial/sccnxp.c:235
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
**Symbols:**

```
ffffffff8192d5d0-ffffffff8192d640: sccnxp_write (STB_LOCAL)
ffffffff81ec26e7-ffffffff81ec2706: sccnxp_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81a8d46a)
Location: drivers/tty/serial/sccnxp.c:235
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
**Symbols:**

```
ffffffff81a8b7e0-ffffffff81a8b850: sccnxp_write (STB_LOCAL)
ffffffff820961fc-ffffffff8209621b: sccnxp_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81ad8bea)
Location: drivers/tty/serial/sccnxp.c:235
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
**Symbols:**

```
ffffffff81ad6fb0-ffffffff81ad7020: sccnxp_write (STB_LOCAL)
ffffffff82117123-ffffffff82117142: sccnxp_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81b2beda)
Location: drivers/tty/serial/sccnxp.c:235
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
**Symbols:**

```
ffffffff81b2a250-ffffffff81b2a2c0: sccnxp_write (STB_LOCAL)
ffffffff821f4e7d-ffffffff821f4e9c: sccnxp_write.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffff80001089f8f0)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
ffff80001089f8f0-ffff80001089f950: sccnxp_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c099990c)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
c099990c-c0999980: sccnxp_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c00000000093c610)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
c00000000093c610-c00000000093c69c: sccnxp_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffe00055c13a)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
ffffffe00055c13a-ffffffe00055c1b8: sccnxp_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8167c390)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
ffffffff8167c390-ffffffff8167c3cb: sccnxp_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165b480)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
ffffffff8165b480-ffffffff8165b4bb: sccnxp_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816aa770)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
ffffffff816aa770-ffffffff816aa7ab: sccnxp_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port *port, u8 reg, u8 v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816c4bd0)
Location: drivers/tty/serial/sccnxp.c:239
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_set_bit
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_enable_irq
```
**Symbols:**

```
ffffffff816c4bd0-ffffffff816c4c0b: sccnxp_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
