# Function: <code>sb_set_blocksize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812484d0)
Location: fs/block_dev.c:126
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff812484d0-ffffffff8124851c: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270d40)
Location: fs/block_dev.c:139
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81270d40-ffffffff81270d8c: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812846b0)
Location: fs/block_dev.c:141
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff812846b0-ffffffff812846fc: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812924b0)
Location: fs/block_dev.c:141
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff812924b0-ffffffff812924fc: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b52c0)
Location: fs/block_dev.c:129
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff812b52c0-ffffffff812b530c: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dbe50)
Location: fs/block_dev.c:129
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff812dbe50-ffffffff812dbe9c: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f1540)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff812f1540-ffffffff812f158c: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813133d0)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff813133d0-ffffffff8131341e: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326310)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81326310-ffffffff8132635e: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813603f2)
Location: fs/block_dev.c:142
Inline: True
Inline callers:
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:sb_min_blocksize
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81360360-ffffffff813603ae: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136d97f)
Location: fs/block_dev.c:174
Inline: True
Inline callers:
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:sb_min_blocksize
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8136d8f0-ffffffff8136d93e: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374360)
Location: fs/block_dev.c:173
Inline: True
Inline callers:
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:sb_min_blocksize
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff813742d0-ffffffff8137431e: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c40f0)
Location: block/bdev.c:164
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:sb_min_blocksize
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff815c4060-ffffffff815c40ae: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166f15b)
Location: block/bdev.c:160
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:sb_min_blocksize
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:__ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8166f0c0-ffffffff8166f116: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a49b)
Location: block/bdev.c:159
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:sb_min_blocksize
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_load_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8172a3e0-ffffffff8172a445: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817667d8)
Location: block/bdev.c:159
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:sb_min_blocksize
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_load_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81766720-ffffffff81766785: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a8308)
Location: block/bdev.c:162
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:sb_min_blocksize
Direct callers:
  - fs/super.c:setup_bdev_super
  - fs/ext4/super.c:ext4_load_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff817a8250-ffffffff817a82b5: sb_set_blocksize (STB_GLOBAL)
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
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e05e0)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffff8000103e05e0-ffff8000103e0654: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b93f0)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
c05b93f0-c05b944c: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e64e0)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
c0000000004e64e0-c0000000004e658c: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000297314)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffe000297314-ffffffe000297376: sb_set_blocksize (STB_GLOBAL)
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
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131e8f0)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8131e8f0-ffffffff8131e93e: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130f490)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8130f490-ffffffff8130f4de: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131c3c0)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8131c3c0-ffffffff8131c40e: sb_set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sb_set_blocksize(struct super_block *sb, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132e5c0)
Location: fs/block_dev.c:143
Inline: True
Direct callers:
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8132e5c0-ffffffff8132e60e: sb_set_blocksize (STB_GLOBAL)
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
