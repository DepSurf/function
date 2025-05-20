# Function: <code>pagevec_lookup_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int pagevec_lookup_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, int tag, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119cad0)
Location: mm/swap.c:1133
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff8119cad0-ffffffff8119caf9: pagevec_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int pagevec_lookup_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, int tag, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b1ae0)
Location: mm/swap.c:959
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff811b1ae0-ffffffff811b1b09: pagevec_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int pagevec_lookup_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, int tag, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c2140)
Location: mm/swap.c:959
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff811c2140-ffffffff811c2169: pagevec_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int pagevec_lookup_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, int tag, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811ca4b0)
Location: mm/swap.c:972
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff811ca4b0-ffffffff811ca4d9: pagevec_lookup_tag (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
