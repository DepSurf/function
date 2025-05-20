# Function: <code>ext4_inode_block_valid</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_inode_block_valid(struct inode *inode, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813dac10)
Location: fs/ext4/block_validity.c:328
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
ffffffff813dac10-ffffffff813dacad: ext4_inode_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_inode_block_valid(struct inode *inode, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813ec8e0)
Location: fs/ext4/block_validity.c:300
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
ffffffff813ec8e0-ffffffff813ec997: ext4_inode_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_inode_block_valid(struct inode *inode, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813f2e20)
Location: fs/ext4/block_validity.c:300
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
ffffffff813f2e20-ffffffff813f2ed7: ext4_inode_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_inode_block_valid(struct inode *inode, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81444e10)
Location: fs/ext4/block_validity.c:300
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/extents.c:ext4_valid_extent_entries
  - fs/ext4/extents.c:ext4_valid_extent_entries
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81444e10-ffffffff81444ec7: ext4_inode_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_inode_block_valid(struct inode *inode, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff814c0f84)
Location: fs/ext4/block_validity.c:343
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
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff814c0ef0-ffffffff814c0f1b: ext4_inode_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ext4_inode_block_valid(struct inode *inode, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81559134)
Location: fs/ext4/block_validity.c:343
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
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81559090-ffffffff815590bb: ext4_inode_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ext4_inode_block_valid(struct inode *inode, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81590f84)
Location: fs/ext4/block_validity.c:343
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
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81590ee0-ffffffff81590f0b: ext4_inode_block_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_inode_block_valid(struct inode *inode, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff815c9cc4)
Location: fs/ext4/block_validity.c:343
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
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff815c9c20-ffffffff815c9c4b: ext4_inode_block_valid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
