# Function: <code>efi_soft_reserve_enabled</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82ce9f16)
Location: include/linux/efi.h:819
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82fd7976)
Location: include/linux/efi.h:824
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff831e2021)
Location: include/linux/efi.h:819
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff832c594c)
Location: include/linux/efi.h:819
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
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
In arch/x86/platform/efi/efi.c (ffffffff834788c3)
Location: include/linux/efi.h:886
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
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
In arch/x86/platform/efi/efi.c (ffffffff83ea2bf2)
Location: include/linux/efi.h:888
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
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
In arch/x86/platform/efi/efi.c (ffffffff836c6e4c)
Location: include/linux/efi.h:908
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
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
In arch/x86/platform/efi/efi.c (ffffffff838f7a4c)
Location: include/linux/efi.h:902
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
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
