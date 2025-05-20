# Function: <code>try_to_free_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243950)
Location: fs/buffer.c:3214
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81243950-ffffffff81243a1a: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126c8d0)
Location: fs/buffer.c:3273
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8126c8d0-ffffffff8126c9ab: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127f930)
Location: fs/buffer.c:3314
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8127f930-ffffffff8127fa0b: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128d130)
Location: fs/buffer.c:3299
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8128d130-ffffffff8128d20b: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af950)
Location: fs/buffer.c:3267
Inline: False
Direct callers:
  - mm/filemap.c:try_to_release_page
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff812af950-ffffffff812afa53: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d77d0)
Location: fs/buffer.c:3238
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff812d77d0-ffffffff812d78d3: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ecc30)
Location: fs/buffer.c:3250
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff812ecc30-ffffffff812ecd33: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130e3e0)
Location: fs/buffer.c:3257
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8130e3e0-ffffffff8130e4e8: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81321400)
Location: fs/buffer.c:3234
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81321400-ffffffff81321508: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135bb40)
Location: fs/buffer.c:3244
Inline: False
Direct callers:
  - mm/filemap.c:try_to_release_page
  - mm/vmscan.c:pageout
  - mm/migrate.c:__unmap_and_move
  - fs/buffer.c:grow_dev_page
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:release_buffer_page
```
**Symbols:**

```
ffffffff8135bb40-ffffffff8135bc4c: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136a0e0)
Location: fs/buffer.c:3225
Inline: False
Direct callers:
  - mm/filemap.c:try_to_release_page
  - mm/vmscan.c:pageout
  - mm/migrate.c:__unmap_and_move
  - fs/buffer.c:grow_dev_page
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:release_buffer_page
```
**Symbols:**

```
ffffffff8136a0e0-ffffffff8136a1ec: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81370d00)
Location: fs/buffer.c:3246
Inline: False
Direct callers:
  - mm/filemap.c:try_to_release_page
  - mm/vmscan.c:pageout
  - mm/migrate.c:__unmap_and_move
  - fs/buffer.c:grow_dev_page
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:release_buffer_page
```
**Symbols:**

```
ffffffff81370d00-ffffffff81370e0b: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bf950)
Location: fs/buffer.c:3225
Inline: False
Direct callers:
  - mm/filemap.c:try_to_release_page
  - mm/vmscan.c:pageout
  - mm/migrate.c:__unmap_and_move
  - fs/buffer.c:grow_dev_page
  - fs/ext4/inode.c:ext4_releasepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:release_buffer_page
```
**Symbols:**

```
ffffffff813bf950-ffffffff813bfab1: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool try_to_free_buffers(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814438b0)
Location: fs/buffer.c:3210
Inline: False
Direct callers:
  - mm/filemap.c:filemap_release_folio
  - mm/vmscan.c:pageout
  - fs/buffer.c:grow_dev_page
  - fs/ext4/inode.c:ext4_release_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:release_buffer_page
```
**Symbols:**

```
ffffffff814438b0-ffffffff8144398e: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool try_to_free_buffers(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d2110)
Location: fs/buffer.c:2815
Inline: False
Direct callers:
  - mm/filemap.c:filemap_release_folio
  - mm/vmscan.c:pageout
  - fs/buffer.c:grow_dev_page
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/ext4/inode.c:ext4_release_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:release_buffer_page
```
**Symbols:**

```
ffffffff814d2110-ffffffff814d21ee: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool try_to_free_buffers(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81509b20)
Location: fs/buffer.c:2953
Inline: False
Direct callers:
  - mm/filemap.c:filemap_release_folio
  - mm/vmscan.c:pageout
  - mm/migrate.c:migrate_folio_unmap
  - fs/buffer.c:__getblk_slow
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/ext4/inode.c:ext4_release_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81509b20-ffffffff81509bfe: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool try_to_free_buffers(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153e950)
Location: fs/buffer.c:2913
Inline: False
Direct callers:
  - mm/filemap.c:filemap_release_folio
  - mm/vmscan.c:pageout
  - mm/migrate.c:migrate_folio_unmap
  - fs/buffer.c:__getblk_slow
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/inode.c:ext4_release_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8153e950-ffffffff8153ea2e: try_to_free_buffers (STB_GLOBAL)
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
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d8778)
Location: fs/buffer.c:3234
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffff8000103d8778-ffff8000103d88e8: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b31ac)
Location: fs/buffer.c:3234
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_slow
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c05b31ac-c05b32ec: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dea50)
Location: fs/buffer.c:3234
Inline: False
Direct callers:
  - mm/filemap.c:try_to_release_page
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c0000000004dea50-c0000000004dec00: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000292e34)
Location: fs/buffer.c:3234
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffe000292e34-ffffffe000292f62: try_to_free_buffers (STB_GLOBAL)
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
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813199e0)
Location: fs/buffer.c:3234
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813199e0-ffffffff81319ae8: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130a5a0)
Location: fs/buffer.c:3234
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8130a5a0-ffffffff8130a6a8: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813174b0)
Location: fs/buffer.c:3234
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813174b0-ffffffff813175b8: try_to_free_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int try_to_free_buffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813290a0)
Location: fs/buffer.c:3234
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - fs/buffer.c:__getblk_gfp
  - fs/block_dev.c:blkdev_releasepage
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813290a0-ffffffff813291a5: try_to_free_buffers (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
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
