# Function: <code>readahead_index</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81477ec8)
Location: include/linux/pagemap.h:811
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126739d)
Location: include/linux/pagemap.h:968
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/fuse/file.c (ffffffff81492b96)
Location: include/linux/pagemap.h:968
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126bff4)
Location: include/linux/pagemap.h:1010
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/fuse/file.c (ffffffff814975fc)
Location: include/linux/pagemap.h:1010
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff812a8cd4)
Location: include/linux/pagemap.h:1013
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/fuse/file.c (ffffffff814ef15c)
Location: include/linux/pagemap.h:1013
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff81301ee0)
Location: include/linux/pagemap.h:1378
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/fuse/file.c (ffffffff8157ee75)
Location: include/linux/pagemap.h:1378
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff8136c6c0)
Location: include/linux/pagemap.h:1354
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/fuse/file.c (ffffffff81624b3f)
Location: include/linux/pagemap.h:1354
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff8139e8ed)
Location: include/linux/pagemap.h:1357
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/fuse/file.c (ffffffff8165cf2f)
Location: include/linux/pagemap.h:1357
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff813c855d)
Location: include/linux/pagemap.h:1444
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/fuse/file.c (ffffffff81696c8c)
Location: include/linux/pagemap.h:1444
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
