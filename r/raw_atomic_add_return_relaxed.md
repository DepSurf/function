# Function: <code>raw_atomic_add_return_relaxed</code>

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
In kernel/events/hw_breakpoint.c (ffffffff8137ef07)
Location: include/linux/atomic/atomic-arch-fallback.h:632
Inline: True
```
```
In mm/rmap.c (ffffffff8140c79a)
Location: include/linux/atomic/atomic-arch-fallback.h:632
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In net/core/page_pool.c (ffffffff81e82590)
Location: include/linux/atomic/atomic-arch-fallback.h:632
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
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
In kernel/events/hw_breakpoint.c (ffffffff813a8167)
Location: include/linux/atomic/atomic-arch-fallback.h:641
Inline: True
```
```
In mm/rmap.c (ffffffff814390aa)
Location: include/linux/atomic/atomic-arch-fallback.h:641
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_file_rmap_pmd
  - mm/rmap.c:folio_add_file_rmap_ptes
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_ptes
```
```
In net/core/page_pool.c (ffffffff81f4369e)
Location: include/linux/atomic/atomic-arch-fallback.h:641
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_page
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
