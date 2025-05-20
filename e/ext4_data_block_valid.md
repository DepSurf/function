# Function: <code>ext4_data_block_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff812d64a0)
Location: fs/ext4/block_validity.c:196
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff812d64a0-ffffffff812d651e: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81306130)
Location: fs/ext4/block_validity.c:196
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff81306130-ffffffff813061ae: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff8131c0f0)
Location: fs/ext4/block_validity.c:196
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff8131c0f0-ffffffff8131c16e: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff812e4cc0)
Location: fs/ext4/block_validity.c:196
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff812e4cc0-ffffffff812e4d3a: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813096f0)
Location: fs/ext4/block_validity.c:197
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff813096f0-ffffffff8130976a: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813375d0)
Location: fs/ext4/block_validity.c:197
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff813375d0-ffffffff8133764e: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff8134e850)
Location: fs/ext4/block_validity.c:197
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff8134e850-ffffffff8134e8ce: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81377040)
Location: fs/ext4/block_validity.c:247
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81377040-ffffffff813770be: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff8138f7d2)
Location: fs/ext4/block_validity.c:342
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff8138f730-ffffffff8138f753: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffff8000104620e4)
Location: fs/ext4/block_validity.c:342
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffff800010462018-ffff800010462060: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c0622694)
Location: fs/ext4/block_validity.c:342
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
c06225e0-c0622610: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c00000000057ea74)
Location: fs/ext4/block_validity.c:342
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
c00000000057e980-c00000000057e9c0: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffe0002f0f98)
Location: fs/ext4/block_validity.c:342
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffe0002f0ed6-ffffffe0002f0f14: ext4_data_block_valid (STB_GLOBAL)
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
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81387db2)
Location: fs/ext4/block_validity.c:342
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81387d10-ffffffff81387d33: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81378842)
Location: fs/ext4/block_validity.c:342
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff813787a0-ffffffff813787c3: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81385882)
Location: fs/ext4/block_validity.c:342
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff813857e0-ffffffff81385803: ext4_data_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info *sbi, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81399350)
Location: fs/ext4/block_validity.c:342
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81399350-ffffffff81399394: ext4_data_block_valid (STB_GLOBAL)
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
