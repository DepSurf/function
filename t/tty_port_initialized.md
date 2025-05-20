# Function: <code>tty_port_initialized</code>

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
In drivers/tty/tty_port.c (ffffffff8153c8de)
Location: include/linux/tty.h:615
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff81550cbe)
Location: include/linux/tty.h:615
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_close
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_startup
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
In drivers/tty/tty_port.c (ffffffff81568f2e)
Location: include/linux/tty.h:615
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157d543)
Location: include/linux/tty.h:615
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8157c61e)
Location: include/linux/tty.h:642
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8159178a)
Location: include/linux/tty.h:642
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff815e105e)
Location: include/linux/tty.h:648
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f625a)
Location: include/linux/tty.h:648
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8161a2ee)
Location: include/linux/tty.h:650
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8162f46a)
Location: include/linux/tty.h:650
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8163756e)
Location: include/linux/tty.h:658
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164d5ea)
Location: include/linux/tty.h:658
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8166b7f2)
Location: include/linux/tty.h:658
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff81682110)
Location: include/linux/tty.h:658
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8168de92)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a47a0)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff817401b2)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817546f4)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175800e)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_do_autoconfig
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8175c0e2)
Location: include/linux/tty.h:652
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176f964)
Location: include/linux/tty.h:652
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff817730ce)
Location: include/linux/tty.h:652
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_do_autoconfig
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177b6d0)
Location: include/linux/tty.h:652
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
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
In drivers/tty/tty_port.c (ffffffff8173ff82)
Location: include/linux/tty.h:583
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753444)
Location: include/linux/tty.h:583
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81756b3e)
Location: include/linux/tty.h:583
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175ed20)
Location: include/linux/tty.h:583
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
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
In drivers/tty/tty_port.c (ffffffff817c0722)
Location: include/linux/tty_port.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d6834)
Location: include/linux/tty_port.h:163
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff817da33e)
Location: include/linux/tty_port.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e36ce)
Location: include/linux/tty_port.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
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
In drivers/tty/tty_port.c (ffffffff818fcf45)
Location: include/linux/tty_port.h:209
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff819148f0)
Location: include/linux/tty_port.h:209
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff819190a7)
Location: include/linux/tty_port.h:209
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8192241f)
Location: include/linux/tty_port.h:209
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
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
In drivers/tty/tty_port.c (ffffffff81a56625)
Location: include/linux/tty_port.h:211
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6f9c0)
Location: include/linux/tty_port.h:211
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a73377)
Location: include/linux/tty_port.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7eccf)
Location: include/linux/tty_port.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
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
In drivers/tty/tty_port.c (ffffffff81aa0c05)
Location: include/linux/tty_port.h:211
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba170)
Location: include/linux/tty_port.h:211
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac0f32)
Location: include/linux/tty_port.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81aca27f)
Location: include/linux/tty_port.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
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
In drivers/tty/tty_port.c (ffffffff81af3665)
Location: include/linux/tty_port.h:212
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0cea0)
Location: include/linux/tty_port.h:212
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b14521)
Location: include/linux/tty_port.h:212
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1d35f)
Location: include/linux/tty_port.h:212
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
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
In drivers/tty/tty_port.c (ffff80001085eef4)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffff80001087cc6c)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (c09661f0)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (c097da74)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (c0000000008fe584)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (c000000000923600)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffe0005372d6)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054f2bc)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff81653912)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166a200)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff81633cfc)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff81649370)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff81681cd2)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff816985e0)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8169c319)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b2b60)
Location: include/linux/tty.h:660
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
</details>
</li>
</ul>

## Differences
