# Function: <code>pagevec_lookup_range_tag</code>

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
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811df370)
Location: mm/swap.c:992
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff811df370-ffffffff811df3a0: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81200b30)
Location: mm/swap.c:1003
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81200b30-ffffffff81200b60: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812134a0)
Location: mm/swap.c:1004
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff812134a0-ffffffff812134d0: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81222ed0)
Location: mm/swap.c:1010
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81222ed0-ffffffff81222f00: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81230980)
Location: mm/swap.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81230980-ffffffff812309b0: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125db40)
Location: mm/swap.c:1116
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff8125db40-ffffffff8125db73: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81267f80)
Location: mm/swap.c:1118
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81267f80-ffffffff81267fb3: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126c9b0)
Location: mm/swap.c:1119
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff8126c9b0-ffffffff8126c9e3: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812a96d0)
Location: mm/swap.c:1110
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff812a96d0-ffffffff812a9703: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81302d50)
Location: mm/swap.c:1118
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81302d50-ffffffff81302d95: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136d220)
Location: mm/swap.c:1122
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff8136d220-ffffffff8136d265: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
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
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c00e0)
Location: mm/swap.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffff8000102c00e0-ffff8000102c0148: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ebc48)
Location: mm/swap.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
c04ebc48-c04ebc94: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c000000000379680)
Location: mm/swap.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
c000000000379680-c0000000003796e4: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e2120)
Location: mm/swap.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffe0001e2120-ffffffe0001e2178: pagevec_lookup_range_tag (STB_GLOBAL)
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
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228fd0)
Location: mm/swap.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81228fd0-ffffffff81229000: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121c110)
Location: mm/swap.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff8121c110-ffffffff8121c140: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81226d70)
Location: mm/swap.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81226d70-ffffffff81226da0: pagevec_lookup_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812360a0)
Location: mm/swap.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff812360a0-ffffffff812360d0: pagevec_lookup_range_tag (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int tag</code> ➡️ <code>xa_mark_t tag</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
