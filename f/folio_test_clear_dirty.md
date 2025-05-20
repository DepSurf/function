# Function: <code>folio_test_clear_dirty</code>

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
In mm/page-writeback.c (ffffffff812fd991)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/huge_memory.c (ffffffff813ba567)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/page-writeback.c (ffffffff813681b5)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/huge_memory.c (ffffffff8143cb91)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/page-writeback.c (ffffffff8139a035)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/huge_memory.c (ffffffff814721e7)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/page-writeback.c (ffffffff813c3cf5)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/huge_memory.c (ffffffff814a2377)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
