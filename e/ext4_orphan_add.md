# Function: <code>ext4_orphan_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a7120)
Location: fs/ext4/namei.c:2747
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/indirect.c:ext4_ind_direct_IO
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
**Symbols:**

```
ffffffff812a7120-ffffffff812a73a5: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d61c0)
Location: fs/ext4/namei.c:2770
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff812d61c0-ffffffff812d641e: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812ebec0)
Location: fs/ext4/namei.c:2772
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff812ebec0-ffffffff812ec11e: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8131bbb0)
Location: fs/ext4/namei.c:2751
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff8131bbb0-ffffffff8131bde1: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813401e0)
Location: fs/ext4/namei.c:2746
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff813401e0-ffffffff81340411: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136e1b0)
Location: fs/ext4/namei.c:2746
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff8136e1b0-ffffffff8136e3ec: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81386630)
Location: fs/ext4/namei.c:2747
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff81386630-ffffffff8138687e: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b0600)
Location: fs/ext4/namei.c:2891
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff813b0600-ffffffff813b085c: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c9630)
Location: fs/ext4/namei.c:2903
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813c9630-ffffffff813c988c: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81414fa0)
Location: fs/ext4/namei.c:2939
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81414fa0-ffffffff814151fc: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:2931
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81bec4e9-ffffffff81bec511: ext4_orphan_add.cold (STB_LOCAL)
ffffffff814285f0-ffffffff814288ad: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3061
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81bde59b-ffffffff81bde5c3: ext4_orphan_add.cold (STB_LOCAL)
ffffffff8142f0f0-ffffffff8142f3ad: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/orphan.c (0)
Location: fs/ext4/orphan.c:99
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81cce2e4-ffffffff81cce30c: ext4_orphan_add.cold (STB_LOCAL)
ffffffff814b1210-ffffffff814b1505: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/orphan.c (0)
Location: fs/ext4/orphan.c:99
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81e81307-ffffffff81e8132f: ext4_orphan_add.cold (STB_LOCAL)
ffffffff81539d00-ffffffff8153a025: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff815d8240)
Location: fs/ext4/orphan.c:99
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff815d8240-ffffffff815d8588: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff8160fdd0)
Location: fs/ext4/orphan.c:99
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff8160fdd0-ffffffff81610117: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff81648b90)
Location: fs/ext4/orphan.c:99
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81648b90-ffffffff81648ed7: ext4_orphan_add (STB_GLOBAL)
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
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff8000104a1200)
Location: fs/ext4/namei.c:2903
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffff8000104a1200-ffff8000104a1448: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c066338c)
Location: fs/ext4/namei.c:2903
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
c066338c-c06635d8: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005cdac0)
Location: fs/ext4/namei.c:2903
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
c0000000005cdac0-c0000000005cde04: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000323280)
Location: fs/ext4/namei.c:2903
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffe000323280-ffffffe000323444: ext4_orphan_add (STB_GLOBAL)
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
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c1c10)
Location: fs/ext4/namei.c:2903
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813c1c10-ffffffff813c1e6c: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b26a0)
Location: fs/ext4/namei.c:2903
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813b26a0-ffffffff813b28fc: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bf0c0)
Location: fs/ext4/namei.c:2903
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813bf0c0-ffffffff813bf31c: ext4_orphan_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d41a0)
Location: fs/ext4/namei.c:2903
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813d41a0-ffffffff813d43fc: ext4_orphan_add (STB_GLOBAL)
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
