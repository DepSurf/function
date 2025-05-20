# Function: <code>kernel_map_sync_memtype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070430)
Location: arch/x86/mm/pat.c:764
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff81070430-ffffffff81070546: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070180)
Location: arch/x86/mm/pat.c:786
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81070180-ffffffff810702c3: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073dc0)
Location: arch/x86/mm/pat.c:800
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81073dc0-ffffffff81073f03: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073360)
Location: arch/x86/mm/pat.c:797
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81073360-ffffffff810734ad: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078d20)
Location: arch/x86/mm/pat.c:819
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81078d20-ffffffff81078e6d: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:835
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8107c02d-ffffffff8107c076: kernel_map_sync_memtype.cold.16 (STB_LOCAL)
ffffffff8107b740-ffffffff8107b821: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81082112)
Location: arch/x86/mm/pat.c:844
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108299d-ffffffff810829e6: kernel_map_sync_memtype.cold.15 (STB_LOCAL)
ffffffff810820b0-ffffffff81082191: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085d93)
Location: arch/x86/mm/pat.c:845
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810865db-ffffffff81086625: kernel_map_sync_memtype.cold (STB_LOCAL)
ffffffff81085d30-ffffffff81085e13: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086a83)
Location: arch/x86/mm/pat.c:845
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810872cb-ffffffff81087315: kernel_map_sync_memtype.cold (STB_LOCAL)
ffffffff81086a20-ffffffff81086b03: kernel_map_sync_memtype (STB_GLOBAL)
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
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085a83)
Location: arch/x86/mm/pat.c:845
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810862cb-ffffffff81086315: kernel_map_sync_memtype.cold (STB_LOCAL)
ffffffff81085a20-ffffffff81085b03: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074803)
Location: arch/x86/mm/pat.c:845
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8107504b-ffffffff81075095: kernel_map_sync_memtype.cold (STB_LOCAL)
ffffffff810747a0-ffffffff81074883: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085a33)
Location: arch/x86/mm/pat.c:845
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108627b-ffffffff810862c5: kernel_map_sync_memtype.cold (STB_LOCAL)
ffffffff810859d0-ffffffff81085ab3: kernel_map_sync_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_map_sync_memtype(u64 base, long unsigned int size, enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81087b83)
Location: arch/x86/mm/pat.c:845
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810883c8-ffffffff81088412: kernel_map_sync_memtype.cold (STB_LOCAL)
ffffffff81087b20-ffffffff81087c03: kernel_map_sync_memtype (STB_GLOBAL)
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
