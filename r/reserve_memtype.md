# Function: <code>reserve_memtype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106fea0)
Location: arch/x86/mm/pat.c:487
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff8106fea0-ffffffff81070288: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106fc10)
Location: arch/x86/mm/pat.c:531
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8106fc10-ffffffff8106ffde: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073840)
Location: arch/x86/mm/pat.c:531
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81073840-ffffffff81073c06: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81072df0)
Location: arch/x86/mm/pat.c:528
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81072df0-ffffffff810731b9: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078770)
Location: arch/x86/mm/pat.c:528
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81078770-ffffffff81078b3f: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:539
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8107bec1-ffffffff8107c02d: reserve_memtype.cold.15 (STB_LOCAL)
ffffffff8107b400-ffffffff8107b686: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:544
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81082831-ffffffff8108299d: reserve_memtype.cold.14 (STB_LOCAL)
ffffffff81081d40-ffffffff81082000: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:545
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108648b-ffffffff810865db: reserve_memtype.cold (STB_LOCAL)
ffffffff810859d0-ffffffff81085c7d: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:545
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108717b-ffffffff810872cb: reserve_memtype.cold (STB_LOCAL)
ffffffff810866c0-ffffffff8108696d: reserve_memtype (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:545
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108617b-ffffffff810862cb: reserve_memtype.cold (STB_LOCAL)
ffffffff810856c0-ffffffff8108596d: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:545
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81074efb-ffffffff8107504b: reserve_memtype.cold (STB_LOCAL)
ffffffff81074440-ffffffff810746ed: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:545
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108612b-ffffffff8108627b: reserve_memtype.cold (STB_LOCAL)
ffffffff81085670-ffffffff8108591d: reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:545
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108827b-ffffffff810883c8: reserve_memtype.cold (STB_LOCAL)
ffffffff810877c0-ffffffff81087a6e: reserve_memtype (STB_GLOBAL)
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
