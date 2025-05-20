# Function: <code>folio_test_idle</code>

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
In mm/filemap.c (ffffffff812f3d63)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/swap.c (ffffffff81305a98)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/migrate.c (ffffffff813b0926)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff813b9bfa)
Location: include/linux/page-flags.h:614
Inline: True
```
```
In mm/page_idle.c (ffffffff813e6942)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In fs/proc/page.c (ffffffff814b1253)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/filemap.c (ffffffff8135e053)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/swap.c (ffffffff8137098d)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/migrate.c (ffffffff8143149a)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff8143c6a2)
Location: include/linux/page-flags.h:593
Inline: True
```
```
In mm/page_idle.c (ffffffff8146e452)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In fs/proc/page.c (ffffffff81547c13)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/filemap.c (ffffffff81390ea4)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/swap.c (ffffffff813a2bb3)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/migrate.c (ffffffff81466e1a)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff81471ce8)
Location: include/linux/page-flags.h:587
Inline: True
```
```
In mm/page_idle.c (ffffffff814a2d32)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In fs/proc/page.c (ffffffff8157f832)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/filemap.c (ffffffff813bab8f)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/swap.c (ffffffff813cc833)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/migrate.c (ffffffff8149607d)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814a2450)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (ffffffff814d3bc2)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In fs/proc/page.c (ffffffff815b826f)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
