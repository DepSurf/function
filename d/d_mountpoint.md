# Function: <code>d_mountpoint</code>

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
In fs/namei.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:402
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
In fs/namei.c (ffffffff8123d5e5)
Location: include/linux/dcache.h:376
Inline: True
Inline callers:
  - fs/namei.c:follow_mount
```
```
In fs/dcache.c (ffffffff8124a3e5)
Location: include/linux/dcache.h:376
Inline: True
Inline callers:
  - fs/dcache.c:check_mount
```
```
In fs/namespace.c (ffffffff81258a5c)
Location: include/linux/dcache.h:376
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:376
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:376
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
In fs/namei.c (ffffffff81250385)
Location: include/linux/dcache.h:376
Inline: True
Inline callers:
  - fs/namei.c:follow_mount
```
```
In fs/dcache.c (0)
Location: include/linux/dcache.h:376
Inline: True
```
```
In fs/namespace.c (ffffffff8126bf0c)
Location: include/linux/dcache.h:376
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:376
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:376
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
In fs/namei.c (ffffffff8125c2d5)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/namei.c:follow_mount
```
```
In fs/dcache.c (ffffffff8126d150)
Location: include/linux/dcache.h:382
Inline: True
```
```
In fs/namespace.c (ffffffff81279811)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:382
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:382
Inline: True
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
In fs/namei.c (ffffffff8127e739)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/namei.c:follow_mount
```
```
In fs/dcache.c (ffffffff8128f4f0)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/dcache.c:d_invalidate
```
```
In fs/namespace.c (ffffffff8129c245)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:383
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:383
Inline: True
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
In fs/namei.c (ffffffff812ab439)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_mount
```
```
In fs/dcache.c (ffffffff812b42a5)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff812c276f)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffffffff813c6b80)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff813d100a)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
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
In fs/namei.c (ffffffff812be049)
Location: include/linux/dcache.h:381
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812c9565)
Location: include/linux/dcache.h:381
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff812d7a0f)
Location: include/linux/dcache.h:381
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffffffff813dfd4d)
Location: include/linux/dcache.h:381
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff813eb6cf)
Location: include/linux/dcache.h:381
Inline: True
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
In fs/namei.c (ffffffff812dac56)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812e5dd5)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff812f5eef)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffffffff8140b958)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff8141779f)
Location: include/linux/dcache.h:379
Inline: True
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
In fs/namei.c (ffffffff812ec766)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812f78d5)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff81307a6f)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffffffff81425407)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff8143165f)
Location: include/linux/dcache.h:379
Inline: True
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
In fs/namei.c (ffffffff8132668a)
Location: include/linux/dcache.h:381
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff81330505)
Location: include/linux/dcache.h:381
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff81340f4f)
Location: include/linux/dcache.h:381
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
```
```
In fs/fuse/dir.c (ffffffff81474b33)
Location: include/linux/dcache.h:381
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff8148177a)
Location: include/linux/dcache.h:381
Inline: True
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
In fs/namei.c (ffffffff81331b2b)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff8133be95)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff8134d03f)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
```
```
In fs/fuse/dir.c (ffffffff8148f4fe)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff8149e82a)
Location: include/linux/dcache.h:382
Inline: True
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
In fs/namei.c (ffffffff81335bc4)
Location: include/linux/dcache.h:385
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff81342325)
Location: include/linux/dcache.h:385
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff81353c1f)
Location: include/linux/dcache.h:385
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
```
```
In fs/fuse/dir.c (ffffffff81494f1e)
Location: include/linux/dcache.h:385
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff814a47f9)
Location: include/linux/dcache.h:385
Inline: True
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
In fs/namei.c (ffffffff813836e4)
Location: include/linux/dcache.h:385
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff8138fce5)
Location: include/linux/dcache.h:385
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff813a206f)
Location: include/linux/dcache.h:385
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
```
```
In fs/fuse/dir.c (ffffffff814ec9ae)
Location: include/linux/dcache.h:385
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff814fc969)
Location: include/linux/dcache.h:385
Inline: True
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
In fs/namei.c (ffffffff8140422c)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff81410f95)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff81425b41)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
```
```
In fs/fuse/dir.c (ffffffff8157b70a)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff8158d119)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
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
In fs/namei.c (ffffffff8148e6ac)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff8149bce5)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff814b2341)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
```
```
In fs/fuse/dir.c (ffffffff8162104a)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff81633c19)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
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
In fs/namei.c (ffffffff814c3d3e)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff814d0f25)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff814e7391)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
```
```
In fs/fuse/dir.c (ffffffff8165949a)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff8166bf19)
Location: include/linux/dcache.h:375
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
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
In fs/namei.c (ffffffff814f6267)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff81503865)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff8151b221)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
```
```
In fs/fuse/dir.c (ffffffff8169318a)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff816a63b9)
Location: include/linux/dcache.h:382
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
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
In fs/namei.c (ffff800010395f84)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffff8000103a4f5c)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffff8000103baf20)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffff800010508b10)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffff800010516380)
Location: include/linux/dcache.h:379
Inline: True
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
In fs/namei.c (c057b438)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
```
```
In fs/dcache.c (c0586cf4)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (c0598cd0)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (c06c4ae4)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (c06d12f0)
Location: include/linux/dcache.h:379
Inline: True
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
In fs/namei.c (c00000000048e2a8)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (c00000000049ea88)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (c0000000004b8894)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (c00000000064e5c0)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (c00000000065f244)
Location: include/linux/dcache.h:379
Inline: True
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
In fs/namei.c (ffffffe0002645b0)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffe00026bb06)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffe00027cffa)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffffffe0003746e8)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffe00037faa4)
Location: include/linux/dcache.h:379
Inline: True
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
In fs/namei.c (ffffffff812e4d46)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812efeb5)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff8130004f)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffffffff8141d9e7)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff81429c3f)
Location: include/linux/dcache.h:379
Inline: True
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
In fs/namei.c (ffffffff812d5986)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812e0ae5)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff812f0c6f)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffffffff8140e467)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff8141a6bf)
Location: include/linux/dcache.h:379
Inline: True
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
In fs/namei.c (ffffffff812e2b56)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812edcc5)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff812fde3f)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffffffff81419b87)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff81425ddf)
Location: include/linux/dcache.h:379
Inline: True
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
In fs/namei.c (ffffffff812f2a96)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812fecb5)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_check_mount
```
```
In fs/namespace.c (ffffffff8130f17f)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:__is_local_mountpoint
```
```
In fs/fuse/dir.c (ffffffff814308f7)
Location: include/linux/dcache.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/debugfs/inode.c (ffffffff8143ce2f)
Location: include/linux/dcache.h:379
Inline: True
```
</details>
</li>
</ul>

## Differences
