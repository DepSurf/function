# Function: <code>clean_bdev_aliases</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127ee00)
Location: fs/buffer.c:1628
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8127ee00-ffffffff8127f02e: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128c780)
Location: fs/buffer.c:1623
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8128c780-ffffffff8128c9a1: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af2f0)
Location: fs/buffer.c:1583
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812af2f0-ffffffff812af4f1: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d6e70)
Location: fs/buffer.c:1554
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812d6e70-ffffffff812d7067: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ec1f0)
Location: fs/buffer.c:1562
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812ec1f0-ffffffff812ec3ea: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d840)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8130d840-ffffffff8130da36: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320810)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81320810-ffffffff81320a06: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81359a90)
Location: fs/buffer.c:1607
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81359a90-ffffffff81359c86: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81367bc0)
Location: fs/buffer.c:1606
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81367bc0-ffffffff81367db6: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136e3d0)
Location: fs/buffer.c:1626
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8136e3d0-ffffffff8136e5c6: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1605
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81cc43d8-ffffffff81cc4448: clean_bdev_aliases.cold (STB_LOCAL)
ffffffff813bcfa0-ffffffff813bd1bd: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1603
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81e76dfc-ffffffff81e76e5f: clean_bdev_aliases.cold (STB_LOCAL)
ffffffff81443d70-ffffffff81443ff7: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1588
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff82068f1d-ffffffff82068f92: clean_bdev_aliases.cold (STB_LOCAL)
ffffffff814d2750-ffffffff814d296f: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1721
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/mpage.c:__mpage_writepage
  - fs/direct-io.c:do_direct_IO
```
**Symbols:**

```
ffffffff820e885a-ffffffff820e88b4: clean_bdev_aliases.cold (STB_LOCAL)
ffffffff81509060-ffffffff8150927c: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1697
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/mpage.c:__mpage_writepage
  - fs/direct-io.c:do_direct_IO
```
**Symbols:**

```
ffffffff821c5604-ffffffff821c5657: clean_bdev_aliases.cold (STB_LOCAL)
ffffffff8153dc90-ffffffff8153deae: clean_bdev_aliases (STB_GLOBAL)
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
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d7ad0)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffff8000103d7ad0-ffff8000103d7d0c: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b2444)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
c05b2444-c05b26b4: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004ddcc0)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
c0000000004ddcc0-c0000000004ddf80: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002920fa)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffe0002920fa-ffffffe0002922aa: clean_bdev_aliases (STB_GLOBAL)
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
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318df0)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81318df0-ffffffff81318fe6: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813099e0)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff813099e0-ffffffff81309bd6: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813168c0)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff813168c0-ffffffff81316ab6: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device *bdev, sector_t block, sector_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328810)
Location: fs/buffer.c:1563
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81328810-ffffffff813289f0: clean_bdev_aliases (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
