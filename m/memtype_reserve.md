# Function: <code>memtype_reserve</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:577
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff810908a6-ffffffff81090a06: memtype_reserve.cold (STB_LOCAL)
ffffffff8108fe40-ffffffff810900ea: memtype_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:577
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81bd99a3-ffffffff81bd9b03: memtype_reserve.cold (STB_LOCAL)
ffffffff8108fb40-ffffffff8108fdea: memtype_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:577
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81bcb9c0-ffffffff81bcbb1d: memtype_reserve.cold (STB_LOCAL)
ffffffff81090640-ffffffff810908e7: memtype_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:577
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81ca153b-ffffffff81ca1694: memtype_reserve.cold (STB_LOCAL)
ffffffff810a0070-ffffffff810a0334: memtype_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:585
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81e50b48-ffffffff81e50cad: memtype_reserve.cold (STB_LOCAL)
ffffffff810b3fa0-ffffffff810b428a: memtype_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:538
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff82054f1b-ffffffff82054f30: memtype_reserve.cold (STB_LOCAL)
ffffffff810cea20-ffffffff810cee22: memtype_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:538
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff820d34ea-ffffffff820d34ff: memtype_reserve.cold (STB_LOCAL)
ffffffff810d1fe0-ffffffff810d23da: memtype_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode *new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:538
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff821ae358-ffffffff821ae36d: memtype_reserve.cold (STB_LOCAL)
ffffffff810da740-ffffffff810dab69: memtype_reserve (STB_GLOBAL)
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
