# Function: <code>vmap_small_pages_range_noflush</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vmap_small_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b84e0)
Location: mm/vmalloc.c:513
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812b84e0-ffffffff812b872c: vmap_small_pages_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vmap_small_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:541
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812fac40-ffffffff812faeaa: vmap_small_pages_range_noflush (STB_LOCAL)
ffffffff81cbce4f-ffffffff81cbceb8: vmap_small_pages_range_noflush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vmap_small_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:542
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81362130-ffffffff813623a3: vmap_small_pages_range_noflush (STB_LOCAL)
ffffffff81e6eaf3-ffffffff81e6eb63: vmap_small_pages_range_noflush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vmap_small_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:554
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff813ddad0-ffffffff813ddd40: vmap_small_pages_range_noflush (STB_LOCAL)
ffffffff82064a01-ffffffff82064a71: vmap_small_pages_range_noflush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vmap_small_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:543
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81412330-ffffffff814125a0: vmap_small_pages_range_noflush (STB_LOCAL)
ffffffff820e4106-ffffffff820e4176: vmap_small_pages_range_noflush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vmap_small_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:543
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8143eb90-ffffffff8143ee00: vmap_small_pages_range_noflush (STB_LOCAL)
ffffffff821c0d3a-ffffffff821c0daa: vmap_small_pages_range_noflush.cold (STB_LOCAL)
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
