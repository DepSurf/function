# Function: <code>tty_ldisc_ref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff814e9830)
Location: drivers/tty/tty_ldisc.c:279
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff814e9830-ffffffff814e9882: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8153a990)
Location: drivers/tty/tty_ldisc.c:290
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8153a990-ffffffff8153a9e2: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81567050)
Location: drivers/tty/tty_ldisc.c:290
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81567050-ffffffff815670a2: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8157a630)
Location: drivers/tty/tty_ldisc.c:293
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8157a630-ffffffff8157a67b: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815df000)
Location: drivers/tty/tty_ldisc.c:294
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff815df000-ffffffff815df04b: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81618320)
Location: drivers/tty/tty_ldisc.c:280
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81618320-ffffffff81618361: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff816354f0)
Location: drivers/tty/tty_ldisc.c:280
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff816354f0-ffffffff81635531: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81669640)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81669640-ffffffff8166968d: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8168bd80)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8168bd80-ffffffff8168bdcd: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e645)
Location: drivers/tty/tty_ldisc.c:284
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8173de50-ffffffff8173de9d: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8175a5a5)
Location: drivers/tty/tty_ldisc.c:283
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81759db0-ffffffff81759dfd: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e455)
Location: drivers/tty/tty_ldisc.c:284
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8173dc50-ffffffff8173dc9d: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff817bea45)
Location: drivers/tty/tty_ldisc.c:269
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff817be1e0-ffffffff817be22d: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff818fae35)
Location: drivers/tty/tty_ldisc.c:260
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff818fa600-ffffffff818fa63f: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a54015)
Location: drivers/tty/tty_ldisc.c:260
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_lookahead_buf
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81a536d0-ffffffff81a5370f: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a9e535)
Location: drivers/tty/tty_ldisc.c:259
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_lookahead_buf
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81a9db10-ffffffff81a9db63: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81af1055)
Location: drivers/tty/tty_ldisc.c:259
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_port.c:tty_port_default_lookahead_buf
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81af0600-ffffffff81af0653: tty_ldisc_ref (STB_GLOBAL)
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
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffff80001085bda8)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffff80001085bda8-ffff80001085be08: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c09642dc)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
c09642dc-c0964328: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0000000008fae20)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
c0000000008fae20-c0000000008faec0: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffe0005353be)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffe0005353be-ffffffe000535414: tty_ldisc_ref (STB_GLOBAL)
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
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81651800)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81651800-ffffffff8165184d: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81631c40)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff81631c40-ffffffff81631c8d: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8167fbc0)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8167fbc0-ffffffff8167fc0d: tty_ldisc_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tty_ldisc *tty_ldisc_ref(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8169a210)
Location: drivers/tty/tty_ldisc.c:289
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_wakeup
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:tty_set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_flush
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/serial/serial_core.c:uart_handle_dcd_change
```
**Symbols:**

```
ffffffff8169a210-ffffffff8169a25d: tty_ldisc_ref (STB_GLOBAL)
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
