# Function: <code>ext4_reserve_inode_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129b770)
Location: fs/ext4/inode.c:5038
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff8129b770-ffffffff8129b802: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c91a0)
Location: fs/ext4/inode.c:5379
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff812c91a0-ffffffff812c9234: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dede0)
Location: fs/ext4/inode.c:5523
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff812dede0-ffffffff812dee74: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81302e40)
Location: fs/ext4/inode.c:5686
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff81302e40-ffffffff81302ef0: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81327830)
Location: fs/ext4/inode.c:5739
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff81327830-ffffffff813278e0: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813554d0)
Location: fs/ext4/inode.c:5835
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff813554d0-ffffffff8135558b: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136d800)
Location: fs/ext4/inode.c:5888
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff8136d800-ffffffff8136d8bb: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81396e10)
Location: fs/ext4/inode.c:5910
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff81396e10-ffffffff81396ecd: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813af840)
Location: fs/ext4/inode.c:5924
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813af840-ffffffff813af8fd: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fb880)
Location: fs/ext4/inode.c:5645
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813fb880-ffffffff813fb93d: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140e000)
Location: fs/ext4/inode.c:5738
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff8140e000-ffffffff8140e0ac: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814141c0)
Location: fs/ext4/inode.c:5735
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff814141c0-ffffffff8141426c: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81467520)
Location: fs/ext4/inode.c:5674
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff81467520-ffffffff814675d6: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e7140)
Location: fs/ext4/inode.c:5752
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff814e7140-ffffffff814e721a: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81580ae0)
Location: fs/ext4/inode.c:5888
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff81580ae0-ffffffff81580bba: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b8090)
Location: fs/ext4/inode.c:5700
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff815b8090-ffffffff815b816a: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f0e30)
Location: fs/ext4/inode.c:5720
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff815f0e30-ffffffff815f0f0a: ext4_reserve_inode_write (STB_GLOBAL)
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
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff8000104842a0)
Location: fs/ext4/inode.c:5924
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffff8000104842a0-ffff800010484390: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c06458d8)
Location: fs/ext4/inode.c:5924
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
c06458d8-c0645990: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a9440)
Location: fs/ext4/inode.c:5924
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
c0000000005a9440-c0000000005a9564: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030c788)
Location: fs/ext4/inode.c:5924
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffe00030c788-ffffffe00030c83e: ext4_reserve_inode_write (STB_GLOBAL)
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
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a7e20)
Location: fs/ext4/inode.c:5924
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813a7e20-ffffffff813a7edd: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813988b0)
Location: fs/ext4/inode.c:5924
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813988b0-ffffffff8139896d: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5680)
Location: fs/ext4/inode.c:5924
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813a5680-ffffffff813a573d: ext4_reserve_inode_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b9dc0)
Location: fs/ext4/inode.c:5924
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813b9dc0-ffffffff813b9e7d: ext4_reserve_inode_write (STB_GLOBAL)
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
