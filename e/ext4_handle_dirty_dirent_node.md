# Function: <code>ext4_handle_dirty_dirent_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_handle_dirty_dirent_node(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a2b50)
Location: fs/ext4/namei.c:381
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff812a2b50-ffffffff812a2cd5: ext4_handle_dirty_dirent_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_handle_dirty_dirent_node(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d1a90)
Location: fs/ext4/namei.c:381
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff812d1a90-ffffffff812d1c1c: ext4_handle_dirty_dirent_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_handle_dirty_dirent_node(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e7810)
Location: fs/ext4/namei.c:381
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff812e7810-ffffffff812e7995: ext4_handle_dirty_dirent_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_handle_dirty_dirent_node(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81317190)
Location: fs/ext4/namei.c:381
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81317190-ffffffff81317291: ext4_handle_dirty_dirent_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_handle_dirty_dirent_node(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133ba00)
Location: fs/ext4/namei.c:382
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8133ba00-ffffffff8133bb01: ext4_handle_dirty_dirent_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_handle_dirty_dirent_node(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136a0d0)
Location: fs/ext4/namei.c:383
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8136a0d0-ffffffff8136a1d6: ext4_handle_dirty_dirent_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_handle_dirty_dirent_node(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81382590)
Location: fs/ext4/namei.c:384
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81382590-ffffffff81382696: ext4_handle_dirty_dirent_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
</ul>
