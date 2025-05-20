# Function: <code>tty_flip_buffer_push</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff814ea5f0)
Location: drivers/tty/tty_buffer.c:539
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff814ea5f0-ffffffff814ea61d: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8153b5c0)
Location: drivers/tty/tty_buffer.c:529
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff8153b5c0-ffffffff8153b5ed: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81567c50)
Location: drivers/tty/tty_buffer.c:529
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff81567c50-ffffffff81567c7d: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8157b200)
Location: drivers/tty/tty_buffer.c:544
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff8157b200-ffffffff8157b22d: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff815dfc10)
Location: drivers/tty/tty_buffer.c:545
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff815dfc10-ffffffff815dfc3d: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81618e90)
Location: drivers/tty/tty_buffer.c:545
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff81618e90-ffffffff81618ebd: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816360a0)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff816360a0-ffffffff816360cd: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8166a2e0)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8166a2e0-ffffffff8166a30d: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8168c9d0)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8168c9d0-ffffffff8168c9fd: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173ef90)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8173ef90-ffffffff8173efbd: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8175aec0)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8175aec0-ffffffff8175aeed: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173ed60)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8173ed60-ffffffff8173ed8d: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff817bf4f0)
Location: drivers/tty/tty_buffer.c:567
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff817bf4f0-ffffffff817bf51d: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff818fb440)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff818fb440-ffffffff818fb479: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a54690)
Location: drivers/tty/tty_buffer.c:599
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff81a54690-ffffffff81a546c9: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a9ec70)
Location: drivers/tty/tty_buffer.c:599
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff81a9ec70-ffffffff81a9eca9: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81af1790)
Location: drivers/tty/tty_buffer.c:528
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff81af1790-ffffffff81af17c9: tty_flip_buffer_push (STB_GLOBAL)
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
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffff80001085d048)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_dma_rx_complete
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_dma_rx_complete
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffff80001085d048-ffff80001085d090: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0964ebc)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_dma_rx_complete
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
c0964ebc-c0964efc: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0000000008fc1f0)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvsi.c:hvsi_unthrottle
  - drivers/tty/hvc/hvsi.c:hvsi_interrupt
  - drivers/tty/hvc/hvsi.c:hvsi_interrupt
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
c0000000008fc1f0-c0000000008fc248: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffe000535fcc)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sifive.c:sifive_serial_irq
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffe000535fcc-ffffffe00053600c: tty_flip_buffer_push (STB_GLOBAL)
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
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81652450)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81652450-ffffffff8165247d: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81632890)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff81632890-ffffffff816328bd: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81680810)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff81680810-ffffffff8168083d: tty_flip_buffer_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_flip_buffer_push(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8169ae60)
Location: drivers/tty/tty_buffer.c:554
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff8169ae60-ffffffff8169ae8d: tty_flip_buffer_push (STB_GLOBAL)
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
