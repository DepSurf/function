# Function: <code>__writeb</code>

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
In lib/iomap.c (ffffffff81402a08)
Location: arch/x86/include/asm/io.h:68
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a738)
Location: arch/x86/include/asm/io.h:68
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
In lib/iomap.c (ffffffff814690f8)
Location: arch/x86/include/asm/io.h:68
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815264a0)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff8146e7d8)
Location: arch/x86/include/asm/io.h:68
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81539443)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff8149ab5f)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159ad9d)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff814cfe0f)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d2877)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff814e471f)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ec027)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff815110eb)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161df21)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff81531b5b)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163f9d1)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff8159604b)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ec904)
Location: arch/x86/include/asm/io.h:69
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
In lib/iomap.c (ffffffff815b1adb)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81709f7b)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f82bb)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8_relaxed
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
In lib/iomap.c (ffffffff815bc8eb)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eb769)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dca4b)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8_relaxed
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
In lib/iomap.c (ffffffff8162373b)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817657d3)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186844b)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8_relaxed
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
In lib/iomap.c (ffffffff816f383c)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818998ab)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0e8b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8_relaxed
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
In lib/iomap.c (ffffffff817e57ec)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819e1c5b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b2592c)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8_relaxed
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
In lib/iomap.c (ffffffff8182582c)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a29cd6)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b759ca)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8_relaxed
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
In lib/iomap.c (ffffffff8187723c)
Location: arch/x86/include/asm/io.h:68
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a74ea6)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc9772)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8_relaxed
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
In <code>ppc64el</code>: Absent ⚠️
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
In lib/iomap.c (ffffffff8152a13b)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160b401)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff8151a41b)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fd041)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff815261cb)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81633811)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In lib/iomap.c (ffffffff8153fb4b)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164db41)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
</ul>

## Differences
