# Function: <code>acpi_hest_get_payload</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8153cc50)
Location: include/acpi/ghes.h:85
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81788e6f)
Location: include/acpi/ghes.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff8159f772)
Location: include/acpi/ghes.h:86
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
  - drivers/acpi/apei/ghes.c:ghes_do_proc
  - drivers/acpi/apei/ghes.c:ghes_do_proc
  - drivers/acpi/apei/ghes.c:ghes_do_proc
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
```
In drivers/firmware/efi/cper.c (ffffffff817ff309)
Location: include/acpi/ghes.h:86
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff815d73d3)
Location: include/acpi/ghes.h:85
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81848db1)
Location: include/acpi/ghes.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff815f0b56)
Location: include/acpi/ghes.h:85
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81875021)
Location: include/acpi/ghes.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff8162294e)
Location: include/acpi/ghes.h:85
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818b925d)
Location: include/acpi/ghes.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff8164441e)
Location: include/acpi/ghes.h:85
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818ebc4a)
Location: include/acpi/ghes.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff816f0f2e)
Location: include/acpi/ghes.h:88
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/firmware/efi/cper.c (ffffffff819bf6a0)
Location: include/acpi/ghes.h:88
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_print_fw_err
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
In drivers/acpi/apei/ghes.c (ffffffff8170e10e)
Location: include/acpi/ghes.h:106
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/firmware/efi/cper.c (ffffffff81c2c438)
Location: include/acpi/ghes.h:106
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_print_fw_err
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
In drivers/acpi/apei/ghes.c (ffffffff816f0111)
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81c1e6b9)
Location: include/acpi/ghes.h:106
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff8176a201)
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81d2fda8)
Location: include/acpi/ghes.h:106
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff8189eecd)
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81efc0d2)
Location: include/acpi/ghes.h:106
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff819e8248)
Location: include/acpi/ghes.h:87
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81d6567b)
Location: include/acpi/ghes.h:87
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff81a30968)
Location: include/acpi/ghes.h:87
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81dd07ab)
Location: include/acpi/ghes.h:87
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff81a7b0d5)
Location: include/acpi/ghes.h:91
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_aer
```
```
In drivers/firmware/efi/cper.c (ffffffff81e89455)
Location: include/acpi/ghes.h:91
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffff8000107af5cc)
Location: include/acpi/ghes.h:85
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffff800010b5ef78)
Location: include/acpi/ghes.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/firmware/efi/cper.c (ffffffff8184634a)
Location: include/acpi/ghes.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff8163825e)
Location: include/acpi/ghes.h:85
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818e0aaa)
Location: include/acpi/ghes.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/acpi/apei/ghes.c (ffffffff8165259e)
Location: include/acpi/ghes.h:85
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818fd54a)
Location: include/acpi/ghes.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
</ul>

## Differences
