# Function: <code>le16_add_cpu</code>

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
In fs/ext4/super.c (ffffffff812ba96b)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
```
```
In fs/ext4/resize.c (ffffffff812c06b6)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff812c3927)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
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
In fs/ext4/super.c (ffffffff812e989b)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
```
```
In fs/ext4/resize.c (ffffffff812efe00)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff812f6571)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
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
In fs/ext4/super.c (ffffffff812ff60b)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
```
```
In fs/ext4/resize.c (ffffffff81305dd0)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff8130c521)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
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
In fs/ext4/extents.c (ffffffff812eb02d)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
```
```
In fs/ext4/resize.c (ffffffff81320046)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/super.c (ffffffff81334425)
Location: include/linux/byteorder/generic.h:143
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8130fad3)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
```
```
In fs/ext4/resize.c (ffffffff81344700)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/super.c (ffffffff81358935)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8133b30f)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffffffff8137270d)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/super.c (ffffffff813872d4)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff813525bb)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffffffff8138a92c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/super.c (ffffffff8139fddc)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8137be5d)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffffffff813b505c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff813ca12c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8139432d)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffffffff813ceb3c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff813e342c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff813e030b)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
```
```
In fs/ext4/resize.c (ffffffff8141beb7)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff81430378)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff813f1b8b)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
```
```
In fs/ext4/resize.c (ffffffff8142fbe3)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff814490b8)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff813f800b)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
```
```
In fs/ext4/resize.c (ffffffff814368a5)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8144ea36)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8144a4f5)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
```
```
In fs/ext4/resize.c (ffffffff8148a4c9)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff814a2508)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff814c6c53)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
```
```
In fs/ext4/resize.c (ffffffff8150de8d)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8152982e)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8155f1db)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
```
```
In fs/ext4/resize.c (ffffffff815a8ce2)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff815c7fdb)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff81596f9a)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
```
```
In fs/ext4/resize.c (ffffffff815df563)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff815ffdeb)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff815cfc4a)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
```
```
In fs/ext4/resize.c (ffffffff81618043)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff81638b3b)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffff8000104670b0)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffff8000104a7488)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffff8000104bc9bc)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (c0627bc4)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (c06695e4)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (c068005c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (c000000000585244)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (c0000000005d4e7c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (c0000000005f2820)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffe0002f4f22)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffffffe000327e34)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffe0003386d4)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8138c90d)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffffffff813c711c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff813dba0c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8137d39d)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffffffff813b7b9c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff813cc48c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8138a26d)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffffffff813c45ac)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff813d8eac)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
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
In fs/ext4/extents.c (ffffffff8139df9d)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/resize.c (ffffffff813d9786)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff813ee19c)
Location: include/linux/byteorder/generic.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_setup_super
```
</details>
</li>
</ul>

## Differences
