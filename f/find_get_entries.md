# Function: <code>find_get_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118fb50)
Location: mm/filemap.c:1222
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff8118fb50-ffffffff8118fc8d: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a3af0)
Location: mm/filemap.c:1273
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff811a3af0-ffffffff811a3d5b: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b3e60)
Location: mm/filemap.c:1375
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff811b3e60-ffffffff811b40c4: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811bab40)
Location: mm/filemap.c:1503
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff811bab40-ffffffff811bad08: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ce4b0)
Location: mm/filemap.c:1625
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff811ce4b0-ffffffff811ce6a3: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811f0060)
Location: mm/filemap.c:1624
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff811f0060-ffffffff811f0259: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812023f0)
Location: mm/filemap.c:1662
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff812023f0-ffffffff8120263e: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219700)
Location: mm/filemap.c:1721
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff81219700-ffffffff8121992f: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226ff0)
Location: mm/filemap.c:1724
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff81226ff0-ffffffff81227256: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812537f0)
Location: mm/filemap.c:1700
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff812537f0-ffffffff81253ac2: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e590)
Location: mm/filemap.c:1899
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff8125e590-ffffffff8125e89b: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, long unsigned int end, struct pagevec *pvec, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81262a50)
Location: mm/filemap.c:1978
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81262a50-ffffffff81262c8e: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, long unsigned int end, struct pagevec *pvec, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2033
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81cb9f79-ffffffff81cb9fb5: find_get_entries.cold (STB_LOCAL)
ffffffff8129f0a0-ffffffff8129f338: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, long unsigned int end, struct folio_batch *fbatch, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2078
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81e6b602-ffffffff81e6b628: find_get_entries.cold (STB_LOCAL)
ffffffff812f6100-ffffffff812f62d4: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int *start, long unsigned int end, struct folio_batch *fbatch, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2052
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8206226f-ffffffff8206229d: find_get_entries.cold (STB_LOCAL)
ffffffff8135fd00-ffffffff8135ff3e: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int *start, long unsigned int end, struct folio_batch *fbatch, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2023
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff820e1a0e-ffffffff820e1a3c: find_get_entries.cold (STB_LOCAL)
ffffffff81391b40-ffffffff81391dc0: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int *start, long unsigned int end, struct folio_batch *fbatch, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff821be446-ffffffff821be474: find_get_entries.cold (STB_LOCAL)
ffffffff813bb9f0-ffffffff813bbc51: find_get_entries (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3e10)
Location: mm/filemap.c:1724
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffff8000102b3e10-ffff8000102b4074: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e1644)
Location: mm/filemap.c:1724
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
c04e1644-c04e1880: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036b4f0)
Location: mm/filemap.c:1724
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
c00000000036b4f0-c00000000036b850: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d97d4)
Location: mm/filemap.c:1724
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffe0001d97d4-ffffffe0001d99a0: find_get_entries (STB_GLOBAL)
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
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121f640)
Location: mm/filemap.c:1724
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff8121f640-ffffffff8121f8a6: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812127f0)
Location: mm/filemap.c:1724
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff812127f0-ffffffff81212a56: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121d3e0)
Location: mm/filemap.c:1724
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff8121d3e0-ffffffff8121d646: find_get_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int find_get_entries(struct address_space *mapping, long unsigned int start, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122c460)
Location: mm/filemap.c:1724
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_entries
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
**Symbols:**

```
ffffffff8122c460-ffffffff8122c6d0: find_get_entries (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int end</code>
</li>
<li>
<b>Param added. </b>
<code>struct pagevec *pvec</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_entries</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page **entries</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio_batch *fbatch</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pagevec *pvec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int start</code> ➡️ <code>long unsigned int *start</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
