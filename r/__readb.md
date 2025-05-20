# Function: <code>__readb</code>

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
In lib/iomap.c (ffffffff81402905)
Location: arch/x86/include/asm/io.h:60
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
In lib/iomap.c (ffffffff8144a635)
Location: arch/x86/include/asm/io.h:60
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
In lib/iomap.c (ffffffff81468ff5)
Location: arch/x86/include/asm/io.h:60
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525dff)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff8146e6d5)
Location: arch/x86/include/asm/io.h:60
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815389c4)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff8149aa0c)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159a25d)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff814cfcbc)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d1b27)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff814e45cc)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815eb147)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff81510f98)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161cf3d)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff81531a08)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163e9ed)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff81595698)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ebafe)
Location: arch/x86/include/asm/io.h:61
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
In lib/iomap.c (ffffffff815b1128)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8170915a)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f83bb)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8_relaxed
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
In lib/iomap.c (ffffffff815bbf38)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ea784)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcb4b)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8_relaxed
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
In lib/iomap.c (ffffffff81622d88)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81764580)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186854b)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8_relaxed
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
In lib/iomap.c (ffffffff816f3749)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8189868f)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0f8b)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8_relaxed
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
In lib/iomap.c (ffffffff817e56e9)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819e09cf)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b2565e)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8_relaxed
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
In lib/iomap.c (ffffffff81825729)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a287ac)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b7575b)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8_relaxed
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
In lib/iomap.c (ffffffff81877139)
Location: arch/x86/include/asm/io.h:60
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a7397c)
Location: arch/x86/include/asm/io.h:60
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc9548)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8_relaxed
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
In lib/iomap.c (ffffffff81529fe8)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160a41d)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff8151a2c8)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fc05d)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff81526078)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163282d)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In lib/iomap.c (ffffffff8153f9f8)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164cb5d)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
</details>
</li>
</ul>

## Differences
