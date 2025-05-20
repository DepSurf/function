# Function: <code>__efi_memmap_alloc_late</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff820224f4)
Location: drivers/firmware/efi/memmap.c:20
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In drivers/firmware/efi/memmap.c (ffffffff82105228)
Location: drivers/firmware/efi/memmap.c:20
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In drivers/firmware/efi/memmap.c (ffffffff8270e8f1)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In drivers/firmware/efi/memmap.c (ffffffff82738bb0)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In drivers/firmware/efi/memmap.c (ffffffff828f2b5c)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8290e336)
Location: drivers/firmware/efi/memmap.c:21
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff8290e336-ffffffff8290e378: __efi_memmap_alloc_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82917d4f)
Location: drivers/firmware/efi/memmap.c:21
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff82917d4f-ffffffff82917d91: __efi_memmap_alloc_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82d2a26e)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In drivers/firmware/efi/memmap.c (ffffffff8301897c)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In drivers/firmware/efi/memmap.c (ffffffff83223969)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In drivers/firmware/efi/memmap.c (ffffffff8330d76f)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In drivers/firmware/efi/memmap.c (ffffffff834c7499)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/platform/efi/memmap.c (ffffffff83ea1551)
Location: arch/x86/platform/efi/memmap.c:22
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/platform/efi/memmap.c (ffffffff836c57a1)
Location: arch/x86/platform/efi/memmap.c:22
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/platform/efi/memmap.c (ffffffff838f63a1)
Location: arch/x86/platform/efi/memmap.c:22
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
```
</details>
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
In drivers/firmware/efi/memmap.c (ffff8000114a6774)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In drivers/firmware/efi/memmap.c (c15a8b10)
Location: drivers/firmware/efi/memmap.c:21
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
<summary>In <code>aws</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828fd155)
Location: drivers/firmware/efi/memmap.c:21
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff828fd155-ffffffff828fd197: __efi_memmap_alloc_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828f49f1)
Location: drivers/firmware/efi/memmap.c:21
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff828f49f1-ffffffff828f4a33: __efi_memmap_alloc_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82912384)
Location: drivers/firmware/efi/memmap.c:21
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff82912384-ffffffff829123c6: __efi_memmap_alloc_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82918db1)
Location: drivers/firmware/efi/memmap.c:21
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff82918db1-ffffffff82918df3: __efi_memmap_alloc_late (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
