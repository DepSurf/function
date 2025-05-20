# Function: <code>tty_port_set_active</code>

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
In drivers/tty/tty_port.c (ffffffff8153c2fe)
Location: include/linux/tty.h:581
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff81553649)
Location: include/linux/tty.h:581
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_close
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
In drivers/tty/tty_port.c (ffffffff8156895e)
Location: include/linux/tty.h:581
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff815800a9)
Location: include/linux/tty.h:581
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff8157c04e)
Location: include/linux/tty.h:608
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff815944b1)
Location: include/linux/tty.h:608
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff815e0a4e)
Location: include/linux/tty.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f91d1)
Location: include/linux/tty.h:614
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff81619cde)
Location: include/linux/tty.h:616
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff816323d9)
Location: include/linux/tty.h:616
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff81636f4e)
Location: include/linux/tty.h:624
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff81650519)
Location: include/linux/tty.h:624
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff8166b1df)
Location: include/linux/tty.h:624
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff81685089)
Location: include/linux/tty.h:624
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff8168d87f)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a7749)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff8173f9cf)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff81759d49)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff8175b9ef)
Location: include/linux/tty.h:627
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff81774e29)
Location: include/linux/tty.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff8173f88f)
Location: include/linux/tty.h:558
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff817581b9)
Location: include/linux/tty.h:558
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff817c00ef)
Location: include/linux/tty_port.h:138
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dba56)
Location: include/linux/tty_port.h:138
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff818fc92f)
Location: include/linux/tty_port.h:184
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191adf4)
Location: include/linux/tty_port.h:184
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff81a55fbf)
Location: include/linux/tty_port.h:186
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a77d42)
Location: include/linux/tty_port.h:186
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff81aa059f)
Location: include/linux/tty_port.h:186
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac2672)
Location: include/linux/tty_port.h:186
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff81af2ffc)
Location: include/linux/tty_port.h:187
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b15e32)
Location: include/linux/tty_port.h:187
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffff80001085e6d0)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffff8000108817f8)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (c09662bc)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (c0981304)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (c0000000008fdc14)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (c000000000927ce0)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffe000537390)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054d90e)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff816532ff)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166d1a9)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff816336ef)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164c549)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff816816bf)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169b589)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
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
In drivers/tty/tty_port.c (ffffffff8169bd0f)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b6339)
Location: include/linux/tty.h:626
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
</details>
</li>
</ul>

## Differences
