# Function: <code>acpi_hest_get_record_size</code>

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
In drivers/firmware/efi/cper.c (ffffffff817886cf)
Location: include/acpi/ghes.h:106
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
Location: include/acpi/ghes.h:107
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
```
In drivers/firmware/efi/cper.c (ffffffff817feb6c)
Location: include/acpi/ghes.h:107
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
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff8184836c)
Location: include/acpi/ghes.h:106
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
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818745bc)
Location: include/acpi/ghes.h:106
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
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818b8843)
Location: include/acpi/ghes.h:106
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
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb243)
Location: include/acpi/ghes.h:106
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
Location: include/acpi/ghes.h:109
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff819bfae2)
Location: include/acpi/ghes.h:109
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
In drivers/acpi/apei/ghes.c (ffffffff8170e635)
Location: include/acpi/ghes.h:127
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
```
```
In drivers/firmware/efi/cper.c (ffffffff81c2c87a)
Location: include/acpi/ghes.h:127
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
In drivers/acpi/apei/ghes.c (ffffffff816ef932)
Location: include/acpi/ghes.h:127
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
```
```
In drivers/firmware/efi/cper.c (ffffffff81c1eba3)
Location: include/acpi/ghes.h:127
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
In drivers/acpi/apei/ghes.c (ffffffff81769992)
Location: include/acpi/ghes.h:127
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
```
```
In drivers/firmware/efi/cper.c (ffffffff81d30136)
Location: include/acpi/ghes.h:127
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
In drivers/acpi/apei/ghes.c (ffffffff8189e2f1)
Location: include/acpi/ghes.h:127
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
```
```
In drivers/firmware/efi/cper.c (ffffffff81efc461)
Location: include/acpi/ghes.h:127
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
In drivers/acpi/apei/ghes.c (ffffffff819e7b9d)
Location: include/acpi/ghes.h:108
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
```
```
In drivers/firmware/efi/cper.c (ffffffff81d65c0c)
Location: include/acpi/ghes.h:108
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
In drivers/acpi/apei/ghes.c (ffffffff81a302ad)
Location: include/acpi/ghes.h:108
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
```
```
In drivers/firmware/efi/cper.c (ffffffff81dd0d3c)
Location: include/acpi/ghes.h:108
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
In drivers/acpi/apei/ghes.c (ffffffff81a7b7bd)
Location: include/acpi/ghes.h:112
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
```
```
In drivers/firmware/efi/cper.c (ffffffff81e89aec)
Location: include/acpi/ghes.h:112
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
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffff800010b5e4a0)
Location: include/acpi/ghes.h:106
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
In drivers/firmware/efi/cper.c (ffffffff81845943)
Location: include/acpi/ghes.h:106
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
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818e00a3)
Location: include/acpi/ghes.h:106
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
Location: include/acpi/ghes.h:106
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff818fcb43)
Location: include/acpi/ghes.h:106
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_check
  - drivers/firmware/efi/cper.c:cper_estatus_print
```
</details>
</li>
</ul>

## Differences
