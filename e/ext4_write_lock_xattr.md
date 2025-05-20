# Function: <code>ext4_write_lock_xattr</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81323fbc)
Location: fs/ext4/xattr.h:114
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/inline.c (ffffffff81328b5b)
Location: fs/ext4/xattr.h:114
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
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
In fs/ext4/inline.c (ffffffff812fcb3b)
Location: fs/ext4/xattr.h:127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81302fb6)
Location: fs/ext4/xattr.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff8133dbbb)
Location: fs/ext4/xattr.h:127
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff8132139b)
Location: fs/ext4/xattr.h:128
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813279a6)
Location: fs/ext4/xattr.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff8136219b)
Location: fs/ext4/xattr.h:128
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff8134f3ba)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81355662)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff81390957)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff8136756a)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff8136d992)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813a9537)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff8139092b)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81396f62)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813d3ab5)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff813a938b)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813af992)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813ed195)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff813f52d8)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813fb9db)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff8143a144)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff81407a78)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff8140e149)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff81452c54)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff8140dee8)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81414309)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff81458484)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff81460da8)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81467679)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff814ac584)
Location: fs/ext4/xattr.h:140
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff814df7a9)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff814e72c0)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff8153453c)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff815788ed)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81580c74)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff815d2a5c)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff815afe8d)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff815b8224)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff8160a56b)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff815e8c3d)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f0fc4)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff81643320)
Location: fs/ext4/xattr.h:153
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffff80001047cc8c)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffff800010484420)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffff8000104c5e2c)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (c063e73c)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (c0645a30)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (c0689e48)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (c0000000005a0800)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (c0000000005a9618)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (c0000000005fe268)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffe000306b06)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffe00030c8a8)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffe00034042a)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff813a196b)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a7f72)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813e5775)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff813923fb)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81398a02)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813d61f5)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff8139f1cb)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a57d2)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813e2af5)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/inline.c (ffffffff813b373b)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813b9f12)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813f7f05)
Location: fs/ext4/xattr.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
</ul>

## Differences
