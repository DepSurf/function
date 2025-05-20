# Function: <code>tty_io_error</code>

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
In drivers/tty/tty_io.c (ffffffff8153134d)
Location: include/linux/tty.h:375
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff8153c665)
Location: include/linux/tty.h:375
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff8153dbf7)
Location: include/linux/tty.h:375
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff815549d9)
Location: include/linux/tty.h:375
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff8155da9d)
Location: include/linux/tty.h:375
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff81568cc5)
Location: include/linux/tty.h:375
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff8156a247)
Location: include/linux/tty.h:375
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff815815a9)
Location: include/linux/tty.h:375
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff815729ad)
Location: include/linux/tty.h:381
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff8157c395)
Location: include/linux/tty.h:381
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff8157e7ad)
Location: include/linux/tty.h:381
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff815952d6)
Location: include/linux/tty.h:381
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff815d6d2d)
Location: include/linux/tty.h:384
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff815e0dc5)
Location: include/linux/tty.h:384
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff815e33a4)
Location: include/linux/tty.h:384
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff815fa064)
Location: include/linux/tty.h:384
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff8160fd4c)
Location: include/linux/tty.h:386
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff8161a065)
Location: include/linux/tty.h:386
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff8161c674)
Location: include/linux/tty.h:386
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81633900)
Location: include/linux/tty.h:386
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff8162cbfc)
Location: include/linux/tty.h:393
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff816372e5)
Location: include/linux/tty.h:393
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff816398f4)
Location: include/linux/tty.h:393
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81651571)
Location: include/linux/tty.h:393
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff81662d7c)
Location: include/linux/tty.h:393
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff8166b560)
Location: include/linux/tty.h:393
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff8166dc07)
Location: include/linux/tty.h:393
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff816860a2)
Location: include/linux/tty.h:393
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff816853ec)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff8168dc00)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff816901f7)
Location: include/linux/tty.h:395
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a87b2)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff817347b1)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff8173fee0)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff81742947)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175aaa2)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff81750ca9)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff8175be10)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff8175e7e7)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81775b82)
Location: include/linux/tty.h:398
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff817349d9)
Location: include/linux/tty.h:358
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff8173fcb0)
Location: include/linux/tty.h:358
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff8174261e)
Location: include/linux/tty.h:358
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81759192)
Location: include/linux/tty.h:358
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff817b5339)
Location: include/linux/tty.h:244
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff817c0450)
Location: include/linux/tty.h:244
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff817c305e)
Location: include/linux/tty.h:244
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dc372)
Location: include/linux/tty.h:244
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff818f1259)
Location: include/linux/tty.h:339
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff818fcc10)
Location: include/linux/tty.h:339
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff818ff46e)
Location: include/linux/tty.h:339
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191b191)
Location: include/linux/tty.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff81a4a41d)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff81a562e0)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff81a5882e)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a77021)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff81a94639)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff81aa08c0)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff81aa2e4e)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac1931)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff81ae7204)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff81af3320)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff81af57be)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b150f1)
Location: include/linux/tty.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffff80001085048c)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffff80001085eb8c)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffff800010862adc)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffff80001088281c)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (c095d780)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (c0965f14)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (c0968a38)
Location: include/linux/tty.h:395
Inline: True
```
```
In drivers/tty/serial/serial_core.c (c0982280)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (c0000000008eeae8)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (c0000000008fe0f8)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (c000000000901c08)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (c0000000009290f4)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffe00052da1e)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffe000537040)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffe000539b56)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054ebc6)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff8164ae6c)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff81653680)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff81655c77)
Location: include/linux/tty.h:395
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166e212)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff8162b2bc)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff81633a70)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff81636017)
Location: include/linux/tty.h:395
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164d662)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff8167922c)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff81681a40)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff81684037)
Location: include/linux/tty.h:395
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169c5f2)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
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
In drivers/tty/tty_io.c (ffffffff8169387c)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_port.c (ffffffff8169c090)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/pty.c (ffffffff8169e257)
Location: include/linux/tty.h:395
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b7132)
Location: include/linux/tty.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
```
</details>
</li>
</ul>

## Differences
