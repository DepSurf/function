# Function: <code>memmap_init_range</code>

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
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c30864)
Location: mm/page_alloc.c:6317
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81c30864-ffffffff81c309e8: memmap_init_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4f08d)
Location: mm/page_alloc.c:6501
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81d4f08d-ffffffff81d4f230: memmap_init_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1ef8b)
Location: mm/page_alloc.c:6563
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81f1ef8b-ffffffff81f1f1b6: memmap_init_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c8030)
Location: mm/page_alloc.c:6730
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff820c8030-ffffffff820c831c: memmap_init_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8214bf10)
Location: mm/mm_init.c:838
Inline: False
Direct callers:
  - mm/mm_init.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff8214bf10-ffffffff8214c1c4: memmap_init_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8222eaa0)
Location: mm/mm_init.c:849
Inline: False
Direct callers:
  - mm/mm_init.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff8222eaa0-ffffffff8222ed47: memmap_init_range (STB_GLOBAL)
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
