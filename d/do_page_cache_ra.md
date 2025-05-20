# Function: <code>do_page_cache_ra</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void do_page_cache_ra(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812674cf)
Location: mm/readahead.c:249
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
Direct callers:
  - mm/filemap.c:do_sync_mmap_readahead
```
**Symbols:**

```
ffffffff81267780-ffffffff812677c0: do_page_cache_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void do_page_cache_ra(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126c11a)
Location: mm/readahead.c:249
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
Direct callers:
  - mm/filemap.c:filemap_fault
```
**Symbols:**

```
ffffffff8126c390-ffffffff8126c3d0: do_page_cache_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void do_page_cache_ra(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812a8dc3)
Location: mm/readahead.c:251
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
Direct callers:
  - mm/filemap.c:filemap_fault
```
**Symbols:**

```
ffffffff812a90a0-ffffffff812a90e0: do_page_cache_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8130230a)
Location: mm/readahead.c:275
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8136caa6)
Location: mm/readahead.c:282
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8139ed00)
Location: mm/readahead.c:281
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813c8965)
Location: mm/readahead.c:281
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
