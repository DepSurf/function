# Function: <code>acpi_hest_get_next</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff817886d3)
Location: include/acpi/ghes.h:111
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff8159f856)
Location: include/acpi/ghes.h:112
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
```
In drivers/firmware/efi/cper.c (ffffffff817feb71)
Location: include/acpi/ghes.h:112
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff815d74a6)
Location: include/acpi/ghes.h:111
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81848371)
Location: include/acpi/ghes.h:111
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff815f0c26)
Location: include/acpi/ghes.h:111
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818745c1)
Location: include/acpi/ghes.h:111
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff81622a27)
Location: include/acpi/ghes.h:111
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818b882e)
Location: include/acpi/ghes.h:111
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff816444f7)
Location: include/acpi/ghes.h:111
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb22e)
Location: include/acpi/ghes.h:111
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff816f173e)
Location: include/acpi/ghes.h:114
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff819bfae2)
Location: include/acpi/ghes.h:114
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff8170eade)
Location: include/acpi/ghes.h:132
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81c2c87a)
Location: include/acpi/ghes.h:132
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff816f020a)
Location: include/acpi/ghes.h:132
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81c1eba3)
Location: include/acpi/ghes.h:132
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff8176a2fa)
Location: include/acpi/ghes.h:132
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81d30136)
Location: include/acpi/ghes.h:132
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff8189edd5)
Location: include/acpi/ghes.h:132
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81efc461)
Location: include/acpi/ghes.h:132
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff819e812d)
Location: include/acpi/ghes.h:113
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81d65c0c)
Location: include/acpi/ghes.h:113
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff81a3084d)
Location: include/acpi/ghes.h:113
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81dd0d3c)
Location: include/acpi/ghes.h:113
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff81a7bd89)
Location: include/acpi/ghes.h:117
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81e89aec)
Location: include/acpi/ghes.h:117
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffff8000107af668)
Location: include/acpi/ghes.h:111
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffff800010b5e48c)
Location: include/acpi/ghes.h:111
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff8184592e)
Location: include/acpi/ghes.h:111
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff81638337)
Location: include/acpi/ghes.h:111
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818e008e)
Location: include/acpi/ghes.h:111
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
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
In drivers/acpi/apei/ghes.c (ffffffff81652677)
Location: include/acpi/ghes.h:111
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818fcb2e)
Location: include/acpi/ghes.h:111
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
```
</details>
</li>
</ul>

## Differences
