# Function: <code>__ext4_warning_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ba530)
Location: fs/ext4/super.c:642
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff812ba530-ffffffff812ba617: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e9460)
Location: fs/ext4/super.c:671
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff812e9460-ffffffff812e9547: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ff1d0)
Location: fs/ext4/super.c:674
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff812ff1d0-ffffffff812ff2b7: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81333fa0)
Location: fs/ext4/super.c:694
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff81333fa0-ffffffff8133408d: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813584b0)
Location: fs/ext4/super.c:693
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813584b0-ffffffff8135859d: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:699
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff8138bc1b-ffffffff8138bc7f: __ext4_warning_inode.cold.142 (STB_LOCAL)
ffffffff81386e10-ffffffff81386e9d: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:741
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813a479a-ffffffff813a47fe: __ext4_warning_inode.cold.146 (STB_LOCAL)
ffffffff8139f920-ffffffff8139f9ad: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:752
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813ce978-ffffffff813ce9dc: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff813c9c40-ffffffff813c9ccd: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:747
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813e8037-ffffffff813e809b: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff813e2f40-ffffffff813e2fcd: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:778
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_dx_csum_verify
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81434be0-ffffffff81434c44: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff814304f0-ffffffff8143057b: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:934
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_dx_csum_verify
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81bec9da-ffffffff81beca3e: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff81449230-ffffffff814492c9: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:943
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81bdea8a-ffffffff81bdeaee: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff8144ebb0-ffffffff8144ec49: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:942
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81ccdc09-ffffffff81ccdc6d: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff814a26f0-ffffffff814a2789: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:974
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81e80b59-ffffffff81e80bbd: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff81529a30-ffffffff81529b10: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c8240)
Location: fs/ext4/super.c:967
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff815c8240-ffffffff815c837b: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81600050)
Location: fs/ext4/super.c:967
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81600050-ffffffff8160018b: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81638da0)
Location: fs/ext4/super.c:1036
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dx_node
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81638da0-ffffffff81638edb: __ext4_warning_inode (STB_GLOBAL)
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
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bc2f0)
Location: fs/ext4/super.c:747
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffff8000104bc2f0-ffff8000104bc3cc: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067f9ac)
Location: fs/ext4/super.c:747
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
c067f9ac-c067fa8c: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f2050)
Location: fs/ext4/super.c:747
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
c0000000005f2050-c0000000005f2150: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe00033816e)
Location: fs/ext4/super.c:747
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffe00033816e-ffffffe0003381fe: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:747
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813e0617-ffffffff813e067b: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff813db520-ffffffff813db5ad: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:747
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813d1097-ffffffff813d10fb: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff813cbfa0-ffffffff813cc02d: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:747
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813dd997-ffffffff813dd9fb: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff813d89c0-ffffffff813d8a4d: __ext4_warning_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ext4_warning_inode(const struct inode *inode, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:747
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813f2dc3-ffffffff813f2e27: __ext4_warning_inode.cold (STB_LOCAL)
ffffffff813edc60-ffffffff813edced: __ext4_warning_inode (STB_GLOBAL)
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
