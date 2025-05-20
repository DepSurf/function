# Function: <code>__tty_insert_flip_char</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8157b6e0)
Location: drivers/tty/tty_buffer.c:373
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff8157b6e0-ffffffff8157b74f: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff815e00f0)
Location: drivers/tty/tty_buffer.c:374
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff815e00f0-ffffffff815e015f: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81619380)
Location: drivers/tty/tty_buffer.c:374
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff81619380-ffffffff816193ef: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816365c0)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff816365c0-ffffffff8163662f: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8166a810)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff8166a810-ffffffff8166a880: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8168cf00)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff8168cf00-ffffffff8168cf70: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173ef20)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff8173ef20-ffffffff8173ef90: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8175ae50)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff8175ae50-ffffffff8175aeba: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173ecf0)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff8173ecf0-ffffffff8173ed5a: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff817bf380)
Location: drivers/tty/tty_buffer.c:387
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff817bf380-ffffffff817bf3ea: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff818fba20)
Location: drivers/tty/tty_buffer.c:388
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff818fba20-ffffffff818fba96: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a54c3f)
Location: drivers/tty/tty_buffer.c:393
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff82095206-ffffffff8209521b: __tty_insert_flip_char.cold (STB_LOCAL)
ffffffff81a54c10-ffffffff81a54c99: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a9f3ff)
Location: drivers/tty/tty_buffer.c:393
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff82116093-ffffffff821160a8: __tty_insert_flip_char.cold (STB_LOCAL)
ffffffff81a9f3d0-ffffffff81a9f454: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffff80001085d4f8)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
**Symbols:**

```
ffff80001085d4f8-ffff80001085d584: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0965444)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/rda-uart.c:rda_interrupt
```
**Symbols:**

```
c0965444-c09654b4: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0000000008fca60)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvsi.c:hvsi_insert_chars
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
c0000000008fca60-c0000000008fcb04: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffe000536580)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffe000536580-ffffffe0005365ea: __tty_insert_flip_char (STB_GLOBAL)
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
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81652980)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff81652980-ffffffff816529f0: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81632dc0)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff81632dc0-ffffffff81632e30: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81680d40)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff81680d40-ffffffff81680db0: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __tty_insert_flip_char(struct tty_port *port, unsigned char ch, char flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8169b390)
Location: drivers/tty/tty_buffer.c:379
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
**Symbols:**

```
ffffffff8169b390-ffffffff8169b400: __tty_insert_flip_char (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
