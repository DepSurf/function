# Function: <code>__folio_alloc_node</code>

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
In mm/filemap.c (ffffffff812ef5bc)
Location: include/linux/gfp.h:591
Inline: True
```
```
In mm/mempolicy.c (ffffffff8139899b)
Location: include/linux/gfp.h:591
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_alloc_folio
```
```
In mm/migrate.c (ffffffff813b128c)
Location: include/linux/gfp.h:591
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_page
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
In mm/filemap.c (ffffffff8135a0cd)
Location: include/linux/gfp.h:241
Inline: True
```
```
In mm/mempolicy.c (ffffffff814187df)
Location: include/linux/gfp.h:241
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_alloc_folio
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:241
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_page
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
In mm/filemap.c (ffffffff8138bb2d)
Location: include/linux/gfp.h:241
Inline: True
```
```
In mm/mempolicy.c (ffffffff8144bd32)
Location: include/linux/gfp.h:241
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_alloc_folio
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:241
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_folio
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
In mm/filemap.c (ffffffff813b569d)
Location: include/linux/gfp.h:242
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:242
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_folio
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
