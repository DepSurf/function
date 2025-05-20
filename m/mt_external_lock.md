# Function: <code>mt_external_lock</code>

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
In kernel/fork.c (0)
Location: include/linux/maple_tree.h:559
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/maple_tree.h:559
Inline: True
```
```
In lib/maple_tree.c (ffffffff820369af)
Location: include/linux/maple_tree.h:559
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mt_free_walk
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
In kernel/fork.c (ffffffff810f2736)
Location: include/linux/maple_tree.h:568
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff813fe47c)
Location: include/linux/maple_tree.h:568
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In drivers/base/regmap/regcache-maple.c (0)
Location: include/linux/maple_tree.h:568
Inline: True
```
```
In lib/maple_tree.c (ffffffff820b592f)
Location: include/linux/maple_tree.h:568
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
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
In kernel/fork.c (ffffffff810fb21a)
Location: include/linux/maple_tree.h:750
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff8142a86a)
Location: include/linux/maple_tree.h:750
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In drivers/base/regmap/regcache-maple.c (0)
Location: include/linux/maple_tree.h:750
Inline: True
```
```
In lib/maple_tree.c (ffffffff8218faa4)
Location: include/linux/maple_tree.h:750
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_insert_range
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
