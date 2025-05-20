# Function: <code>sparse_remove_one_section</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sparse_remove_one_section(struct zone *zone, struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff811e3820)
Location: mm/sparse.c:791
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff811e3820-ffffffff811e394f: sparse_remove_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sparse_remove_one_section(struct zone *zone, struct mem_section *ms, long unsigned int map_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81202250)
Location: mm/sparse.c:790
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81202250-ffffffff812023ca: sparse_remove_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sparse_remove_one_section(struct zone *zone, struct mem_section *ms, long unsigned int map_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81214090)
Location: mm/sparse.c:790
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81214090-ffffffff81214201: sparse_remove_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sparse_remove_one_section(struct zone *zone, struct mem_section *ms, long unsigned int map_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8121f440)
Location: mm/sparse.c:861
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8121f440-ffffffff8121f5f7: sparse_remove_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sparse_remove_one_section(struct zone *zone, struct mem_section *ms, long unsigned int map_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8123a6b0)
Location: mm/sparse.c:873
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8123a6b0-ffffffff8123a824: sparse_remove_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sparse_remove_one_section(struct zone *zone, struct mem_section *ms, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8125dc30)
Location: mm/sparse.c:851
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8125dc30-ffffffff8125ddc4: sparse_remove_one_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sparse_remove_one_section(struct zone *zone, struct mem_section *ms, long unsigned int map_offset, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812724c0)
Location: mm/sparse.c:789
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff812724c0-ffffffff8127265a: sparse_remove_one_section (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int map_offset</code>
</li>
</ul>
</details>
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
