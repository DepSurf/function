# Function: <code>generic_writepages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81199330)
Location: mm/page-writeback.c:2319
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/mpage.c:mpage_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff81199330-ffffffff811993ab: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811afc20)
Location: mm/page-writeback.c:2364
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff811afc20-ffffffff811afca4: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c02e0)
Location: mm/page-writeback.c:2331
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff811c02e0-ffffffff811c0364: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c9052)
Location: mm/page-writeback.c:2331
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff811c84b0-ffffffff811c853c: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dde55)
Location: mm/page-writeback.c:2314
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff811dd2c0-ffffffff811dd34c: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811ff3bc)
Location: mm/page-writeback.c:2315
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff811fe420-ffffffff811fe4a4: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81211c7c)
Location: mm/page-writeback.c:2309
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff812110b0-ffffffff81211134: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812212b1)
Location: mm/page-writeback.c:2316
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff81220740-ffffffff812207c6: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122ed41)
Location: mm/page-writeback.c:2318
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff8122e1f0-ffffffff8122e276: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8125be22)
Location: mm/page-writeback.c:2328
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff81259cc0-ffffffff81259d40: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81266252)
Location: mm/page-writeback.c:2326
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff812641c0-ffffffff81264240: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8126ad57)
Location: mm/page-writeback.c:2326
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff81269d90-ffffffff81269e14: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a7b1a)
Location: mm/page-writeback.c:2335
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - block/fops.c:blkdev_writepages
```
**Symbols:**

```
ffffffff812a6a20-ffffffff812a6aa7: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81300151)
Location: mm/page-writeback.c:2414
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_submit_inode_data_buffers
  - block/fops.c:blkdev_writepages
```
**Symbols:**

```
ffffffff812fd720-ffffffff812fd7d7: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8136aaa1)
Location: mm/page-writeback.c:2552
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_submit_inode_data_buffers
```
**Symbols:**

```
ffffffff81368050-ffffffff81368107: generic_writepages (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bdf24)
Location: mm/page-writeback.c:2318
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffff8000102bd0c8-ffff8000102bd160: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04ea224)
Location: mm/page-writeback.c:2318
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
c04e95f0-c04e968c: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000376d34)
Location: mm/page-writeback.c:2318
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
c000000000375c00-c000000000375cd0: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001e09d6)
Location: mm/page-writeback.c:2318
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffe0001dfed6-ffffffe0001dff44: generic_writepages (STB_GLOBAL)
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
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81227391)
Location: mm/page-writeback.c:2318
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff81226840-ffffffff812268c6: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121a501)
Location: mm/page-writeback.c:2318
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff812199b0-ffffffff81219a36: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81225131)
Location: mm/page-writeback.c:2318
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff812245e0-ffffffff81224666: generic_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int generic_writepages(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8123440c)
Location: mm/page-writeback.c:2318
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/mpage.c:mpage_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
**Symbols:**

```
ffffffff812338b0-ffffffff81233936: generic_writepages (STB_GLOBAL)
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
