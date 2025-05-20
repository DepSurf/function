# Function: <code>__section_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff811e3790)
Location: mm/sparse.c:108
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/memory_hotplug.c:__remove_pages
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block_hinted
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff811e3790-ffffffff811e37f0: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812021c0)
Location: mm/sparse.c:104
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/memory_hotplug.c:__remove_pages
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:is_zone_device_section
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block_hinted
```
**Symbols:**

```
ffffffff812021c0-ffffffff81202218: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81214000)
Location: mm/sparse.c:104
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/memory_hotplug.c:__remove_pages
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:is_zone_device_section
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block_hinted
```
**Symbols:**

```
ffffffff81214000-ffffffff81214058: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8121f48d)
Location: mm/sparse.c:104
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:section_mark_present
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block_hinted
```
**Symbols:**

```
ffffffff8121f2d0-ffffffff8121f328: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8123a4f0)
Location: mm/sparse.c:100
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:memory_present
  - mm/memory_hotplug.c:__remove_pages
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block_hinted
```
**Symbols:**

```
ffffffff8123a4f0-ffffffff8123a55b: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8125dab0)
Location: mm/sparse.c:100
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:memory_present
  - mm/memory_hotplug.c:__remove_pages
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block_hinted
```
**Symbols:**

```
ffffffff8125dab0-ffffffff8125db1b: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81272340)
Location: mm/sparse.c:101
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:memory_present
  - mm/memory_hotplug.c:__remove_pages
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block_hinted
```
**Symbols:**

```
ffffffff81272340-ffffffff812723ab: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8128d970)
Location: mm/sparse.c:112
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffffffff8128d970-ffffffff8128d9d4: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8129d860)
Location: mm/sparse.c:114
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffffffff8129d860-ffffffff8129d8c4: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d14e0)
Location: mm/sparse.c:113
Inline: False
Direct callers:
  - mm/sparse.c:section_mark_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffffffff812d14e0-ffffffff812d1566: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812dd000)
Location: mm/sparse.c:112
Inline: False
Direct callers:
  - mm/sparse.c:section_mark_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffffffff812dd000-ffffffff812dd086: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812e4850)
Location: mm/sparse.c:112
Inline: False
Direct callers:
  - mm/sparse.c:section_mark_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffffffff812e4850-ffffffff812e48d5: __section_nr (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff80001033c9a0)
Location: mm/sparse.c:114
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffff80001033c9a0-ffff80001033ca1c: __section_nr (STB_GLOBAL)
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
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000417a80)
Location: mm/sparse.c:114
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
c000000000417a80-c000000000417b00: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffe0002323b2)
Location: mm/sparse.c:114
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffe0002323b2-ffffffe00023241a: __section_nr (STB_GLOBAL)
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
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81295e40)
Location: mm/sparse.c:114
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffffffff81295e40-ffffffff81295ea4: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81287a50)
Location: mm/sparse.c:114
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffffffff81287a50-ffffffff81287ab4: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81293c50)
Location: mm/sparse.c:114
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffffffff81293c50-ffffffff81293cb4: __section_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section *ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812a3ab0)
Location: mm/sparse.c:114
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
  - drivers/base/memory.c:find_memory_block
```
**Symbols:**

```
ffffffff812a3ab0-ffffffff812a3b14: __section_nr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
