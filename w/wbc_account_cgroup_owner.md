# Function: <code>wbc_account_cgroup_owner</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd250)
Location: fs/fs-writeback.c:718
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812fd250-ffffffff812fd2cd: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130f740)
Location: fs/fs-writeback.c:723
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8130f740-ffffffff8130f7bd: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81348d90)
Location: fs/fs-writeback.c:724
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81348d90-ffffffff81348e0d: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81355cf0)
Location: fs/fs-writeback.c:724
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81355cf0-ffffffff81355d6d: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135c8d0)
Location: fs/fs-writeback.c:730
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8135c8d0-ffffffff8135c94d: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813aad20)
Location: fs/fs-writeback.c:854
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff813aad20-ffffffff813aad9d: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81431ba0)
Location: fs/fs-writeback.c:857
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81431ba0-ffffffff81431c43: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814bfc30)
Location: fs/fs-writeback.c:859
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff814bfc30-ffffffff814bfcd3: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f4d30)
Location: fs/fs-writeback.c:859
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
**Symbols:**

```
ffffffff814f4d30-ffffffff814f4e10: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81529440)
Location: fs/fs-writeback.c:876
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
**Symbols:**

```
ffffffff81529440-ffffffff8152951d: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c3368)
Location: fs/fs-writeback.c:723
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffff8000103c3368-ffff8000103c343c: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a1470)
Location: fs/fs-writeback.c:723
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
c05a1470-c05a1528: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c4d20)
Location: fs/fs-writeback.c:723
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
c0000000004c4d20-c0000000004c4e5c: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000283e26)
Location: fs/fs-writeback.c:723
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffe000283e26-ffffffe000283ebe: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81307d20)
Location: fs/fs-writeback.c:723
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81307d20-ffffffff81307d9d: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812f8940)
Location: fs/fs-writeback.c:723
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812f8940-ffffffff812f89bd: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81305b10)
Location: fs/fs-writeback.c:723
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81305b10-ffffffff81305b8d: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81317050)
Location: fs/fs-writeback.c:723
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81317050-ffffffff813170cd: wbc_account_cgroup_owner (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
