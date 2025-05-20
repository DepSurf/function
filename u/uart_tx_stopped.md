# Function: <code>uart_tx_stopped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81500edc)
Location: include/linux/serial_core.h:397
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815089b7)
Location: include/linux/serial_core.h:397
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509b6c)
Location: include/linux/serial_core.h:397
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff8150d39a)
Location: include/linux/serial_core.h:397
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8150fd42)
Location: include/linux/serial_core.h:397
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81554f34)
Location: include/linux/serial_core.h:412
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8155a5b7)
Location: include/linux/serial_core.h:412
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155bafc)
Location: include/linux/serial_core.h:412
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff8155f60a)
Location: include/linux/serial_core.h:412
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8156228e)
Location: include/linux/serial_core.h:412
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff81581b3e)
Location: include/linux/serial_core.h:421
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81586e07)
Location: include/linux/serial_core.h:421
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff815882ef)
Location: include/linux/serial_core.h:421
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff8158bd5e)
Location: include/linux/serial_core.h:421
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8158e9fe)
Location: include/linux/serial_core.h:421
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff81595b02)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159b4ad)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c765)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff8159fea2)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a298a)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff815fa662)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81600713)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81601a65)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff816055d2)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81607b3a)
Location: include/linux/serial_core.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff81633f1e)
Location: include/linux/serial_core.h:432
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816397d7)
Location: include/linux/serial_core.h:432
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163ad22)
Location: include/linux/serial_core.h:432
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff8163fabb)
Location: include/linux/serial_core.h:432
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_wq_proc
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8164120d)
Location: include/linux/serial_core.h:432
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff8165193c)
Location: include/linux/serial_core.h:444
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81657ab7)
Location: include/linux/serial_core.h:444
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658f12)
Location: include/linux/serial_core.h:444
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff8165dccb)
Location: include/linux/serial_core.h:444
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_wq_proc
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165f463)
Location: include/linux/serial_core.h:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff816864ac)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168bc37)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e3f0)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff81692944)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81694a83)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff816a8bbc)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ae1f7)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b09c0)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff816b54e4)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b7623)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff8175ad93)
Location: include/linux/serial_core.h:434
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81760157)
Location: include/linux/serial_core.h:434
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763da0)
Location: include/linux/serial_core.h:434
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff81768fa4)
Location: include/linux/serial_core.h:434
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176b3d3)
Location: include/linux/serial_core.h:434
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/serial_core.c (ffffffff81775e73)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177afd7)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177ed33)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff81783ea4)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81785fb0)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/serial_core.c (ffffffff817595c1)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e637)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8176269a)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff81767794)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81769920)
Location: include/linux/serial_core.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/serial_core.c (ffffffff817dc8c8)
Location: include/linux/serial_core.h:429
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e2a97)
Location: include/linux/serial_core.h:429
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e677e)
Location: include/linux/serial_core.h:429
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff817ec170)
Location: include/linux/serial_core.h:429
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817ef126)
Location: include/linux/serial_core.h:429
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/serial_core.c (ffffffff8191b6a5)
Location: include/linux/serial_core.h:436
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923615)
Location: include/linux/serial_core.h:436
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81925ce7)
Location: include/linux/serial_core.h:436
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff8192c3a4)
Location: include/linux/serial_core.h:436
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192f266)
Location: include/linux/serial_core.h:436
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/serial_core.c (ffffffff81a775ca)
Location: include/linux/serial_core.h:875
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7ff85)
Location: include/linux/serial_core.h:875
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a82737)
Location: include/linux/serial_core.h:875
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff81a893e4)
Location: include/linux/serial_core.h:875
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8d5f6)
Location: include/linux/serial_core.h:875
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/serial_core.c (ffffffff81ac1ed6)
Location: include/linux/serial_core.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/serial_port.c (ffffffff81ac4721)
Location: include/linux/serial_core.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_runtime_resume
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acb595)
Location: include/linux/serial_core.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acdd57)
Location: include/linux/serial_core.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad4b94)
Location: include/linux/serial_core.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad8d76)
Location: include/linux/serial_core.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/serial_core.c (ffffffff81b15696)
Location: include/linux/serial_core.h:980
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:__uart_start
```
```
In drivers/tty/serial/serial_port.c (ffffffff81b175d5)
Location: include/linux/serial_core.h:980
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:__serial_port_busy
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1dd35)
Location: include/linux/serial_core.h:980
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20e27)
Location: include/linux/serial_core.h:980
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff81b28054)
Location: include/linux/serial_core.h:980
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81b2c066)
Location: include/linux/serial_core.h:980
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/serial_core.c (ffff80001087d960)
Location: include/linux/serial_core.h:431
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010887f3c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088be6c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010894e74)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/max310x.c (ffff800010898cc0)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
```
In drivers/tty/serial/imx.c (ffff80001089c500)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089f0fc)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
```
```
In drivers/tty/serial/sccnxp.c (ffff80001089fcf8)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a3838)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5094)
Location: include/linux/serial_core.h:431
Inline: True
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a73bc)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
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
In drivers/tty/serial/serial_core.c (c098270c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:__uart_start
```
```
In drivers/tty/serial/8250/8250_port.c (c0987144)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (c098983c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/amba-pl011.c (c0990e2c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/max310x.c (c0994260)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
```
In drivers/tty/serial/imx.c (c0997e78)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
```
In drivers/tty/serial/meson_uart.c (c0998a8c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
```
```
In drivers/tty/serial/sccnxp.c (c099aa00)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/tty/serial/msm_serial.c (c099caa0)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/tty/serial/omap-serial.c (c09a0a10)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
```
```
In drivers/tty/serial/mvebu-uart.c (c09a206c)
Location: include/linux/serial_core.h:431
Inline: True
```
```
In drivers/tty/serial/owl-uart.c (c09a2f48)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
```
In drivers/tty/serial/rda-uart.c (c09a3ecc)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_interrupt
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
In drivers/tty/serial/serial_core.c (c00000000092959c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:__uart_start
```
```
In drivers/tty/serial/8250/8250_port.c (c000000000930f00)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934950)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:431
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (c00000000093cf20)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffe00054eeb2)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:__uart_start
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000553842)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe00055574a)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffe00055b752)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055c7a2)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/tty/serial/sifive.c (ffffffe00055ded8)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sifive.c:sifive_serial_irq
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
In drivers/tty/serial/serial_core.c (ffffffff8166e61c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81673c67)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81676430)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff8167af44)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d083)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff8164da6c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81652f47)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81655510)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff8165a034)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165c173)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff8169c9fc)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a2037)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a4800)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff816a9324)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816ab463)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/serial_core.c (ffffffff816b753c)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bc6c7)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816bec60)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff816c3784)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c58c3)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
</ul>

## Differences
