# Function: <code>__ext4_iget</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136c740)
Location: fs/ext4/inode.c:4821
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff8136c740-ffffffff8136d433: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395d10)
Location: fs/ext4/inode.c:4835
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff81395d10-ffffffff81396a27: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ae700)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813ae700-ffffffff813af45b: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fa750)
Location: fs/ext4/inode.c:4542
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813fa750-ffffffff813fb4cd: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140cdb0)
Location: fs/ext4/inode.c:4600
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_del_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay_unlink
```
**Symbols:**

```
ffffffff8140cdb0-ffffffff8140dbfc: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412f30)
Location: fs/ext4/inode.c:4599
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff81412f30-ffffffff81413db8: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4520
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff81ccae44-ffffffff81ccae8d: __ext4_iget.cold (STB_LOCAL)
ffffffff81466260-ffffffff81467135: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff81e7dce0-ffffffff81e7dd29: __ext4_iget.cold (STB_LOCAL)
ffffffff814e5d50-ffffffff814e6ceb: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff8206e1a9-ffffffff8206e1f8: __ext4_iget.cold (STB_LOCAL)
ffffffff8157f4d0-ffffffff815804e9: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4636
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff820edeed-ffffffff820edf3c: __ext4_iget.cold (STB_LOCAL)
ffffffff815b6980-ffffffff815b7aa6: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4655
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff821cb048-ffffffff821cb097: __ext4_iget.cold (STB_LOCAL)
ffffffff815ef720-ffffffff815f083a: __ext4_iget (STB_GLOBAL)
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
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010483288)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffff800010483288-ffff800010483d7c: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0644578)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
c0644578-c064538c: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a80a0)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
c0000000005a80a0-c0000000005a8e28: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030b998)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffe00030b998-ffffffe00030c35c: __ext4_iget (STB_GLOBAL)
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
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a6ce0)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813a6ce0-ffffffff813a7a3b: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81397770)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff81397770-ffffffff813984cb: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4540)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813a4540-ffffffff813a529b: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *__ext4_iget(struct super_block *sb, long unsigned int ino, ext4_iget_flags flags, const char *function, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b8c40)
Location: fs/ext4/inode.c:4828
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813b8c40-ffffffff813b99df: __ext4_iget (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
