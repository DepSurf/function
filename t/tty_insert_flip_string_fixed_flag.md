# Function: <code>tty_insert_flip_string_fixed_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff814ea8e0)
Location: drivers/tty/tty_buffer.c:330
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
```
**Symbols:**

```
ffffffff814ea8e0-ffffffff814ea9b8: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8153b8a0)
Location: drivers/tty/tty_buffer.c:305
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
```
**Symbols:**

```
ffffffff8153b8a0-ffffffff8153b978: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81567f20)
Location: drivers/tty/tty_buffer.c:305
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
```
**Symbols:**

```
ffffffff81567f20-ffffffff81567ff8: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8157b540)
Location: drivers/tty/tty_buffer.c:305
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
```
**Symbols:**

```
ffffffff8157b540-ffffffff8157b612: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff815dff50)
Location: drivers/tty/tty_buffer.c:306
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff815dff50-ffffffff815e0022: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816192a0)
Location: drivers/tty/tty_buffer.c:306
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff816192a0-ffffffff8161937b: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816364e0)
Location: drivers/tty/tty_buffer.c:311
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff816364e0-ffffffff816365bb: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8166a670)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8166a670-ffffffff8166a748: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8168cd60)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8168cd60-ffffffff8168ce38: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173ed80)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8173ed80-ffffffff8173ee58: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8175acb0)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8175acb0-ffffffff8175ad88: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173eb50)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8173eb50-ffffffff8173ec27: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff817bf1e0)
Location: drivers/tty/tty_buffer.c:313
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff817bf1e0-ffffffff817bf2b7: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff818fb7b0)
Location: drivers/tty/tty_buffer.c:314
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff818fb7b0-ffffffff818fb8a1: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_buffer.c (0)
Location: drivers/tty/tty_buffer.c:319
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff820951c0-ffffffff820951f1: tty_insert_flip_string_fixed_flag.cold (STB_LOCAL)
ffffffff81a549f0-ffffffff81a54aeb: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_buffer.c (0)
Location: drivers/tty/tty_buffer.c:319
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff82115ff2-ffffffff82116023: tty_insert_flip_string_fixed_flag.cold (STB_LOCAL)
ffffffff81a9efd0-ffffffff81a9f0cb: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
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
In drivers/tty/tty_buffer.c (ffffffff81af2073)
Location: include/linux/tty_flip.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afd9a0)
Location: include/linux/tty_flip.h:31
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff81b0b0f9)
Location: include/linux/tty_flip.h:31
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b2058d)
Location: include/linux/tty_flip.h:31
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db5b55)
Location: include/linux/tty_flip.h:31
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
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
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffff80001085d400)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_dma_rx_complete
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_dma_rx_complete
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_dma_rx_complete
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffff80001085d400-ffff80001085d4f4: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0965294)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_dma_rx_complete
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_dma_rx_complete
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_dma_rx_complete
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
c0965294-c096535c: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0000000008fc7c0)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
c0000000008fc7c0-c0000000008fc8ec: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffe000536302)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffe000536302-ffffffe0005363c8: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
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
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816527e0)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
```
**Symbols:**

```
ffffffff816527e0-ffffffff816528b8: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81632c20)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff81632c20-ffffffff81632cf8: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81680ba0)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff81680ba0-ffffffff81680c78: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_insert_flip_string_fixed_flag(struct tty_port *port, const unsigned char *chars, char flag, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8169b1f0)
Location: drivers/tty/tty_buffer.c:311
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8169b1f0-ffffffff8169b2c8: tty_insert_flip_string_fixed_flag (STB_GLOBAL)
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
