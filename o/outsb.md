# Function: <code>outsb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81402a1e)
Location: arch/x86/include/asm/io.h:316
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
In lib/iomap.c (ffffffff8144a751)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81550556)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
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
In lib/iomap.c (ffffffff81469111)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cdd6)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
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
In lib/iomap.c (ffffffff8146e7f3)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8159103d)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
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
In lib/iomap.c (ffffffff8149ab7a)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4fd6)
Location: arch/x86/include/asm/io.h:348
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
In lib/iomap.c (ffffffff814cfe2a)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162dca9)
Location: arch/x86/include/asm/io.h:333
Inline: True
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
In lib/iomap.c (ffffffff814e473a)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c277)
Location: arch/x86/include/asm/io.h:342
Inline: True
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
In lib/iomap.c (ffffffff81511106)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81681062)
Location: arch/x86/include/asm/io.h:339
Inline: True
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
In lib/iomap.c (ffffffff81531b76)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3712)
Location: arch/x86/include/asm/io.h:339
Inline: True
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
In lib/iomap.c (ffffffff81596070)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755c76)
Location: arch/x86/include/asm/io.h:334
Inline: True
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
In lib/iomap.c (ffffffff815b1b00)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770ee6)
Location: arch/x86/include/asm/io.h:334
Inline: True
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
In lib/iomap.c (ffffffff815bc910)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817549a6)
Location: arch/x86/include/asm/io.h:334
Inline: True
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
In lib/iomap.c (ffffffff81623760)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d8066)
Location: arch/x86/include/asm/io.h:334
Inline: True
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
In lib/iomap.c (ffffffff816f386c)
Location: arch/x86/include/asm/io.h:305
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8191631f)
Location: arch/x86/include/asm/io.h:305
Inline: True
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
In lib/iomap.c (ffffffff817e581c)
Location: arch/x86/include/asm/io.h:296
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a71a09)
Location: arch/x86/include/asm/io.h:296
Inline: True
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
In lib/iomap.c (ffffffff8182585c)
Location: arch/x86/include/asm/io.h:296
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc2b9)
Location: arch/x86/include/asm/io.h:296
Inline: True
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
In lib/iomap.c (ffffffff8187726c)
Location: arch/x86/include/asm/io.h:291
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0f009)
Location: arch/x86/include/asm/io.h:291
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In lib/iomap.c (c0000000007e51b8)
Location: arch/powerpc/include/asm/io-defs.h:49
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In lib/iomap.c (ffffffff8152a156)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81669172)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8151a436)
Location: arch/x86/include/asm/io.h:339
Inline: True
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
In lib/iomap.c (ffffffff815261e6)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697552)
Location: arch/x86/include/asm/io.h:339
Inline: True
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
In lib/iomap.c (ffffffff8153fb66)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1c12)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
</details>
</li>
</ul>

## Differences
