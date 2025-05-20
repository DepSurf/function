# Function: <code>__efi_soft_reserve_enabled</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819baf10)
Location: drivers/firmware/efi/efi.c:79
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff819baf10-ffffffff819baf2c: __efi_soft_reserve_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bd170)
Location: drivers/firmware/efi/efi.c:83
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff819bd170-ffffffff819bd18c: __efi_soft_reserve_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819a1900)
Location: drivers/firmware/efi/efi.c:83
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff819a1900-ffffffff819a191c: __efi_soft_reserve_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81a4e8b0)
Location: drivers/firmware/efi/efi.c:83
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff81a4e8b0-ffffffff81a4e8cc: __efi_soft_reserve_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81bbd4a0)
Location: drivers/firmware/efi/efi.c:86
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff81bbd4a0-ffffffff81bbd4c0: __efi_soft_reserve_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81d63120)
Location: drivers/firmware/efi/efi.c:90
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff81d63120-ffffffff81d63140: __efi_soft_reserve_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81dce1f0)
Location: drivers/firmware/efi/efi.c:93
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff81dce1f0-ffffffff81dce210: __efi_soft_reserve_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81e86ef0)
Location: drivers/firmware/efi/efi.c:94
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff81e86ef0-ffffffff81e86f10: __efi_soft_reserve_enabled (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
