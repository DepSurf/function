# Function: <code>set_direct_map_default_noflush</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084a40)
Location: arch/x86/mm/pageattr.c:2266
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81084a40-ffffffff81084a55: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085740)
Location: arch/x86/mm/pageattr.c:2156
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81085740-ffffffff81085755: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f4c0)
Location: arch/x86/mm/pat/set_memory.c:2192
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8108f4c0-ffffffff8108f53b: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f2b0)
Location: arch/x86/mm/pat/set_memory.c:2192
Inline: False
Direct callers:
  - kernel/power/snapshot.c:safe_copy_page
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8108f2b0-ffffffff8108f32b: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fe40)
Location: arch/x86/mm/pat/set_memory.c:2200
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8108fe40-ffffffff8108febb: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f920)
Location: arch/x86/mm/pat/set_memory.c:2200
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/secretmem.c:secretmem_freepage
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff8109f920-ffffffff8109f99b: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3740)
Location: arch/x86/mm/pat/set_memory.c:2251
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/secretmem.c:secretmem_free_folio
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810b3740-ffffffff810b37c7: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce320)
Location: arch/x86/mm/pat/set_memory.c:2355
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/secretmem.c:secretmem_free_folio
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810ce320-ffffffff810ce3b1: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d18e0)
Location: arch/x86/mm/pat/set_memory.c:2354
Inline: False
Direct callers:
  - mm/vmalloc.c:vfree
  - mm/secretmem.c:secretmem_free_folio
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810d18e0-ffffffff810d1971: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810da010)
Location: arch/x86/mm/pat/set_memory.c:2358
Inline: False
Direct callers:
  - mm/secretmem.c:secretmem_free_folio
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810da010-ffffffff810da0a1: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pageattr.c (ffff8000100b0578)
Location: arch/arm64/mm/pageattr.c:166
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffff8000100b0578-ffff8000100b0618: set_direct_map_default_noflush (STB_GLOBAL)
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
In mm/vmalloc.c (0)
Location: include/linux/set_memory.h:22
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (0)
Location: include/linux/set_memory.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (0)
Location: include/linux/set_memory.h:22
Inline: False
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084740)
Location: arch/x86/mm/pageattr.c:2156
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81084740-ffffffff81084755: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81073350)
Location: arch/x86/mm/pageattr.c:2156
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81073350-ffffffff81073365: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810846f0)
Location: arch/x86/mm/pageattr.c:2156
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff810846f0-ffffffff81084705: set_direct_map_default_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_direct_map_default_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086830)
Location: arch/x86/mm/pageattr.c:2156
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81086830-ffffffff81086845: set_direct_map_default_noflush (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
