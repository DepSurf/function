# Function: <code>folio_set_idle</code>

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
In mm/migrate.c (ffffffff813b0930)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff813b9d53)
Location: include/linux/page-flags.h:614
Inline: True
```
```
In mm/page_idle.c (ffffffff813e6791)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff814314a4)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff8143c830)
Location: include/linux/page-flags.h:593
Inline: True
```
```
In mm/page_idle.c (ffffffff8146e291)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff81466e24)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff81471dde)
Location: include/linux/page-flags.h:587
Inline: True
```
```
In mm/page_idle.c (ffffffff814a2c3d)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff81496087)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814a245a)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (ffffffff814d3acd)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
