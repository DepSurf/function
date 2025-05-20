# Function: <code>free_memtype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070290)
Location: arch/x86/mm/pat.c:562
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pat.c:io_free_memtype
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:untrack_pfn
```
**Symbols:**

```
ffffffff81070290-ffffffff810703c8: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106ffe0)
Location: arch/x86/mm/pat.c:606
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_free_memtype
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8106ffe0-ffffffff8107011c: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073c10)
Location: arch/x86/mm/pat.c:606
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81073c10-ffffffff81073d3d: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810731c0)
Location: arch/x86/mm/pat.c:603
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810731c0-ffffffff810732ed: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078b40)
Location: arch/x86/mm/pat.c:603
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81078b40-ffffffff81078c73: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107bdac)
Location: arch/x86/mm/pat.c:616
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8107b020-ffffffff8107b111: free_memtype.part.6 (STB_LOCAL)
ffffffff8107be4b-ffffffff8107be9a: free_memtype.part.6.cold.12 (STB_LOCAL)
ffffffff8107b690-ffffffff8107b6ac: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8108271c)
Location: arch/x86/mm/pat.c:625
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81081960-ffffffff81081a51: free_memtype.part.6 (STB_LOCAL)
ffffffff810827bb-ffffffff8108280a: free_memtype.part.6.cold.11 (STB_LOCAL)
ffffffff81082000-ffffffff8108201c: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086389)
Location: arch/x86/mm/pat.c:626
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810855f0-ffffffff810856e4: free_memtype.part.0 (STB_LOCAL)
ffffffff81086417-ffffffff81086464: free_memtype.part.0.cold (STB_LOCAL)
ffffffff81085c80-ffffffff81085c9c: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81087079)
Location: arch/x86/mm/pat.c:626
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810862e0-ffffffff810863d4: free_memtype.part.0 (STB_LOCAL)
ffffffff81087107-ffffffff81087154: free_memtype.part.0.cold (STB_LOCAL)
ffffffff81086970-ffffffff8108698c: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086079)
Location: arch/x86/mm/pat.c:626
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810852e0-ffffffff810853d4: free_memtype.part.0 (STB_LOCAL)
ffffffff81086107-ffffffff81086154: free_memtype.part.0.cold (STB_LOCAL)
ffffffff81085970-ffffffff8108598c: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074df9)
Location: arch/x86/mm/pat.c:626
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81073fb0-ffffffff810740a4: free_memtype.part.0 (STB_LOCAL)
ffffffff81074e87-ffffffff81074ed4: free_memtype.part.0.cold (STB_LOCAL)
ffffffff810746f0-ffffffff8107470c: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086029)
Location: arch/x86/mm/pat.c:626
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81085290-ffffffff81085384: free_memtype.part.0 (STB_LOCAL)
ffffffff810860b7-ffffffff81086104: free_memtype.part.0.cold (STB_LOCAL)
ffffffff81085920-ffffffff8108593c: free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int free_memtype(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81088179)
Location: arch/x86/mm/pat.c:626
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810874d0-ffffffff810875c6: free_memtype.part.0 (STB_LOCAL)
ffffffff81088207-ffffffff81088254: free_memtype.part.0.cold (STB_LOCAL)
ffffffff81087a70-ffffffff81087a8c: free_memtype (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
