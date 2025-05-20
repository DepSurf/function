# Function: <code>dax_writeback_mapping_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff81287280)
Location: fs/dax.c:736
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff81287280-ffffffff812875c4: dax_writeback_mapping_range.part.17 (STB_LOCAL)
ffffffff812875d0-ffffffff8128762f: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff8129b590)
Location: fs/dax.c:853
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff8129b590-ffffffff8129bc2f: dax_writeback_mapping_range.part.25 (STB_LOCAL)
ffffffff8129bc30-ffffffff8129bc8f: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812aa310)
Location: fs/dax.c:761
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff812aa310-ffffffff812aabbb: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812cdb40)
Location: fs/dax.c:769
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff812cdb40-ffffffff812ce3ed: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f8290)
Location: fs/dax.c:1016
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffff812f8290-ffffffff812f89f8: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130eb90)
Location: fs/dax.c:933
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffff8130eb90-ffffffff8130f09c: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:938
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffff813367dd-ffffffff813367f0: dax_writeback_mapping_range.cold (STB_LOCAL)
ffffffff81334880-ffffffff81334d8f: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81348450)
Location: fs/dax.c:939
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffff81348450-ffffffff8134896b: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct dax_device *dax_dev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138df80)
Location: fs/dax.c:939
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffff8138df80-ffffffff8138e265: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct dax_device *dax_dev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139f6f0)
Location: fs/dax.c:955
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/fuse/dax.c:fuse_dax_writepages
```
**Symbols:**

```
ffffffff8139f6f0-ffffffff8139f9b6: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct dax_device *dax_dev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a6460)
Location: fs/dax.c:967
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/fuse/dax.c:fuse_dax_writepages
```
**Symbols:**

```
ffffffff813a6460-ffffffff813a672e: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct dax_device *dax_dev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f5ed0)
Location: fs/dax.c:967
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/fuse/dax.c:fuse_dax_writepages
```
**Symbols:**

```
ffffffff813f5ed0-ffffffff813f61cf: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct dax_device *dax_dev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81469a90)
Location: fs/dax.c:893
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/fuse/dax.c:fuse_dax_writepages
```
**Symbols:**

```
ffffffff81469a90-ffffffff81469dc9: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct dax_device *dax_dev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814fa1e0)
Location: fs/dax.c:1012
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/fuse/dax.c:fuse_dax_writepages
```
**Symbols:**

```
ffffffff814fa1e0-ffffffff814fa509: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct dax_device *dax_dev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81531660)
Location: fs/dax.c:1039
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/fuse/dax.c:fuse_dax_writepages
```
**Symbols:**

```
ffffffff81531660-ffffffff81531976: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct dax_device *dax_dev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81566540)
Location: fs/dax.c:1025
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/fuse/dax.c:fuse_dax_writepages
```
**Symbols:**

```
ffffffff81566540-ffffffff81566856: dax_writeback_mapping_range (STB_GLOBAL)
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
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff8000104093d8)
Location: fs/dax.c:939
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffff8000104093d8-ffff800010409a18: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000514950)
Location: fs/dax.c:939
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
c000000000514950-c0000000005150c8: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b408c)
Location: fs/dax.c:939
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffe0002b408c-ffffffe0002b4612: dax_writeback_mapping_range (STB_GLOBAL)
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
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81340a30)
Location: fs/dax.c:939
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffff81340a30-ffffffff81340f4b: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81331420)
Location: fs/dax.c:939
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffff81331420-ffffffff81331929: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133e500)
Location: fs/dax.c:939
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffff8133e500-ffffffff8133ea1b: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space *mapping, struct block_device *bdev, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813513a0)
Location: fs/dax.c:939
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dax_writepages
```
**Symbols:**

```
ffffffff813513a0-ffffffff813518ec: dax_writeback_mapping_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dax_device *dax_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
</ul>
</details>
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
