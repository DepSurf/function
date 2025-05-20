# Function: <code>fuse_invalidate_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81311afb)
Location: fs/fuse/dir.c:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_follow_link
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_setattr
Direct callers:
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81312d80-ffffffff81312d96: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81346acb)
Location: fs/fuse/dir.c:112
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
Direct callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81347300-ffffffff81347316: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135eaee)
Location: fs/fuse/dir.c:104
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
Direct callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8135cc10-ffffffff8135cc26: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8137362c)
Location: fs/fuse/dir.c:104
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
Direct callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81371600-ffffffff81371616: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8139833c)
Location: fs/fuse/dir.c:104
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
Direct callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81396300-ffffffff81396316: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c7472)
Location: fs/fuse/dir.c:104
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
Direct callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813c6480-ffffffff813c6496: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813de205)
Location: fs/fuse/dir.c:93
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813df640-ffffffff813df66a: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140a14a)
Location: fs/fuse/dir.c:93
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8140b270-ffffffff8140b29a: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142380e)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81423c00-ffffffff81423c2a: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814740fe)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff814730d0-ffffffff814730fa: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148ea51)
Location: fs/fuse/dir.c:128
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff8148daa0-ffffffff8148daca: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81495a3f)
Location: fs/fuse/dir.c:128
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81493340-ffffffff8149336a: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ed4ef)
Location: fs/fuse/dir.c:128
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff814ea7a0-ffffffff814ea7ca: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157c2f5)
Location: fs/fuse/dir.c:131
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81579260-ffffffff81579298: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81621d05)
Location: fs/fuse/dir.c:137
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8161e8b0-ffffffff8161e8dc: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8165a15e)
Location: fs/fuse/dir.c:137
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81656ce0-ffffffff81656d12: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81693df2)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81690930-ffffffff81690962: fuse_invalidate_attr (STB_GLOBAL)
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
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010506fd4)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffff800010507320-ffff800010507380: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c568c)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
c06c32b4-c06c32d4: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064d9cc)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
c00000000064c860-c00000000064c8d4: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe000375100)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffe000373298-ffffffe0003732de: fuse_invalidate_attr (STB_GLOBAL)
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
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141bdee)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8141c1e0-ffffffff8141c20a: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140c86e)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8140cc60-ffffffff8140cc8a: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81417f8e)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81418380-ffffffff814183aa: fuse_invalidate_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_attr(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142ed0e)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
Direct callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8142f100-ffffffff8142f12a: fuse_invalidate_attr (STB_GLOBAL)
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
