# Function: <code>gfp_has_io_fs</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b6273)
Location: include/linux/gfp.h:341
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/page_alloc.c (ffffffff81420977)
Location: include/linux/gfp.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_may_oom
```
```
In mm/swapfile.c (ffffffff814315d4)
Location: include/linux/gfp.h:341
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813df130)
Location: include/linux/gfp.h:351
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/page_alloc.c (ffffffff8144d737)
Location: include/linux/gfp.h:351
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_may_oom
```
```
In mm/swapfile.c (ffffffff8146a9c0)
Location: include/linux/gfp.h:351
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
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
