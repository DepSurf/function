# Function: <code>ext4_has_feature_dir_index</code>

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
In fs/ext4/dir.c (ffffffff8129093d)
Location: fs/ext4/ext4.h:1690
Inline: True
```
```
In fs/ext4/file.c (ffffffff81291924)
Location: fs/ext4/ext4.h:1690
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/namei.c (ffffffff812a1a46)
Location: fs/ext4/ext4.h:1690
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
```
```
In fs/ext4/super.c (ffffffff812bc9f6)
Location: fs/ext4/ext4.h:1690
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/inline.c (ffffffff812e03f8)
Location: fs/ext4/ext4.h:1690
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
In fs/ext4/dir.c (ffffffff812bde5d)
Location: fs/ext4/ext4.h:1758
Inline: True
```
```
In fs/ext4/file.c (ffffffff812bee82)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/namei.c (ffffffff812d36dd)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff812eb997)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/inline.c (ffffffff813100bf)
Location: fs/ext4/ext4.h:1758
Inline: True
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
In fs/ext4/dir.c (ffffffff812d35ed)
Location: fs/ext4/ext4.h:1743
Inline: True
```
```
In fs/ext4/file.c (ffffffff812d44a2)
Location: fs/ext4/ext4.h:1743
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/namei.c (ffffffff812e942d)
Location: fs/ext4/ext4.h:1743
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813019bb)
Location: fs/ext4/ext4.h:1743
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/inline.c (ffffffff81325c9e)
Location: fs/ext4/ext4.h:1743
Inline: True
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
In fs/ext4/dir.c (ffffffff812e4ecd)
Location: fs/ext4/ext4.h:1748
Inline: True
```
```
In fs/ext4/file.c (ffffffff812f0e25)
Location: fs/ext4/ext4.h:1748
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff812f9ce1)
Location: fs/ext4/ext4.h:1748
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8131c4c3)
Location: fs/ext4/ext4.h:1748
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8133684f)
Location: fs/ext4/ext4.h:1748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff813098fd)
Location: fs/ext4/ext4.h:1708
Inline: True
```
```
In fs/ext4/file.c (ffffffff81315a55)
Location: fs/ext4/ext4.h:1708
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff8131e311)
Location: fs/ext4/ext4.h:1708
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81340ab2)
Location: fs/ext4/ext4.h:1708
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8135ae49)
Location: fs/ext4/ext4.h:1708
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff81337789)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff81343865)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff8134c520)
Location: fs/ext4/ext4.h:1711
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8136baca)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff81389723)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff8134ea09)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff8135b9a5)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff81364660)
Location: fs/ext4/ext4.h:1724
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81383f8a)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813a22bb)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff81377559)
Location: fs/ext4/ext4.h:1744
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff813851b5)
Location: fs/ext4/ext4.h:1744
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8138cf52)
Location: fs/ext4/ext4.h:1744
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813ad742)
Location: fs/ext4/ext4.h:1744
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813ccbd4)
Location: fs/ext4/ext4.h:1744
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff8138f8b9)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff8139dc55)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813a59a2)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813aec78)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff813c6681)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813e6099)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff813db0d9)
Location: fs/ext4/ext4.h:1896
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff813e9745)
Location: fs/ext4/ext4.h:1896
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff813f18f2)
Location: fs/ext4/ext4.h:1896
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff813facfa)
Location: fs/ext4/ext4.h:1896
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff81412ba5)
Location: fs/ext4/ext4.h:1896
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff81433199)
Location: fs/ext4/ext4.h:1896
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff813ecb09)
Location: fs/ext4/ext4.h:2020
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff813fb3f5)
Location: fs/ext4/ext4.h:2020
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff81404412)
Location: fs/ext4/ext4.h:2020
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8140d369)
Location: fs/ext4/ext4.h:2020
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff8142605c)
Location: fs/ext4/ext4.h:2020
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8144bf9c)
Location: fs/ext4/ext4.h:2020
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff813f3049)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff814018c5)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff8140a9f5)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff81413524)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff8142cbff)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff814518a4)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff81445039)
Location: fs/ext4/ext4.h:2094
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff81453e55)
Location: fs/ext4/ext4.h:2094
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff8145d64f)
Location: fs/ext4/ext4.h:2094
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff81466858)
Location: fs/ext4/ext4.h:2094
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff81480b36)
Location: fs/ext4/ext4.h:2094
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff814a4f0e)
Location: fs/ext4/ext4.h:2094
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff814c10e9)
Location: fs/ext4/ext4.h:2096
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff814d0e15)
Location: fs/ext4/ext4.h:2096
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff814db89a)
Location: fs/ext4/ext4.h:2096
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814e63c7)
Location: fs/ext4/ext4.h:2096
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff81503a63)
Location: fs/ext4/ext4.h:2096
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8152ce93)
Location: fs/ext4/ext4.h:2096
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
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
In fs/ext4/dir.c (ffffffff815592c9)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff81569845)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff8157428b)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8157fb5c)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff8159e5d7)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff815cb74f)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
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
In fs/ext4/dir.c (ffffffff815910f9)
Location: fs/ext4/ext4.h:2100
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff815a1635)
Location: fs/ext4/ext4.h:2100
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff815ac0db)
Location: fs/ext4/ext4.h:2100
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff815b6ffe)
Location: fs/ext4/ext4.h:2100
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff815d4ee7)
Location: fs/ext4/ext4.h:2100
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8160320e)
Location: fs/ext4/ext4.h:2100
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
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
In fs/ext4/dir.c (ffffffff815c9e39)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff815da3f5)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (ffffffff815e4e70)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff815efd9e)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff8160d577)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8163c027)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
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
In fs/ext4/dir.c (ffff800010462174)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffff8000104711a0)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inline.c (ffff800010479184)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inode.c (ffff80001048360c)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffff80001049e17c)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffff8000104bf3c0)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (c062270c)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (c0631b54)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inline.c (c063aeac)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (c0644aa0)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (c065fe6c)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (c0682ed4)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (c00000000057eb3c)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (c000000000590e08)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/inline.c (c00000000059bd6c)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inode.c (c0000000005a8694)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (c0000000005c9b2c)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (c0000000005f5a38)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffe0002f0fe8)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffe0002fd1b8)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inline.c (ffffffe0003044c0)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inode.c (ffffffe00030bda2)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffe000320ca4)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffe00033a6a4)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff81387e99)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff81396235)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139df82)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a7258)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff813bec61)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813de679)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff81378929)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff81386cc5)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8138ea12)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81397ce8)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff813af6f1)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813cf0f9)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff81385969)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff81393b95)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139b7e2)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a4ab8)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff813bc241)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813dba36)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/dir.c (ffffffff813994e9)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/file.c (ffffffff813a7c25)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813afca2)
Location: fs/ext4/ext4.h:1800
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b91bd)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/namei.c (ffffffff813d11f1)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813f0de9)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
</ul>

## Differences
