# Function: <code>stack_depot_fetch</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int stack_depot_fetch(depot_stack_handle_t handle, long unsigned int **entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/stackdepot.c (ffffffff8176fa50)
Location: lib/stackdepot.c:314
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_print
  - lib/stackdepot.c:stack_depot_snprint
Direct callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:__kmem_obj_info
```
**Symbols:**

```
ffffffff8176f3b0-ffffffff8176f462: stack_depot_fetch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int stack_depot_fetch(depot_stack_handle_t handle, long unsigned int **entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/stackdepot.c (ffffffff8189f5a0)
Location: lib/stackdepot.c:364
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_print
  - lib/stackdepot.c:stack_depot_snprint
Direct callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:__kmem_obj_info
```
**Symbols:**

```
ffffffff8189edf0-ffffffff8189ee9b: stack_depot_fetch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int stack_depot_fetch(depot_stack_handle_t handle, long unsigned int **entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/stackdepot.c (ffffffff818e1c30)
Location: lib/stackdepot.c:460
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_snprint
  - lib/stackdepot.c:stack_depot_print
Direct callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:__kmem_obj_info
```
**Symbols:**

```
ffffffff818e12c0-ffffffff818e136b: stack_depot_fetch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int stack_depot_fetch(depot_stack_handle_t handle, long unsigned int **entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (ffffffff81928700)
Location: lib/stackdepot.c:731
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_snprint
  - lib/stackdepot.c:stack_depot_print
Direct callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:__kmem_obj_info
```
**Symbols:**

```
ffffffff821eb4b3-ffffffff821eb4c8: stack_depot_fetch.cold (STB_LOCAL)
ffffffff819280e0-ffffffff8192815c: stack_depot_fetch (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
