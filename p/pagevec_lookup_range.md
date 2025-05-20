# Function: <code>pagevec_lookup_range</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811df340)
Location: mm/swap.c:983
Inline: False
Direct callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff811df340-ffffffff811df36c: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81200b00)
Location: mm/swap.c:994
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81200b00-ffffffff81200b2c: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81213470)
Location: mm/swap.c:995
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81213470-ffffffff8121349c: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81222ea0)
Location: mm/swap.c:1001
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81222ea0-ffffffff81222ecc: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81230950)
Location: mm/swap.c:1041
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81230950-ffffffff8123097c: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125db10)
Location: mm/swap.c:1107
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8125db10-ffffffff8125db3f: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81267f50)
Location: mm/swap.c:1109
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81267f50-ffffffff81267f7f: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126c980)
Location: mm/swap.c:1110
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unlock_mapping
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8126c980-ffffffff8126c9af: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812a96a0)
Location: mm/swap.c:1101
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unlock_mapping
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812a96a0-ffffffff812a96cf: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81302d10)
Location: mm/swap.c:1109
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unlock_mapping
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81302d10-ffffffff81302d4e: pagevec_lookup_range (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c0088)
Location: mm/swap.c:1041
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffff8000102c0088-ffff8000102c00e0: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ebc00)
Location: mm/swap.c:1041
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
c04ebc00-c04ebc48: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c000000000379620)
Location: mm/swap.c:1041
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
c000000000379620-c000000000379680: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e20d0)
Location: mm/swap.c:1041
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffe0001e20d0-ffffffe0001e2120: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228fa0)
Location: mm/swap.c:1041
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81228fa0-ffffffff81228fcc: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121c0e0)
Location: mm/swap.c:1041
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8121c0e0-ffffffff8121c10c: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81226d40)
Location: mm/swap.c:1041
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81226d40-ffffffff81226d6c: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec *pvec, struct address_space *mapping, long unsigned int *start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81236070)
Location: mm/swap.c:1041
Inline: False
Direct callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81236070-ffffffff8123609c: pagevec_lookup_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
