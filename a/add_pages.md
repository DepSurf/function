# Function: <code>add_pages</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810711a0)
Location: arch/x86/mm/init_64.c:775
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/hmm.c:hmm_devmem_pages_create
```
**Symbols:**

```
ffffffff810711a0-ffffffff81071204: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81073f20)
Location: arch/x86/mm/init_64.c:786
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/hmm.c:hmm_devmem_pages_create
```
**Symbols:**

```
ffffffff81073f20-ffffffff81073f85: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079e10)
Location: arch/x86/mm/init_64.c:779
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - kernel/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff81079e10-ffffffff81079e75: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107db40)
Location: arch/x86/mm/init_64.c:846
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff8107db40-ffffffff8107dba1: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107ebd0)
Location: arch/x86/mm/init_64.c:846
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8107ebd0-ffffffff8107ec31: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085570)
Location: arch/x86/mm/init_64.c:854
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81085570-ffffffff810855d7: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086620)
Location: arch/x86/mm/init_64.c:848
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81086620-ffffffff81086687: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810873a0)
Location: arch/x86/mm/init_64.c:948
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810873a0-ffffffff81087401: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810966d0)
Location: arch/x86/mm/init_64.c:949
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810966d0-ffffffff81096731: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a8fe0)
Location: arch/x86/mm/init_64.c:949
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810a8fe0-ffffffff810a904d: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c26d0)
Location: arch/x86/mm/init_64.c:950
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810c26d0-ffffffff810c273d: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c5db0)
Location: arch/x86/mm/init_64.c:950
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810c5db0-ffffffff810c5e15: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810ce200)
Location: arch/x86/mm/init_64.c:950
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810ce200-ffffffff810ce265: add_pages (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046e4a0)
Location: include/linux/memory_hotplug.h:136
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
</details>
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107dbd0)
Location: arch/x86/mm/init_64.c:846
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8107dbd0-ffffffff8107dc31: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ced0)
Location: arch/x86/mm/init_64.c:846
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8106ced0-ffffffff8106cf31: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107db80)
Location: arch/x86/mm/init_64.c:846
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8107db80-ffffffff8107dbe1: add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107fc70)
Location: arch/x86/mm/init_64.c:846
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8107fc70-ffffffff8107fcd1: add_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, start_pfn, nr_pages, want_memblock</code> ➡️ <code>nid, start_pfn, nr_pages, altmap, want_memblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mhp_restrictions *restrictions</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vmem_altmap *altmap</code>
</li>
<li>
<b>Param removed. </b>
<code>bool want_memblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mhp_params *params</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mhp_restrictions *restrictions</code>
</li>
</ul>
</details>
</li>
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
