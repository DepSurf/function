# Function: <code>irq_canonicalize</code>

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
In drivers/tty/serial/serial_core.c (ffffffff81503034)
Location: arch/x86/include/asm/irq.h:13
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81fa7195)
Location: arch/x86/include/asm/irq.h:13
Inline: True
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
In drivers/tty/serial/serial_core.c (ffffffff8155463e)
Location: arch/x86/include/asm/irq.h:13
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81fd35d5)
Location: arch/x86/include/asm/irq.h:13
Inline: True
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
In drivers/tty/serial/serial_core.c (ffffffff8158120e)
Location: arch/x86/include/asm/irq.h:13
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff82010f95)
Location: arch/x86/include/asm/irq.h:13
Inline: True
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
In drivers/tty/serial/serial_core.c (ffffffff81595116)
Location: arch/x86/include/asm/irq.h:13
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff820f2a9d)
Location: arch/x86/include/asm/irq.h:13
Inline: True
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
In drivers/tty/serial/serial_core.c (ffffffff815f9c66)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff826fc299)
Location: arch/x86/include/asm/irq.h:14
Inline: True
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
In drivers/tty/serial/serial_core.c (ffffffff8163355f)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8272658f)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff81650fc1)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff828de773)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff81685a7c)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff828f90a1)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff816a813c)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff82901fa4)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff8175a23c)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff82d191ea)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff8177531c)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83006eb3)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff8175884c)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83211a9d)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff817dca1c)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff832fabab)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff8191b81d)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff834b34d8)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff81a776fe)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83eedfcb)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff81ac202e)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83713c22)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff81b157ee)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83947682)
Location: arch/x86/include/asm/irq.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/irq.h:14
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (0)
Location: include/asm-generic/irq.h:14
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: arch/powerpc/include/asm/irq.h:31
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/irq.h:14
Inline: True
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
In drivers/tty/serial/serial_core.c (ffffffff8166db9c)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff828e978b)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff8164cfec)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff828e0c3a)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff8169bf7c)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff828fd2c7)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
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
In drivers/tty/serial/serial_core.c (ffffffff816b6abc)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff82903006)
Location: arch/x86/include/asm/irq.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
```
</details>
</li>
</ul>

## Differences
