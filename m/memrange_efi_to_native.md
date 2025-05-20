# Function: <code>memrange_efi_to_native</code>

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
In arch/x86/platform/efi/efi.c (ffffffff81f79e73)
Location: include/linux/efi.h:1085
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_set_executable
  - arch/x86/platform/efi/efi.c:efi_memory_uc
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
In arch/x86/platform/efi/efi.c (ffffffff81fa2855)
Location: include/linux/efi.h:1149
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff81fde25f)
Location: include/linux/efi.h:1222
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff820bf050)
Location: include/linux/efi.h:1241
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff826c717c)
Location: include/linux/efi.h:1282
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff826f1280)
Location: include/linux/efi.h:1323
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828a8024)
Location: include/linux/efi.h:1334
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c0b3f)
Location: include/linux/efi.h:1349
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c6fca)
Location: include/linux/efi.h:1343
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memrange_efi_to_native(u64 *addr, u64 *npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff810977d8)
Location: include/linux/efi.h:957
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810977d8-ffffffff81097800: memrange_efi_to_native (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/arm-init.c (ffff8000114a7344)
Location: include/linux/efi.h:1343
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:reserve_regions
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/arm-init.c (c15a9b54)
Location: include/linux/efi.h:1343
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:reserve_regions
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828b1f62)
Location: include/linux/efi.h:1343
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
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
In arch/x86/platform/efi/efi.c (ffffffff828aa0d4)
Location: include/linux/efi.h:1343
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c4e61)
Location: include/linux/efi.h:1343
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c8007)
Location: include/linux/efi.h:1343
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
