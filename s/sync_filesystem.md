# Function: <code>sync_filesystem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81240700)
Location: fs/sync.c:47
Inline: True
Direct callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:freeze_super
  - fs/sync.c:SyS_syncfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_remount
  - fs/devpts/inode.c:devpts_remount
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff81240700-ffffffff8124079b: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81268a40)
Location: fs/sync.c:47
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:SyS_syncfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_remount
  - fs/devpts/inode.c:devpts_remount
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_remount
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff81268a40-ffffffff81268add: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8127ba60)
Location: fs/sync.c:48
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:SyS_syncfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_remount
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_remount
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff8127ba60-ffffffff8127bab2: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81288df0)
Location: fs/sync.c:48
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:SyS_syncfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_remount
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_remount
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff81288df0-ffffffff81288e2f: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812ab930)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:SyS_syncfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_remount
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_remount
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff812ab930-ffffffff812ab970: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812d25f0)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_remount
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_remount
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff812d25f0-ffffffff812d2630: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812e79d0)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_remount
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_remount
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff812e79d0-ffffffff812e7a10: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sync.c (ffffffff813062b7)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_remount
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff81306710-ffffffff81306723: sync_filesystem.cold (STB_LOCAL)
ffffffff81306280-ffffffff813062c8: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81319300)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff81319300-ffffffff81319348: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813530c0)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fat/inode.c:fat_remount
  - fs/fuse/inode.c:fuse_reconfigure
  - fs/debugfs/inode.c:debugfs_remount
  - fs/tracefs/inode.c:tracefs_remount
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff813530c0-ffffffff8135315a: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8135f9a0)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fat/inode.c:fat_remount
  - fs/fuse/inode.c:fuse_reconfigure
  - fs/debugfs/inode.c:debugfs_remount
  - fs/tracefs/inode.c:tracefs_remount
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff8135f9a0-ffffffff8135fa3a: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813661d0)
Location: fs/sync.c:48
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fat/inode.c:fat_remount
  - fs/fuse/inode.c:fuse_reconfigure
  - fs/debugfs/inode.c:debugfs_remount
  - fs/tracefs/inode.c:tracefs_remount
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff813661d0-ffffffff8136626a: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813b5003)
Location: fs/sync.c:49
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fat/inode.c:fat_remount
  - fs/fuse/inode.c:fuse_reconfigure
  - fs/debugfs/inode.c:debugfs_remount
  - fs/tracefs/inode.c:tracefs_remount
  - fs/pstore/inode.c:pstore_remount
  - block/bdev.c:fsync_bdev
```
**Symbols:**

```
ffffffff813b4d80-ffffffff813b4e1a: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81439ea0)
Location: fs/sync.c:30
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:__ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fat/inode.c:fat_remount
  - fs/fuse/inode.c:fuse_reconfigure
  - fs/debugfs/inode.c:debugfs_remount
  - fs/tracefs/inode.c:tracefs_remount
  - fs/pstore/inode.c:pstore_remount
  - block/bdev.c:fsync_bdev
```
**Symbols:**

```
ffffffff81439ea0-ffffffff81439f4f: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814c8240)
Location: fs/sync.c:30
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:__ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fat/inode.c:fat_remount
  - fs/fuse/inode.c:fuse_reconfigure
  - fs/debugfs/inode.c:debugfs_remount
  - fs/tracefs/inode.c:tracefs_remount
  - fs/pstore/inode.c:pstore_remount
  - block/bdev.c:fsync_bdev
```
**Symbols:**

```
ffffffff814c8240-ffffffff814c82ef: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814fe470)
Location: fs/sync.c:30
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:__ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fat/inode.c:fat_remount
  - fs/fuse/inode.c:fuse_reconfigure
  - fs/debugfs/inode.c:debugfs_remount
  - fs/tracefs/inode.c:tracefs_remount
  - fs/pstore/inode.c:pstore_remount
  - block/bdev.c:fsync_bdev
```
**Symbols:**

```
ffffffff814fe470-ffffffff814fe51f: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81533070)
Location: fs/sync.c:30
Inline: True
Direct callers:
  - fs/super.c:fs_bdev_sync
  - fs/super.c:fs_bdev_mark_dead
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:__ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fat/inode.c:fat_remount
  - fs/fuse/inode.c:fuse_reconfigure
  - fs/debugfs/inode.c:debugfs_remount
  - fs/tracefs/inode.c:tracefs_remount
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff81533070-ffffffff8153311f: sync_filesystem (STB_GLOBAL)
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
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffff8000103d0320)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__arm64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffff8000103d0320-ffff8000103d0388: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (c05ab620)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__se_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
c05ab620-c05ab690: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (c0000000004d29c0)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__se_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
c0000000004d29c0-c0000000004d2a54: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffe00028c584)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__se_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffe00028c584-ffffffe00028c5da: sync_filesystem (STB_GLOBAL)
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
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813118e0)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff813118e0-ffffffff81311928: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813024f0)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff813024f0-ffffffff81302538: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8130f6d0)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff8130f6d0-ffffffff8130f718: sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sync_filesystem(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81320ed0)
Location: fs/sync.c:49
Inline: True
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:generic_shutdown_super
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/block_dev.c:fsync_bdev
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/root.c:proc_reconfigure
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/squashfs/super.c:squashfs_reconfigure
  - fs/fuse/inode.c:fuse_remount_fs
  - fs/pstore/inode.c:pstore_remount
```
**Symbols:**

```
ffffffff81320ed0-ffffffff81320f18: sync_filesystem (STB_GLOBAL)
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
