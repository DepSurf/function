# Function: <code>__fill_map</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __fill_map(long unsigned int *obj_map, struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:537
Inline: False
Direct callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff81333710-ffffffff81333822: __fill_map (STB_LOCAL)
ffffffff81cc0fb0-ffffffff81cc1001: __fill_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __fill_map(long unsigned int *obj_map, struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:566
Inline: False
Direct callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:free_partial
```
**Symbols:**

```
ffffffff813a4db0-ffffffff813a4ed3: __fill_map (STB_LOCAL)
ffffffff81e73424-ffffffff81e73475: __fill_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __fill_map(long unsigned int *obj_map, struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:605
Inline: False
Direct callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:free_partial
```
**Symbols:**

```
ffffffff814257d0-ffffffff814258f3: __fill_map (STB_LOCAL)
ffffffff82067380-ffffffff820673d1: __fill_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __fill_map(long unsigned int *obj_map, struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:626
Inline: False
Direct callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:free_partial
```
**Symbols:**

```
ffffffff8145aa60-ffffffff8145ab83: __fill_map (STB_LOCAL)
ffffffff820e6c45-ffffffff820e6c96: __fill_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __fill_map(long unsigned int *obj_map, struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:739
Inline: False
Direct callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:free_partial
```
**Symbols:**

```
ffffffff81455dc0-ffffffff81455ee3: __fill_map (STB_LOCAL)
ffffffff821c1da7-ffffffff821c1df8: __fill_map.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct slab *slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
