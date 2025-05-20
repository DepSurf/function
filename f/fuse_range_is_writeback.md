# Function: <code>fuse_range_is_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813155c0)
Location: fs/fuse/file.c:338
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff813155c0-ffffffff81315677: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81349e10)
Location: fs/fuse/file.c:338
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81349e10-ffffffff81349ec7: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8135f750)
Location: fs/fuse/file.c:339
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff8135f750-ffffffff8135f807: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81374480)
Location: fs/fuse/file.c:334
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81374480-ffffffff81374537: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813987b0)
Location: fs/fuse/file.c:334
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff813987b0-ffffffff81398867: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c8c70)
Location: fs/fuse/file.c:334
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff813c8c70-ffffffff813c8d25: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e1fe0)
Location: fs/fuse/file.c:338
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff813e1fe0-ffffffff813e20a8: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140d890)
Location: fs/fuse/file.c:362
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff8140d890-ffffffff8140d8e4: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81426a90)
Location: fs/fuse/file.c:390
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81426a90-ffffffff81426ae4: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81476da0)
Location: fs/fuse/file.c:397
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepage_need_send
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81476da0-ffffffff81476e2d: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81491bb0)
Location: fs/fuse/file.c:420
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepage_need_send
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81491bb0-ffffffff81491c3d: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496d00)
Location: fs/fuse/file.c:424
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81496d00-ffffffff81496d8e: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ee5e0)
Location: fs/fuse/file.c:428
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff814ee5e0-ffffffff814ee66e: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157c7a0)
Location: fs/fuse/file.c:434
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff8157c7a0-ffffffff8157c834: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81622200)
Location: fs/fuse/file.c:434
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81622200-ffffffff81622294: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165a650)
Location: fs/fuse/file.c:435
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff8165a650-ffffffff8165a6e4: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81694320)
Location: fs/fuse/file.c:436
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81694320-ffffffff816943b4: fuse_range_is_writeback (STB_LOCAL)
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
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050aff8)
Location: fs/fuse/file.c:390
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffff80001050aff8-ffff80001050b09c: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c5db8)
Location: fs/fuse/file.c:390
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
c06c5db8-c06c5e18: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c00000000064f9c0)
Location: fs/fuse/file.c:390
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
c00000000064f9c0-c00000000064fa88: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000375d76)
Location: fs/fuse/file.c:390
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffe000375d76-ffffffe000375e00: fuse_range_is_writeback (STB_LOCAL)
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
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141f070)
Location: fs/fuse/file.c:390
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff8141f070-ffffffff8141f0c4: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140faf0)
Location: fs/fuse/file.c:390
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff8140faf0-ffffffff8140fb44: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141b210)
Location: fs/fuse/file.c:390
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff8141b210-ffffffff8141b264: fuse_range_is_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode *inode, long unsigned int idx_from, long unsigned int idx_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814318a0)
Location: fs/fuse/file.c:390
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff814318a0-ffffffff814318f2: fuse_range_is_writeback (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
