# Function: <code>set_direct_map_invalid_noflush</code>

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
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084a20)
Location: arch/x86/mm/pageattr.c:2261
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81084a20-ffffffff81084a35: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085720)
Location: arch/x86/mm/pageattr.c:2151
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81085720-ffffffff81085735: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f440)
Location: arch/x86/mm/pat/set_memory.c:2187
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8108f440-ffffffff8108f4bb: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f230)
Location: arch/x86/mm/pat/set_memory.c:2187
Inline: False
Direct callers:
  - kernel/power/snapshot.c:safe_copy_page
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8108f230-ffffffff8108f2ab: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fdc0)
Location: arch/x86/mm/pat/set_memory.c:2195
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8108fdc0-ffffffff8108fe3b: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f8a0)
Location: arch/x86/mm/pat/set_memory.c:2195
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff8109f8a0-ffffffff8109f91b: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b36b0)
Location: arch/x86/mm/pat/set_memory.c:2246
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810b36b0-ffffffff810b3737: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce270)
Location: arch/x86/mm/pat/set_memory.c:2350
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810ce270-ffffffff810ce301: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d1830)
Location: arch/x86/mm/pat/set_memory.c:2349
Inline: False
Direct callers:
  - mm/vmalloc.c:vfree
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810d1830-ffffffff810d18c1: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9f60)
Location: arch/x86/mm/pat/set_memory.c:2353
Inline: False
Direct callers:
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810d9f60-ffffffff810d9ff1: set_direct_map_invalid_noflush (STB_GLOBAL)
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
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pageattr.c (ffff8000100b04e0)
Location: arch/arm64/mm/pageattr.c:151
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffff8000100b04e0-ffff8000100b0578: set_direct_map_invalid_noflush (STB_GLOBAL)
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
Location: include/linux/set_memory.h:18
Inline: True
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
Location: include/linux/set_memory.h:18
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
Location: include/linux/set_memory.h:18
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
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084720)
Location: arch/x86/mm/pageattr.c:2151
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81084720-ffffffff81084735: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81073330)
Location: arch/x86/mm/pageattr.c:2151
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81073330-ffffffff81073345: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810846d0)
Location: arch/x86/mm/pageattr.c:2151
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff810846d0-ffffffff810846e5: set_direct_map_invalid_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_direct_map_invalid_noflush(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086810)
Location: arch/x86/mm/pageattr.c:2151
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81086810-ffffffff81086825: set_direct_map_invalid_noflush (STB_GLOBAL)
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
