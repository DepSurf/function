# Function: <code>ext4_flex_group</code>

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
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ext4.h:2797
Inline: True
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/ext4.h:2797
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: fs/ext4/ext4.h:2797
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/ext4.h:2797
Inline: True
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
In fs/ext4/ialloc.c (ffffffff812c2a73)
Location: fs/ext4/ext4.h:2832
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/super.c (ffffffff812edb4f)
Location: fs/ext4/ext4.h:2832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/resize.c (ffffffff812f0549)
Location: fs/ext4/ext4.h:2832
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff81305285)
Location: fs/ext4/ext4.h:2832
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
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
In fs/ext4/ialloc.c (ffffffff812d8047)
Location: fs/ext4/ext4.h:2810
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/super.c (ffffffff81303aee)
Location: fs/ext4/ext4.h:2810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/resize.c (ffffffff81306519)
Location: fs/ext4/ext4.h:2810
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff8131b255)
Location: fs/ext4/ext4.h:2810
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
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
In fs/ext4/ialloc.c (ffffffff812f6327)
Location: fs/ext4/ext4.h:2828
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff81312639)
Location: fs/ext4/ext4.h:2828
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff81320ec4)
Location: fs/ext4/ext4.h:2828
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81338219)
Location: fs/ext4/ext4.h:2828
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff8131a9a7)
Location: fs/ext4/ext4.h:2785
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff81336e1a)
Location: fs/ext4/ext4.h:2785
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813455fa)
Location: fs/ext4/ext4.h:2785
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8135c6fb)
Location: fs/ext4/ext4.h:2785
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff81348887)
Location: fs/ext4/ext4.h:2790
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8136540c)
Location: fs/ext4/ext4.h:2790
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813736ae)
Location: fs/ext4/ext4.h:2790
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8138b12c)
Location: fs/ext4/ext4.h:2790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff81360a37)
Location: fs/ext4/ext4.h:2817
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8137d7cc)
Location: fs/ext4/ext4.h:2817
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff8138baa3)
Location: fs/ext4/ext4.h:2817
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813a33a0)
Location: fs/ext4/ext4.h:2817
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff81389b3e)
Location: fs/ext4/ext4.h:2897
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a7381)
Location: fs/ext4/ext4.h:2897
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813b66f8)
Location: fs/ext4/ext4.h:2897
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813ce04a)
Location: fs/ext4/ext4.h:2897
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff813a24c4)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813c0211)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813cf628)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e7afe)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff813ee5b0)
Location: fs/ext4/ext4.h:3070
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8140c341)
Location: fs/ext4/ext4.h:3070
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff814192e8)
Location: fs/ext4/ext4.h:3070
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81430bb2)
Location: fs/ext4/ext4.h:3070
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff81400c6f)
Location: fs/ext4/ext4.h:3244
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8141f807)
Location: fs/ext4/ext4.h:3244
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff8142d3a1)
Location: fs/ext4/ext4.h:3244
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81449977)
Location: fs/ext4/ext4.h:3244
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff81407160)
Location: fs/ext4/ext4.h:3306
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff814260e8)
Location: fs/ext4/ext4.h:3306
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff81434066)
Location: fs/ext4/ext4.h:3306
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8144f2f7)
Location: fs/ext4/ext4.h:3306
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff8145993b)
Location: fs/ext4/ext4.h:3376
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff81479cd8)
Location: fs/ext4/ext4.h:3376
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff81487a85)
Location: fs/ext4/ext4.h:3376
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814a2e6f)
Location: fs/ext4/ext4.h:3376
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff81457070-ffffffff81457080: ext4_flex_group.isra.0 (STB_LOCAL)
ffffffff81cca18e-ffffffff81cca1b3: ext4_flex_group.isra.0.cold (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff814d7631)
Location: fs/ext4/ext4.h:3339
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff814fbeb5)
Location: fs/ext4/ext4.h:3339
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff8150b36a)
Location: fs/ext4/ext4.h:3339
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8152a395)
Location: fs/ext4/ext4.h:3339
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff814d5020-ffffffff814d503c: ext4_flex_group.isra.0 (STB_LOCAL)
ffffffff81e7cf8f-ffffffff81e7cfc0: ext4_flex_group.isra.0.cold (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff815703a8)
Location: fs/ext4/ext4.h:3352
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff8159661b)
Location: fs/ext4/ext4.h:3352
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff815a5fe3)
Location: fs/ext4/ext4.h:3352
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815c8d35)
Location: fs/ext4/ext4.h:3352
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff8156dcf0-ffffffff8156dd0c: ext4_flex_group.isra.0 (STB_LOCAL)
ffffffff8206d572-ffffffff8206d5a3: ext4_flex_group.isra.0.cold (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff815a828d)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff815cd05d)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff815dc853)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81600af9)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff815a5be0-ffffffff815a5bfc: ext4_flex_group.isra.0 (STB_LOCAL)
ffffffff820ed2cb-ffffffff820ed2fc: ext4_flex_group.isra.0.cold (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff815e104a)
Location: fs/ext4/ext4.h:3351
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff816016e3)
Location: fs/ext4/ext4.h:3351
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_context
```
```
In fs/ext4/resize.c (ffffffff81615133)
Location: fs/ext4/ext4.h:3351
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81639849)
Location: fs/ext4/ext4.h:3351
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff815dea50-ffffffff815dea6c: ext4_flex_group.isra.0 (STB_LOCAL)
ffffffff821ca411-ffffffff821ca442: ext4_flex_group.isra.0.cold (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffff800010475b10)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffff800010496e84)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffff8000104a8038)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104c04bc)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (c06373d0)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (c0658f24)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (c066a1fc)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0683c10)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (c0000000005977fc)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (c0000000005c11a0)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (c0000000005d59dc)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0000000005f6d44)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffe00030150c)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffe00031b88a)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffe0003284b8)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffe00033c39e)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff8139aaa4)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b87f1)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813c7c08)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e00de)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff8138b534)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a9281)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813b8688)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d0b5e)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff81398304)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b6051)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813c5098)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813dd457)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
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
In fs/ext4/ialloc.c (ffffffff813ac6d9)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813cadcd)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813da3cf)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813f2873)
Location: fs/ext4/ext4.h:2959
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
</details>
</li>
</ul>

## Differences
