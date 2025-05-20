# Function: <code>sb_issue_zeroout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81295a3f)
Location: include/linux/blkdev.h:1134
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/resize.c (ffffffff812bfb8d)
Location: include/linux/blkdev.h:1134
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff812c273a)
Location: include/linux/blkdev.h:1134
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_zeroout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812c30df)
Location: include/linux/blkdev.h:1163
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff812c5c0b)
Location: include/linux/blkdev.h:1163
Inline: True
```
```
In fs/ext4/resize.c (ffffffff812ef396)
Location: include/linux/blkdev.h:1163
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812d86cf)
Location: include/linux/blkdev.h:1328
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff812db43b)
Location: include/linux/blkdev.h:1328
Inline: True
```
```
In fs/ext4/resize.c (ffffffff81305366)
Location: include/linux/blkdev.h:1328
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812f6aec)
Location: include/linux/blkdev.h:1366
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff812ffceb)
Location: include/linux/blkdev.h:1366
Inline: True
```
```
In fs/ext4/resize.c (ffffffff81320a77)
Location: include/linux/blkdev.h:1366
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8131b11c)
Location: include/linux/blkdev.h:1381
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8132450b)
Location: include/linux/blkdev.h:1381
Inline: True
```
```
In fs/ext4/resize.c (ffffffff8134518c)
Location: include/linux/blkdev.h:1381
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8134902c)
Location: include/linux/blkdev.h:1419
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8135273b)
Location: include/linux/blkdev.h:1419
Inline: True
```
```
In fs/ext4/resize.c (ffffffff81372d3a)
Location: include/linux/blkdev.h:1419
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813611ec)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8136a85b)
Location: include/linux/blkdev.h:1200
Inline: True
```
```
In fs/ext4/resize.c (ffffffff8138b17f)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8138a288)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff81393d6f)
Location: include/linux/blkdev.h:1214
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813b57a1)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813a2cc3)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813ac6ff)
Location: include/linux/blkdev.h:1241
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813ce260)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813eedfe)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813f89da)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
```
In fs/ext4/resize.c (ffffffff8141b862)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81401577)
Location: include/linux/blkdev.h:1363
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8140b0aa)
Location: include/linux/blkdev.h:1363
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
```
In fs/ext4/resize.c (ffffffff8142f1a3)
Location: include/linux/blkdev.h:1363
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81407b24)
Location: include/linux/blkdev.h:1348
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff81411265)
Location: include/linux/blkdev.h:1348
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
```
In fs/ext4/resize.c (ffffffff814360ab)
Location: include/linux/blkdev.h:1348
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8145a3ec)
Location: include/linux/blkdev.h:1320
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8146409e)
Location: include/linux/blkdev.h:1320
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
```
In fs/ext4/resize.c (ffffffff81489b99)
Location: include/linux/blkdev.h:1320
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff814d80ef)
Location: include/linux/blkdev.h:1131
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff814e35de)
Location: include/linux/blkdev.h:1131
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
```
In fs/ext4/resize.c (ffffffff8150cb2b)
Location: include/linux/blkdev.h:1131
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81570e70)
Location: include/linux/blkdev.h:1079
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8157cace)
Location: include/linux/blkdev.h:1079
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
```
In fs/ext4/resize.c (ffffffff815a782d)
Location: include/linux/blkdev.h:1079
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815a8c01)
Location: include/linux/blkdev.h:1059
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff815b3ece)
Location: include/linux/blkdev.h:1059
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
```
In fs/ext4/resize.c (ffffffff815de0c6)
Location: include/linux/blkdev.h:1059
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815e1924)
Location: include/linux/blkdev.h:1037
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff815eccce)
Location: include/linux/blkdev.h:1037
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
```
In fs/ext4/resize.c (ffffffff8161679d)
Location: include/linux/blkdev.h:1037
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffff800010476458)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffff800010480eac)
Location: include/linux/blkdev.h:1241
Inline: True
```
```
In fs/ext4/resize.c (ffff8000104a6864)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c0637e44)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (c0641f90)
Location: include/linux/blkdev.h:1241
Inline: True
```
```
In fs/ext4/resize.c (c06685d4)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c0000000005984a8)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (c0000000005a52dc)
Location: include/linux/blkdev.h:1241
Inline: True
```
```
In fs/ext4/resize.c (c0000000005d3ff8)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffe000301d38)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffe000309bfa)
Location: include/linux/blkdev.h:1241
Inline: True
```
```
In fs/ext4/resize.c (ffffffe000327410)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8139b2a3)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813a4cdf)
Location: include/linux/blkdev.h:1241
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813c6840)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8138bd33)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8139576f)
Location: include/linux/blkdev.h:1241
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813b72c0)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81398b03)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813a253f)
Location: include/linux/blkdev.h:1241
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813c3cd0)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813acf2b)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813b6c1f)
Location: include/linux/blkdev.h:1241
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813d8e89)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
</details>
</li>
</ul>

## Differences
