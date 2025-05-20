# Function: <code>sparse_remove_section</code>

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
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8128dce0)
Location: mm/sparse.c:912
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8128dce0-ffffffff8128dd58: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8129d9e0)
Location: mm/sparse.c:938
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8129d9e0-ffffffff8129da57: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d1680)
Location: mm/sparse.c:958
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff812d1680-ffffffff812d16f1: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812dd1a0)
Location: mm/sparse.c:965
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff812dd1a0-ffffffff812dd211: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812e49f0)
Location: mm/sparse.c:973
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff812e49f0-ffffffff812e4a67: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8132bc70)
Location: mm/sparse.c:946
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8132bc70-ffffffff8132bce7: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8139b990)
Location: mm/sparse.c:925
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8139b990-ffffffff8139b9e3: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8141ba20)
Location: mm/sparse.c:925
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8141ba20-ffffffff8141ba46: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sparse_remove_section(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8144efc0)
Location: mm/sparse.c:925
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8144efc0-ffffffff8144f041: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sparse_remove_section(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81488b80)
Location: mm/sparse.c:926
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81488b80-ffffffff81488c01: sparse_remove_section (STB_GLOBAL)
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
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff80001033cb00)
Location: mm/sparse.c:938
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffff80001033cb00-ffff80001033cbe8: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000417cb0)
Location: mm/sparse.c:938
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
c000000000417cb0-c000000000417d5c: sparse_remove_section (STB_GLOBAL)
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
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81295fc0)
Location: mm/sparse.c:938
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81295fc0-ffffffff81296037: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81287bd0)
Location: mm/sparse.c:938
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81287bd0-ffffffff81287c47: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81293dd0)
Location: mm/sparse.c:938
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81293dd0-ffffffff81293e47: sparse_remove_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sparse_remove_section(struct mem_section *ms, long unsigned int pfn, long unsigned int nr_pages, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812a3c30)
Location: mm/sparse.c:938
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff812a3c30-ffffffff812a3ca7: sparse_remove_section (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_section *ms</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int map_offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>ms, pfn, nr_pages, map_offset, altmap</code> ➡️ <code>pfn, nr_pages, altmap</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
