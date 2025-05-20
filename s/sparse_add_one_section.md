# Function: <code>sparse_add_one_section</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sparse_add_one_section(struct zone *zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8181ef4d)
Location: mm/sparse.c:693
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff8181ef4d-ffffffff8181f0b9: sparse_add_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sparse_add_one_section(struct zone *zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8189946f)
Location: mm/sparse.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff8189946f-ffffffff818995c8: sparse_add_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sparse_add_one_section(struct zone *zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff818cdb27)
Location: mm/sparse.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff818cdb27-ffffffff818cdc80: sparse_add_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sparse_add_one_section(struct pglist_data *pgdat, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81904fc2)
Location: mm/sparse.c:764
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff81904fc2-ffffffff81905127: sparse_add_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sparse_add_one_section(struct pglist_data *pgdat, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8198ef96)
Location: mm/sparse.c:776
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff8198ef96-ffffffff8198f119: sparse_add_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sparse_add_one_section(struct pglist_data *pgdat, long unsigned int start_pfn, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff819eb83f)
Location: mm/sparse.c:746
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff819eb83f-ffffffff819eb995: sparse_add_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sparse_add_one_section(int nid, long unsigned int start_pfn, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a26b00)
Location: mm/sparse.c:681
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff81a26b00-ffffffff81a26c18: sparse_add_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pglist_data *pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pglist_data *pgdat</code>
</li>
</ul>
</details>
</li>
</ul>
