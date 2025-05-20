# Function: <code>ext4_handle_dirty_dirblock</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ab7d0)
Location: fs/ext4/namei.c:399
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
ffffffff813ab7d0-ffffffff813ab8cf: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c4700)
Location: fs/ext4/namei.c:399
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
ffffffff813c4700-ffffffff813c47ff: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81410e70)
Location: fs/ext4/namei.c:406
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81410e70-ffffffff81410f6d: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81424330)
Location: fs/ext4/namei.c:402
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81424330-ffffffff8142442d: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142ad40)
Location: fs/ext4/namei.c:404
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8142ad40-ffffffff8142ae3d: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147ed30)
Location: fs/ext4/namei.c:405
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8147ed30-ffffffff8147ee2d: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81501be0)
Location: fs/ext4/namei.c:428
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81501be0-ffffffff81501d07: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159c790)
Location: fs/ext4/namei.c:433
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8159c790-ffffffff8159c8b7: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d2fc0)
Location: fs/ext4/namei.c:433
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff815d2fc0-ffffffff815d30e7: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160b760)
Location: fs/ext4/namei.c:434
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8160b760-ffffffff8160b896: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049c248)
Location: fs/ext4/namei.c:399
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
ffff80001049c248-ffff80001049c368: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065df70)
Location: fs/ext4/namei.c:399
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
c065df70-c065e0a4: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c7150)
Location: fs/ext4/namei.c:399
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
c0000000005c7150-c0000000005c72d8: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00031f414)
Location: fs/ext4/namei.c:399
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
ffffffe00031f414-ffffffe00031f4ec: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bcce0)
Location: fs/ext4/namei.c:399
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
ffffffff813bcce0-ffffffff813bcddf: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ad770)
Location: fs/ext4/namei.c:399
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
ffffffff813ad770-ffffffff813ad86f: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ba6c0)
Location: fs/ext4/namei.c:399
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
ffffffff813ba6c0-ffffffff813ba7bf: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813cf260)
Location: fs/ext4/namei.c:399
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
ffffffff813cf260-ffffffff813cf35f: ext4_handle_dirty_dirblock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
