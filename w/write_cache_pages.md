# Function: <code>write_cache_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81198e20)
Location: mm/page-writeback.c:2142
Inline: False
Direct callers:
  - mm/page-writeback.c:generic_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81198e20-ffffffff81199324: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811af6f0)
Location: mm/page-writeback.c:2187
Inline: False
Direct callers:
  - mm/page-writeback.c:generic_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff811af6f0-ffffffff811afc1a: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bfdb0)
Location: mm/page-writeback.c:2154
Inline: False
Direct callers:
  - mm/page-writeback.c:generic_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff811bfdb0-ffffffff811c02da: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c7fa0)
Location: mm/page-writeback.c:2154
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff811c7fa0-ffffffff811c84a5: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dcde0)
Location: mm/page-writeback.c:2153
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff811dcde0-ffffffff811dd2b3: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fdf40)
Location: mm/page-writeback.c:2154
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff811fdf40-ffffffff811fe420: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81210be0)
Location: mm/page-writeback.c:2151
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81210be0-ffffffff812110a2: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81220290)
Location: mm/page-writeback.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81220290-ffffffff81220735: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122dd40)
Location: mm/page-writeback.c:2158
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff8122dd40-ffffffff8122e1e5: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812597e0)
Location: mm/page-writeback.c:2170
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff812597e0-ffffffff81259cb6: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81263d90)
Location: mm/page-writeback.c:2168
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81263d90-ffffffff812641bf: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81269960)
Location: mm/page-writeback.c:2168
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81269960-ffffffff81269d8f: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a65c0)
Location: mm/page-writeback.c:2177
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff812a65c0-ffffffff812a6a18: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812fd1e0)
Location: mm/page-writeback.c:2256
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/ext4/super.c:ext4_journalled_submit_inode_data_buffers
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff812fd1e0-ffffffff812fd716: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81367b00)
Location: mm/page-writeback.c:2394
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/super.c:ext4_journalled_submit_inode_data_buffers
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81367b00-ffffffff81368036: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139a190)
Location: mm/page-writeback.c:2394
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/ext4/super.c:ext4_journalled_submit_inode_data_buffers
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff8139a190-ffffffff8139a5c0: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c3e40)
Location: mm/page-writeback.c:2394
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/ext4/super.c:ext4_journalled_submit_inode_data_buffers
  - fs/fuse/file.c:fuse_writepages
  - block/fops.c:blkdev_writepages
```
**Symbols:**

```
ffffffff813c3e40-ffffffff813c426b: write_cache_pages (STB_GLOBAL)
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
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bcc90)
Location: mm/page-writeback.c:2158
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffff8000102bcc90-ffff8000102bd0c4: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e9128)
Location: mm/page-writeback.c:2158
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
c04e9128-c04e95f0: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c0000000003756e0)
Location: mm/page-writeback.c:2158
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
c0000000003756e0-c000000000375bfc: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001dfb72)
Location: mm/page-writeback.c:2158
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffe0001dfb72-ffffffe0001dfed6: write_cache_pages (STB_GLOBAL)
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
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81226390)
Location: mm/page-writeback.c:2158
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81226390-ffffffff81226835: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81219500)
Location: mm/page-writeback.c:2158
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81219500-ffffffff812199a5: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81224130)
Location: mm/page-writeback.c:2158
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81224130-ffffffff812245d5: write_cache_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int write_cache_pages(struct address_space *mapping, struct writeback_control *wbc, writepage_t writepage, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81233400)
Location: mm/page-writeback.c:2158
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/fuse/file.c:fuse_writepages
```
**Symbols:**

```
ffffffff81233400-ffffffff812338af: write_cache_pages (STB_GLOBAL)
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
