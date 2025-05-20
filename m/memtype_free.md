# Function: <code>memtype_free</code>

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
int memtype_free(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090770)
Location: arch/x86/mm/pat/memtype.c:658
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff8108fa70-ffffffff8108fb5f: memtype_free.part.0 (STB_LOCAL)
ffffffff81090832-ffffffff8109087f: memtype_free.part.0.cold (STB_LOCAL)
ffffffff810900f0-ffffffff8109010c: memtype_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memtype_free(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090470)
Location: arch/x86/mm/pat/memtype.c:658
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff8108f770-ffffffff8108f85f: memtype_free.part.0 (STB_LOCAL)
ffffffff81bd992f-ffffffff81bd997c: memtype_free.part.0.cold (STB_LOCAL)
ffffffff8108fdf0-ffffffff8108fe0c: memtype_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memtype_free(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090fe0)
Location: arch/x86/mm/pat/memtype.c:658
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81090270-ffffffff8109035f: memtype_free.part.0 (STB_LOCAL)
ffffffff81bcb94c-ffffffff81bcb999: memtype_free.part.0.cold (STB_LOCAL)
ffffffff810908f0-ffffffff8109090c: memtype_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memtype_free(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810a036c)
Location: arch/x86/mm/pat/memtype.c:663
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81ca1694-ffffffff81ca16f6: memtype_free.cold (STB_LOCAL)
ffffffff810a0340-ffffffff810a044e: memtype_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int memtype_free(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:671
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81e50cad-ffffffff81e50d1e: memtype_free.cold (STB_LOCAL)
ffffffff810b4290-ffffffff810b4390: memtype_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int memtype_free(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:624
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff82054f30-ffffffff82054f45: memtype_free.cold (STB_LOCAL)
ffffffff810cee40-ffffffff810cef99: memtype_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int memtype_free(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:624
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff820d34ff-ffffffff820d3514: memtype_free.cold (STB_LOCAL)
ffffffff810d23f0-ffffffff810d2543: memtype_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int memtype_free(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:624
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff821ae36d-ffffffff821ae382: memtype_free.cold (STB_LOCAL)
ffffffff810dab80-ffffffff810dacd3: memtype_free (STB_GLOBAL)
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
