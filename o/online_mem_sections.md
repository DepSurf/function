# Function: <code>online_mem_sections</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8121f360)
Location: mm/sparse.c:628
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff8121f360-ffffffff8121f3c4: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8123a590)
Location: mm/sparse.c:640
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff8123a590-ffffffff8123a5fb: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8125db50)
Location: mm/sparse.c:606
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff8125db50-ffffffff8125dbbb: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812723e0)
Location: mm/sparse.c:541
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff812723e0-ffffffff8127244b: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/sparse.c (0)
Location: mm/sparse.c:597
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff8128dd8c-ffffffff8128dda7: online_mem_sections.cold (STB_LOCAL)
ffffffff8128dbe0-ffffffff8128dc5c: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8129d900)
Location: mm/sparse.c:609
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff8129d900-ffffffff8129d96a: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d15a0)
Location: mm/sparse.c:606
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff812d15a0-ffffffff812d160a: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812dd0c0)
Location: mm/sparse.c:609
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff812dd0c0-ffffffff812dd12a: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812e4910)
Location: mm/sparse.c:619
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
```
**Symbols:**

```
ffffffff812e4910-ffffffff812e4979: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8132bb90)
Location: mm/sparse.c:592
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
```
**Symbols:**

```
ffffffff8132bb90-ffffffff8132bbf9: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8139b830)
Location: mm/sparse.c:593
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
```
**Symbols:**

```
ffffffff8139b830-ffffffff8139b8d3: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8141b8a0)
Location: mm/sparse.c:593
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
```
**Symbols:**

```
ffffffff8141b8a0-ffffffff8141b948: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8144ee40)
Location: mm/sparse.c:593
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
```
**Symbols:**

```
ffffffff8144ee40-ffffffff8144eee8: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81488a00)
Location: mm/sparse.c:592
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
```
**Symbols:**

```
ffffffff81488a00-ffffffff81488aa8: online_mem_sections (STB_GLOBAL)
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
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff80001033ca70)
Location: mm/sparse.c:609
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffff80001033ca70-ffff80001033cafc: online_mem_sections (STB_GLOBAL)
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
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000417b60)
Location: mm/sparse.c:609
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
c000000000417b60-c000000000417bf8: online_mem_sections (STB_GLOBAL)
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
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81295ee0)
Location: mm/sparse.c:609
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff81295ee0-ffffffff81295f4a: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81287af0)
Location: mm/sparse.c:609
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff81287af0-ffffffff81287b5a: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81293cf0)
Location: mm/sparse.c:609
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff81293cf0-ffffffff81293d5a: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void online_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812a3b50)
Location: mm/sparse.c:609
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages_range
```
**Symbols:**

```
ffffffff812a3b50-ffffffff812a3bba: online_mem_sections (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
