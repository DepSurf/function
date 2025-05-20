# Function: <code>__folio_clear_active</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81305683)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130d35b)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff813a8070)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136f80b)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8137c894)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/slub.c (ffffffff814256d4)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a192b)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813acbd7)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/slub.c (ffffffff8145a96e)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (ffffffff813cb5b2)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813d6083)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/slub.c (ffffffff81459707)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
