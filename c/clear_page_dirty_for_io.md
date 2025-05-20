# Function: <code>clear_page_dirty_for_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81198c80)
Location: mm/page-writeback.c:2649
Inline: False
Direct callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
```
**Symbols:**

```
ffffffff81198c80-ffffffff81198e15: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811af540)
Location: mm/page-writeback.c:2693
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff811af540-ffffffff811af6e4: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bfc00)
Location: mm/page-writeback.c:2660
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff811bfc00-ffffffff811bfda4: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c7dd0)
Location: mm/page-writeback.c:2663
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff811c7dd0-ffffffff811c7f92: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dcc10)
Location: mm/page-writeback.c:2646
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff811dcc10-ffffffff811dcdd2: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fdca0)
Location: mm/page-writeback.c:2647
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff811fdca0-ffffffff811fdf3a: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81210930)
Location: mm/page-writeback.c:2641
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81210930-ffffffff81210bd6: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81220070)
Location: mm/page-writeback.c:2649
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81220070-ffffffff81220284: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122db20)
Location: mm/page-writeback.c:2653
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8122db20-ffffffff8122dd34: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812595e0)
Location: mm/page-writeback.c:2663
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/vmscan.c:pageout
  - mm/migrate.c:move_to_new_page
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff812595e0-ffffffff812597d1: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81263be0)
Location: mm/page-writeback.c:2661
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/vmscan.c:pageout
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81263be0-ffffffff81263d90: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812697c0)
Location: mm/page-writeback.c:2661
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/vmscan.c:pageout
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff812697c0-ffffffff81269953: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a6420)
Location: mm/page-writeback.c:2690
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/vmscan.c:pageout
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff812a6420-ffffffff812a65bd: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300d70)
Location: mm/folio-compat.c:94
Inline: False
Direct callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:writeout
  - fs/ext4/inode.c:mpage_submit_page
```
**Symbols:**

```
ffffffff81300d70-ffffffff81300dc7: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b6b0)
Location: mm/folio-compat.c:66
Inline: False
Direct callers:
  - mm/page-writeback.c:write_cache_pages
  - fs/ext4/inode.c:mpage_submit_page
```
**Symbols:**

```
ffffffff8136b6b0-ffffffff8136b707: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d8a0)
Location: mm/folio-compat.c:67
Inline: False
```
**Symbols:**

```
ffffffff8139d8a0-ffffffff8139d904: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7500)
Location: mm/folio-compat.c:67
Inline: False
```
**Symbols:**

```
ffffffff813c7500-ffffffff813c7561: clear_page_dirty_for_io (STB_GLOBAL)
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
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bc9a0)
Location: mm/page-writeback.c:2653
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffff8000102bc9a0-ffff8000102bcc90: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e8f18)
Location: mm/page-writeback.c:2653
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
c04e8f18-c04e9128: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c0000000003753d0)
Location: mm/page-writeback.c:2653
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
c0000000003753d0-c0000000003756d8: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001df954)
Location: mm/page-writeback.c:2653
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffe0001df954-ffffffe0001dfb72: clear_page_dirty_for_io (STB_GLOBAL)
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
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81226170)
Location: mm/page-writeback.c:2653
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81226170-ffffffff81226384: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81219300)
Location: mm/page-writeback.c:2653
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81219300-ffffffff81219500: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81223f10)
Location: mm/page-writeback.c:2653
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81223f10-ffffffff81224124: clear_page_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clear_page_dirty_for_io(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812331d0)
Location: mm/page-writeback.c:2653
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/migrate.c:move_to_new_page
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff812331d0-ffffffff812333ff: clear_page_dirty_for_io (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
