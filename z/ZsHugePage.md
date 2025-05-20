# Function: <code>ZsHugePage</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e24fd)
Location: mm/zsmalloc.c:292
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814682c1)
Location: mm/zsmalloc.c:316
Inline: True
Inline callers:
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:find_tagged_obj
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
  - mm/zsmalloc.c:__free_zspage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149e1d8)
Location: mm/zsmalloc.c:273
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cd300)
Location: mm/zsmalloc.c:273
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:migrate_zspage
  - mm/zsmalloc.c:migrate_zspage
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
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
