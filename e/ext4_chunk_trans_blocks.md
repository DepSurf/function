# Function: <code>ext4_chunk_trans_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129907c)
Location: fs/ext4/inode.c:5006
Inline: True
Inline callers:
  - fs/ext4/inode.c:_ext4_get_block
Direct callers:
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
```
**Symbols:**

```
ffffffff8129b000-ffffffff8129b015: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6996)
Location: fs/ext4/inode.c:5347
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff812c9110-ffffffff812c9125: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dc523)
Location: fs/ext4/inode.c:5491
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff812ded50-ffffffff812ded65: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81300c83)
Location: fs/ext4/inode.c:5651
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff81302d90-ffffffff81302da5: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813255f9)
Location: fs/ext4/inode.c:5704
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff81327780-ffffffff81327795: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813537c4)
Location: fs/ext4/inode.c:5800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff81355430-ffffffff81355445: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136b8f5)
Location: fs/ext4/inode.c:5852
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff8136d760-ffffffff8136d775: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394e92)
Location: fs/ext4/inode.c:5874
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff81396d60-ffffffff81396d75: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ad81e)
Location: fs/ext4/inode.c:5888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff813af790-ffffffff813af7a5: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f98b7)
Location: fs/ext4/inode.c:5609
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_writepages
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff813fb7d0-ffffffff813fb7e5: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140bea7)
Location: fs/ext4/inode.c:5700
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_writepages
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff8140df30-ffffffff8140df45: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8141212b)
Location: fs/ext4/inode.c:5697
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff814140f0-ffffffff81414105: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81464e99)
Location: fs/ext4/inode.c:5636
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff81467450-ffffffff81467465: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e4753)
Location: fs/ext4/inode.c:5714
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff814e7050-ffffffff814e706f: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157dcb3)
Location: fs/ext4/inode.c:5853
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_do_writepages
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff81580a10-ffffffff81580a2f: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b4fa2)
Location: fs/ext4/inode.c:5665
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_do_writepages
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff815b7fc0-ffffffff815b7fdf: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815edd42)
Location: fs/ext4/inode.c:5685
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_do_writepages
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff815f0d60-ffffffff815f0d7f: ext4_chunk_trans_blocks (STB_GLOBAL)
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
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff8000104820c4)
Location: fs/ext4/inode.c:5888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffff800010484128-ffff800010484160: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0643404)
Location: fs/ext4/inode.c:5888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
c064579c-c06457bc: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a697c)
Location: fs/ext4/inode.c:5888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
c0000000005a9310-c0000000005a9328: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030ab62)
Location: fs/ext4/inode.c:5888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffe00030c692-ffffffe00030c6c6: ext4_chunk_trans_blocks (STB_GLOBAL)
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
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5dfe)
Location: fs/ext4/inode.c:5888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff813a7d70-ffffffff813a7d85: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139688e)
Location: fs/ext4/inode.c:5888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff81398800-ffffffff81398815: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a365e)
Location: fs/ext4/inode.c:5888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff813a55d0-ffffffff813a55e5: ext4_chunk_trans_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_chunk_trans_blocks(struct inode *inode, int nrblocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b7d4e)
Location: fs/ext4/inode.c:5888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
**Symbols:**

```
ffffffff813b9d10-ffffffff813b9d25: ext4_chunk_trans_blocks (STB_GLOBAL)
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
