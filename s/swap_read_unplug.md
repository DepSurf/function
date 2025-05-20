# Function: <code>swap_read_unplug</code>

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
In mm/madvise.c (ffffffff81376226)
Location: mm/swap.h:14
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff8137a2d8)
Location: mm/swap.h:14
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
```
```
In mm/swap_state.c (ffffffff8137c26c)
Location: mm/swap.h:14
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/madvise.c (ffffffff813f3b73)
Location: mm/swap.h:14
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff813f7d85)
Location: mm/swap.h:14
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
```
```
In mm/swap_state.c (ffffffff813f9a0c)
Location: mm/swap.h:14
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/madvise.c (ffffffff81427646)
Location: mm/swap.h:13
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff8142af29)
Location: mm/swap.h:13
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
```
```
In mm/swap_state.c (ffffffff8142c8a6)
Location: mm/swap.h:13
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/madvise.c (ffffffff81460d0e)
Location: mm/swap.h:16
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff8146472c)
Location: mm/swap.h:16
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_read_folio_fs
```
```
In mm/swap_state.c (ffffffff81465fd2)
Location: mm/swap.h:16
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
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
