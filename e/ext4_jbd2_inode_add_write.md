# Function: <code>ext4_jbd2_inode_add_write</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6798)
Location: fs/ext4/ext4_jbd2.h:370
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81306e8b)
Location: fs/ext4/ext4_jbd2.h:370
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff812dc06e)
Location: fs/ext4/ext4_jbd2.h:370
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8131ce2f)
Location: fs/ext4/ext4_jbd2.h:370
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff813008ea)
Location: fs/ext4/ext4_jbd2.h:366
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813159e4)
Location: fs/ext4/ext4_jbd2.h:366
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff8132513f)
Location: fs/ext4/ext4_jbd2.h:366
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8133a20a)
Location: fs/ext4/ext4_jbd2.h:366
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff8135336a)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81368722)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff8136b497)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81380ba6)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff813949e6)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813a9f00)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff813ad366)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813c2e30)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff813f93b0)
Location: fs/ext4/ext4_jbd2.h:422
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8140f3f5)
Location: fs/ext4/ext4_jbd2.h:422
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412d76)
Location: fs/ext4/ext4_jbd2.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_map_blocks
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff814228b4)
Location: fs/ext4/ext4_jbd2.h:414
Inline: True
```
**Symbols:**

```
ffffffff81407e00-ffffffff81407e12: ext4_jbd2_inode_add_write.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff814191da)
Location: fs/ext4/ext4_jbd2.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_map_blocks
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff814290c3)
Location: fs/ext4/ext4_jbd2.h:414
Inline: True
```
**Symbols:**

```
ffffffff8140e180-ffffffff8140e192: ext4_jbd2_inode_add_write.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff8146c420)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_map_blocks
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8147cee3)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
```
**Symbols:**

```
ffffffff81461050-ffffffff81461062: ext4_jbd2_inode_add_write.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff814ec428)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_map_blocks
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff814ff6e7)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
```
**Symbols:**

```
ffffffff814dff40-ffffffff814dff5e: ext4_jbd2_inode_add_write.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81586193)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_map_blocks
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81599e7f)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
```
**Symbols:**

```
ffffffff81579250-ffffffff8157926e: ext4_jbd2_inode_add_write.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b484d)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:ext4_map_blocks
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff815d0779)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
```
**Symbols:**

```
ffffffff815b0750-ffffffff815b076e: ext4_jbd2_inode_add_write.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ed65d)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:ext4_map_blocks
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8160900b)
Location: fs/ext4/ext4_jbd2.h:420
Inline: True
```
**Symbols:**

```
ffffffff815e9540-ffffffff815e955e: ext4_jbd2_inode_add_write.part.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffff800010481acc)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffff80001049a71c)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (c0642c84)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (c065c0c4)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (c0000000005a629c)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (c0000000005c4eac)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffe00030a6d0)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffe00031deb6)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff813a5946)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813bb410)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff813963d6)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813abea0)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff813a31a6)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813b8c70)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/inode.c (ffffffff813b788d)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813cd990)
Location: fs/ext4/ext4_jbd2.h:363
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
</details>
</li>
</ul>

## Differences
