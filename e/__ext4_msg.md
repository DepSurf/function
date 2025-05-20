# Function: <code>__ext4_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7e90)
Location: fs/ext4/super.c:605
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
```
**Symbols:**

```
ffffffff812b7e90-ffffffff812b7f4c: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e6b90)
Location: fs/ext4/super.c:634
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff812e6b90-ffffffff812e6c4c: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fc740)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff812fc740-ffffffff812fc7fc: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81331380)
Location: fs/ext4/super.c:657
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff81331380-ffffffff81331443: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81355840)
Location: fs/ext4/super.c:656
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff81355840-ffffffff81355903: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:662
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff8138b85c-ffffffff8138b8a3: __ext4_msg.cold.133 (STB_LOCAL)
ffffffff81383c60-ffffffff81383cdc: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:704
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff813a43bc-ffffffff813a4403: __ext4_msg.cold.137 (STB_LOCAL)
ffffffff8139c740-ffffffff8139c7bc: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:715
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_clamp_want_extra_isize
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff813ce5dd-ffffffff813ce624: __ext4_msg.cold (STB_LOCAL)
ffffffff813c69a0-ffffffff813c6a1c: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:710
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff813e7c9c-ffffffff813e7ce3: __ext4_msg.cold (STB_LOCAL)
ffffffff813dfd60-ffffffff813dfddc: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
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
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff8143475c-ffffffff814347a3: __ext4_msg.cold (STB_LOCAL)
ffffffff8142c620-ffffffff8142c69a: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:893
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff81bec5ef-ffffffff81bec636: __ext4_msg.cold (STB_LOCAL)
ffffffff81445440-ffffffff814454c8: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:902
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff81bde6a1-ffffffff81bde6e8: __ext4_msg.cold (STB_LOCAL)
ffffffff8144ad60-ffffffff8144ade8: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:901
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_process_orphan
```
**Symbols:**

```
ffffffff81ccd710-ffffffff81ccd757: __ext4_msg.cold (STB_LOCAL)
ffffffff8149ec70-ffffffff8149ecf8: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:927
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_apply_options
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_process_orphan
```
**Symbols:**

```
ffffffff81e8053f-ffffffff81e805c3: __ext4_msg.cold (STB_LOCAL)
ffffffff815253b0-ffffffff81525484: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c2990)
Location: fs/ext4/super.c:920
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_geometry_check
  - fs/ext4/super.c:ext4_geometry_check
  - fs/ext4/super.c:ext4_geometry_check
  - fs/ext4/super.c:ext4_geometry_check
  - fs/ext4/super.c:ext4_geometry_check
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_apply_options
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_process_orphan
```
**Symbols:**

```
ffffffff815c2990-ffffffff815c2adb: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fa0f0)
Location: fs/ext4/super.c:920
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_journal_bmap
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_apply_options
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_percpu_param_init
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_process_orphan
```
**Symbols:**

```
ffffffff815fa0f0-ffffffff815fa23b: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81632cf0)
Location: fs/ext4/super.c:989
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_journal_bmap
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_apply_options
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:parse_apply_sb_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_percpu_param_init
  - fs/ext4/super.c:update_super_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_process_orphan
```
**Symbols:**

```
ffffffff81632cf0-ffffffff81632e3b: __ext4_msg (STB_GLOBAL)
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
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b8d70)
Location: fs/ext4/super.c:710
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffff8000104b8d70-ffff8000104b8e2c: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067c3c0)
Location: fs/ext4/super.c:710
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
c067c3c0-c067c46c: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ede20)
Location: fs/ext4/super.c:710
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
c0000000005ede20-c0000000005edf00: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe0003356f0)
Location: fs/ext4/super.c:710
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffe0003356f0-ffffffe000335774: __ext4_msg (STB_GLOBAL)
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
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:710
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff813e027c-ffffffff813e02c3: __ext4_msg.cold (STB_LOCAL)
ffffffff813d8340-ffffffff813d83bc: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:710
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff813d0cfc-ffffffff813d0d43: __ext4_msg.cold (STB_LOCAL)
ffffffff813c8dc0-ffffffff813c8e3c: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:710
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_feature_set_ok
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff813dd5fc-ffffffff813dd643: __ext4_msg.cold (STB_LOCAL)
ffffffff813d57d0-ffffffff813d584c: __ext4_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ext4_msg(struct super_block *sb, const char *prefix, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:710
Inline: False
Direct callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
```
**Symbols:**

```
ffffffff813f2a2c-ffffffff813f2a73: __ext4_msg.cold (STB_LOCAL)
ffffffff813eaa50-ffffffff813eaacc: __ext4_msg (STB_GLOBAL)
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
