# Function: <code>__kmalloc_large_node</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__kmalloc_large_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:1103
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
```
**Symbols:**

```
ffffffff813a12a0-ffffffff813a13f4: __kmalloc_large_node (STB_LOCAL)
ffffffff820631b4-ffffffff820631d4: __kmalloc_large_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__kmalloc_large_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:1116
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
```
**Symbols:**

```
ffffffff813d4520-ffffffff813d4670: __kmalloc_large_node (STB_LOCAL)
ffffffff820e2a51-ffffffff820e2a71: __kmalloc_large_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__kmalloc_large_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3916
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmalloc_large
```
**Symbols:**

```
ffffffff81454ec0-ffffffff81454fe6: __kmalloc_large_node (STB_LOCAL)
ffffffff821c1cdb-ffffffff821c1cfb: __kmalloc_large_node.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
