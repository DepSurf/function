# Function: <code>memtype_kernel_map_sync</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810901b0)
Location: arch/x86/mm/pat/memtype.c:873
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff8108f8e0-ffffffff8108f96a: memtype_kernel_map_sync.part.0 (STB_LOCAL)
ffffffff810907e7-ffffffff81090832: memtype_kernel_map_sync.part.0.cold (STB_LOCAL)
ffffffff810901b0-ffffffff8109022c: memtype_kernel_map_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8108feb0)
Location: arch/x86/mm/pat/memtype.c:873
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff8108f5d0-ffffffff8108f65a: memtype_kernel_map_sync.part.0 (STB_LOCAL)
ffffffff81bd98e4-ffffffff81bd992f: memtype_kernel_map_sync.part.0.cold (STB_LOCAL)
ffffffff8108feb0-ffffffff8108ff2c: memtype_kernel_map_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090a13)
Location: arch/x86/mm/pat/memtype.c:875
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81bcbb1d-ffffffff81bcbb67: memtype_kernel_map_sync.cold (STB_LOCAL)
ffffffff810909b0-ffffffff81090a93: memtype_kernel_map_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810a0563)
Location: arch/x86/mm/pat/memtype.c:880
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81ca16f6-ffffffff81ca1740: memtype_kernel_map_sync.cold (STB_LOCAL)
ffffffff810a0500-ffffffff810a05e3: memtype_kernel_map_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:888
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81e50d1e-ffffffff81e50d67: memtype_kernel_map_sync.cold (STB_LOCAL)
ffffffff810b4470-ffffffff810b4564: memtype_kernel_map_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810cf0d0)
Location: arch/x86/mm/pat/memtype.c:841
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff810cf0d0-ffffffff810cf206: memtype_kernel_map_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810d2680)
Location: arch/x86/mm/pat/memtype.c:841
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff810d2680-ffffffff810d27b6: memtype_kernel_map_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810dae10)
Location: arch/x86/mm/pat/memtype.c:841
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff810dae10-ffffffff810daf46: memtype_kernel_map_sync (STB_GLOBAL)
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
