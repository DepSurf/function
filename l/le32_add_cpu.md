# Function: <code>le32_add_cpu</code>

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
In fs/ext4/super.c (ffffffff812ac29b)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
```
```
In fs/ext4/resize.c (ffffffff812c0b70)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff812c4a2c)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/xattr.c (ffffffff812dd104)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/super.c (ffffffff812e0a0b)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
```
```
In fs/ext4/resize.c (ffffffff812f0489)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff812f4277)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/super.c (ffffffff812f654b)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
```
```
In fs/ext4/resize.c (ffffffff81306459)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff8130a21a)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff812e88ab)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff81320df8)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8132ae3b)
Location: include/linux/byteorder/generic.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff8130d34b)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff8134552e)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8134f29b)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff8133c5ea)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff813735d4)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8137d757)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff81353c9a)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff8138b9c9)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81395f06)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff8137d7f5)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff813b6615)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813bfed6)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff81395f15)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff813cf545)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d91a6)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff813e0682)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
```
```
In fs/ext4/resize.c (ffffffff81419222)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814256b4)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff813f1f1b)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
```
```
In fs/ext4/resize.c (ffffffff8142d21a)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81444991)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
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
In fs/ext4/extents.c (ffffffff813f84a7)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
```
```
In fs/ext4/resize.c (ffffffff81433ee7)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8144a21b)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
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
In fs/ext4/extents.c (ffffffff8144a98d)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
```
```
In fs/ext4/resize.c (ffffffff814878ae)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8149e6e1)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
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
In fs/ext4/extents.c (ffffffff814c7143)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
```
```
In fs/ext4/resize.c (ffffffff8150b170)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81524dcf)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
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
In fs/ext4/extents.c (ffffffff8155f753)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
```
```
In fs/ext4/resize.c (ffffffff815a5d60)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815c229c)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
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
In fs/ext4/extents.c (ffffffff815974bf)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
```
```
In fs/ext4/resize.c (ffffffff815dc5d0)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815f9a1c)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
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
In fs/ext4/extents.c (ffffffff815d016f)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
```
```
In fs/ext4/resize.c (ffffffff81614eb0)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8163261c)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
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
In fs/ext4/extents.c (ffff800010468d38)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffff8000104a7e94)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104ac83c)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (c0629a14)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (c066a0f8)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0674e78)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (c000000000587270)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (c0000000005d57c8)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0000000005e473c)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffe0002f673e)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffe0003283ee)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffe00032fbd8)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff8138e4f5)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff813c7b25)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d1786)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff8137ef85)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff813b85a5)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813c2206)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff8138be55)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff813c4fb5)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813cec16)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
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
In fs/ext4/extents.c (ffffffff8139fba5)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
```
In fs/ext4/resize.c (ffffffff813da1a9)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e3e66)
Location: include/linux/byteorder/generic.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__save_error_info
```
</details>
</li>
</ul>

## Differences
