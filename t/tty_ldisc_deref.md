# Function: <code>tty_ldisc_deref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff814e9890)
Location: drivers/tty/tty_ldisc.c:300
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff814e9890-ffffffff814e98a8: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8153b12d)
Location: drivers/tty/tty_ldisc.c:311
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8153a970-ffffffff8153a988: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815677dd)
Location: drivers/tty/tty_ldisc.c:311
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81567030-ffffffff81567048: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8157af2d)
Location: drivers/tty/tty_ldisc.c:314
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8157a610-ffffffff8157a628: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815df913)
Location: drivers/tty/tty_ldisc.c:315
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff815defe0-ffffffff815deff8: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81618ba4)
Location: drivers/tty/tty_ldisc.c:301
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81618300-ffffffff81618318: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81635db4)
Location: drivers/tty/tty_ldisc.c:301
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff816354d0-ffffffff816354e8: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81669f55)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81669620-ffffffff81669638: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8168c685)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8168bd60-ffffffff8168bd78: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e6c6)
Location: drivers/tty/tty_ldisc.c:305
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tiocsti
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8173de30-ffffffff8173de48: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8175a626)
Location: drivers/tty/tty_ldisc.c:304
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tiocsti
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81759d90-ffffffff81759da8: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e4d6)
Location: drivers/tty/tty_ldisc.c:305
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8173dc30-ffffffff8173dc48: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff817beac6)
Location: drivers/tty/tty_ldisc.c:290
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff817be1c0-ffffffff817be1d8: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff818faeb5)
Location: drivers/tty/tty_ldisc.c:280
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff818fa5e0-ffffffff818fa5fe: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a54095)
Location: drivers/tty/tty_ldisc.c:280
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_lookahead_buf
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81a536a0-ffffffff81a536be: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a9e5b5)
Location: drivers/tty/tty_ldisc.c:279
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_lookahead_buf
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81a9dae0-ffffffff81a9dafe: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81af10d5)
Location: drivers/tty/tty_ldisc.c:279
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_lookahead_buf
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81af05d0-ffffffff81af05ee: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffff80001085cba8)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffff80001085bd78-ffff80001085bda8: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0964ba8)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
c09642b8-c09642dc: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0000000008fbcc8)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
c0000000008fade0-c0000000008fae1c: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffe000535c7a)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffe000535390-ffffffe0005353be: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81652105)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff816517e0-ffffffff816517f8: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81632545)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81631c20-ffffffff81631c38: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff816804c5)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8167fba0-ffffffff8167fbb8: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_deref(struct tty_ldisc *ld);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8169ab15)
Location: drivers/tty/tty_ldisc.c:310
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8169a1f0-ffffffff8169a208: tty_ldisc_deref (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
