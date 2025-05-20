# Function: <code>__writeq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap_copy.c (ffffffff8149ae29)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815306ab)
Location: arch/x86/include/asm/io.h:100
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff81530dcd)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159ac29)
Location: arch/x86/include/asm/io.h:100
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
In lib/iomap_copy.c (ffffffff814d00d9)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8156610b)
Location: arch/x86/include/asm/io.h:100
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8156676a)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d27e7)
Location: arch/x86/include/asm/io.h:100
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
In lib/iomap_copy.c (ffffffff814e49f9)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8157db7b)
Location: arch/x86/include/asm/io.h:100
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8157e1d9)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ebf97)
Location: arch/x86/include/asm/io.h:100
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
In lib/iomap_copy.c (ffffffff81511398)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815ae0fe)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815ae860)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161dde7)
Location: arch/x86/include/asm/io.h:98
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
In lib/iomap_copy.c (ffffffff81531e08)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815cf07e)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815cf7e0)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163f897)
Location: arch/x86/include/asm/io.h:98
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
In lib/iomap_copy.c (ffffffff81596348)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff81678a4b)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff816790d1)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ec8c3)
Location: arch/x86/include/asm/io.h:98
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
In lib/iomap_copy.c (ffffffff815b1dd8)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff81698b1b)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff81699151)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81709f45)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f837d)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le_relaxed
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
In lib/iomap_copy.c (ffffffff815bcbe8)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8167b93b)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8167bf5f)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eb625)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcb0d)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le_relaxed
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
In lib/iomap_copy.c (ffffffff81623ea8)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff816f0558)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff816f0d90)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81765709)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186850d)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le_relaxed
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
In lib/iomap_copy.c (ffffffff816f4288)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8181b9d4)
Location: arch/x86/include/asm/io.h:100
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8181c6b2)
Location: arch/x86/include/asm/io.h:100
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8189988c)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0f4d)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le_relaxed
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
In lib/iomap_copy.c (ffffffff817e62d8)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8194af54)
Location: arch/x86/include/asm/io.h:100
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8194bce2)
Location: arch/x86/include/asm/io.h:100
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819e1c3c)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b257d4)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
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
In lib/iomap_copy.c (ffffffff818262a8)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8198f554)
Location: arch/x86/include/asm/io.h:100
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8199027f)
Location: arch/x86/include/asm/io.h:100
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a29c87)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b7593b)
Location: arch/x86/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
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
In lib/iomap_copy.c (ffffffff81877cb8)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff819d9474)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff819da1ef)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a74e57)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
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
In lib/iomap_copy.c (ffffffff8152a3e8)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815c308e)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815c37f0)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160b2c7)
Location: arch/x86/include/asm/io.h:98
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
In lib/iomap_copy.c (ffffffff8151a6c8)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fcf07)
Location: arch/x86/include/asm/io.h:98
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
In lib/iomap_copy.c (ffffffff81526478)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815c361e)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815c3d80)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816336d7)
Location: arch/x86/include/asm/io.h:98
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
In lib/iomap_copy.c (ffffffff8153fdf8)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815dd1be)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815dd920)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164da07)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
</ul>

## Differences
