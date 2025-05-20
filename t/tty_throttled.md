# Function: <code>tty_throttled</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8153a720)
Location: include/linux/tty.h:380
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff8154263b)
Location: include/linux/tty.h:380
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154eed0)
Location: include/linux/tty.h:380
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81554267)
Location: include/linux/tty.h:380
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81566de0)
Location: include/linux/tty.h:380
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff8156ec7c)
Location: include/linux/tty.h:380
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b750)
Location: include/linux/tty.h:380
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81580f47)
Location: include/linux/tty.h:380
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8157a3b0)
Location: include/linux/tty.h:386
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff815831ec)
Location: include/linux/tty.h:386
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8158f676)
Location: include/linux/tty.h:386
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81594e0a)
Location: include/linux/tty.h:386
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff815ded70)
Location: include/linux/tty.h:389
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff815e7cf1)
Location: include/linux/tty.h:389
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f4176)
Location: include/linux/tty.h:389
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f966a)
Location: include/linux/tty.h:389
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81774944)
Location: include/linux/tty.h:389
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816180b0)
Location: include/linux/tty.h:391
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff81620fd1)
Location: include/linux/tty.h:391
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d0aa)
Location: include/linux/tty.h:391
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8163211d)
Location: include/linux/tty.h:391
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b5084)
Location: include/linux/tty.h:391
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81635280)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff8163e421)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b779)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8165078d)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db5d4)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816693a1)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff8167214c)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8167ffd9)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81685306)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181bff4)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8168baf1)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff8169482f)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2689)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a79c6)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184d3b4)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173db31)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff81747302)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754b29)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81759eaf)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8191fe54)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81759a91)
Location: include/linux/tty.h:403
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff81762c54)
Location: include/linux/tty.h:403
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fe29)
Location: include/linux/tty.h:403
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81774f8f)
Location: include/linux/tty.h:403
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81927555)
Location: include/linux/tty.h:403
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173d931)
Location: include/linux/tty.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff81746911)
Location: include/linux/tty.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817538d9)
Location: include/linux/tty.h:363
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175843f)
Location: include/linux/tty.h:363
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190ac15)
Location: include/linux/tty.h:363
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff817bdfd1)
Location: include/linux/tty.h:249
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff817c7901)
Location: include/linux/tty.h:249
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d6db9)
Location: include/linux/tty.h:249
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dbcdf)
Location: include/linux/tty.h:249
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819ab2c5)
Location: include/linux/tty.h:249
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff818fa310)
Location: include/linux/tty.h:344
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff81904a11)
Location: include/linux/tty.h:344
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81914ec3)
Location: include/linux/tty.h:344
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81918c3d)
Location: include/linux/tty.h:344
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b09075)
Location: include/linux/tty.h:344
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a527a0)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff81a5eb01)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a70113)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a7497d)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c98d71)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a9caa0)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff81aa91a1)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba8d3)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abf60d)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d0010a)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
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
In drivers/tty/tty_ioctl.c (ffffffff81aef570)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff81afbc61)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d623)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b1244d)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db5bbf)
Location: include/linux/tty.h:338
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffff80001085bb88)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffff800010868b38)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087ab70)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffff80001087ec80)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c794)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0963f9c)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (c096de3c)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (c097c9e0)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (c097dde0)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (c0b5f3ec)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0000000008fa900)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (c0000000009085fc)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvsi.c (c00000000091fbe0)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_interrupt
```
```
In drivers/tty/hvc/hvc_console.c (c000000000921bd4)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (c000000000926ff0)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (c000000000b68f30)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffe000535112)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffe00053d988)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054a914)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054e11e)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a15e0)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81651571)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff8165a2af)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816680e9)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166d426)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816319b1)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff8163a62f)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81648469)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164bee6)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817ca904)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8167f931)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff8168866f)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816964c9)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169b806)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81842234)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81699f81)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/vt/selection.c (ffffffff816a2c5f)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0a89)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b3f36)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185c664)
Location: include/linux/tty.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
</details>
</li>
</ul>

## Differences
