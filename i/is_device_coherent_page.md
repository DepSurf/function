# Function: <code>is_device_coherent_page</code>

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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813af277)
Location: include/linux/memremap.h:178
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_folio
```
```
In mm/rmap.c (ffffffff813da40a)
Location: include/linux/memremap.h:178
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
```
```
In mm/hugetlb.c (ffffffff81405c22)
Location: include/linux/memremap.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/migrate_device.c (ffffffff81439150)
Location: include/linux/memremap.h:178
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/memremap.h:178
Inline: True
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
In mm/gup.c (ffffffff813e3802)
Location: include/linux/memremap.h:178
Inline: True
Inline callers:
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_folio
```
```
In mm/rmap.c (ffffffff8140eb49)
Location: include/linux/memremap.h:178
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
```
```
In mm/hugetlb.c (ffffffff8143915f)
Location: include/linux/memremap.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/migrate_device.c (ffffffff8146f901)
Location: include/linux/memremap.h:178
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/memremap.h:178
Inline: True
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
In mm/gup.c (ffffffff8140e0c7)
Location: include/linux/memremap.h:179
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_folio
```
```
In mm/rmap.c (ffffffff8143b509)
Location: include/linux/memremap.h:179
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
```
```
In mm/hugetlb.c (ffffffff81472c8f)
Location: include/linux/memremap.h:179
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/migrate_device.c (ffffffff8149d51c)
Location: include/linux/memremap.h:179
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/memremap.h:179
Inline: True
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
