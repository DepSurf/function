# Function: <code>hugetlb_page_subpool</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d8d6f)
Location: include/linux/hugetlb.h:636
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff812f7604)
Location: include/linux/hugetlb.h:636
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In fs/hugetlbfs/inode.c (ffffffff81472054)
Location: include/linux/hugetlb.h:636
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131efa3)
Location: include/linux/hugetlb.h:659
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff81341c71)
Location: include/linux/hugetlb.h:659
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In fs/hugetlbfs/inode.c (ffffffff814c89e4)
Location: include/linux/hugetlb.h:659
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138b8e9)
Location: include/linux/hugetlb.h:689
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff813b3a07)
Location: include/linux/hugetlb.h:689
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In fs/hugetlbfs/inode.c (ffffffff81554135)
Location: include/linux/hugetlb.h:689
Inline: True
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
