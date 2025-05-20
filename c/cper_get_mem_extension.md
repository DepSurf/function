# Function: <code>cper_get_mem_extension</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff819901e8)
Location: include/linux/cper.h:501
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/firmware/efi/cper.c (ffffffff819c050d)
Location: include/linux/cper.h:501
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
In drivers/edac/ghes_edac.c (ffffffff81974775)
Location: include/linux/cper.h:501
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/firmware/efi/cper.c (ffffffff819a4c0d)
Location: include/linux/cper.h:501
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
In drivers/edac/ghes_edac.c (ffffffff81a1d475)
Location: include/linux/cper.h:501
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/firmware/efi/cper.c (ffffffff81a51e0e)
Location: include/linux/cper.h:501
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_location
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81bc1039)
Location: include/linux/cper.h:501
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_location
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81d64969)
Location: include/linux/cper.h:501
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_location
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81dcfa99)
Location: include/linux/cper.h:501
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_location
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81e887c9)
Location: include/linux/cper.h:524
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_location
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
