# Function: <code>d_is_miss</code>

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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:415
Inline: True
```
```
In fs/namei.c (ffffffff8121766a)
Location: include/linux/dcache.h:415
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
```
```
In security/security.c (0)
Location: include/linux/dcache.h:415
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/dcache.h:415
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:415
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:415
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8137a0d4)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:389
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813907f4)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:389
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:395
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/dcache.h:395
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/dcache.h:395
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:395
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813a6c5a)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:395
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:395
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:396
Inline: True
```
```
In fs/namei.c (ffffffff8128016e)
Location: include/linux/dcache.h:396
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/dcache.h:396
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:396
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813cc6aa)
Location: include/linux/dcache.h:396
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:396
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:396
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
In kernel/audit_watch.c (ffffffff81159144)
Location: include/linux/dcache.h:397
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812ac9cd)
Location: include/linux/dcache.h:397
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/crypto/crypto.c (ffffffff812fa006)
Location: include/linux/dcache.h:397
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_d_revalidate
```
```
In security/security.c (ffffffff813f4983)
Location: include/linux/dcache.h:397
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff814007e0)
Location: include/linux/dcache.h:397
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff8141b759)
Location: include/linux/dcache.h:397
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff814370eb)
Location: include/linux/dcache.h:397
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In kernel/audit_watch.c (ffffffff811660e4)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812c1acd)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812ca70f)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/crypto/crypto.c (ffffffff8130f2e6)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_d_revalidate
```
```
In security/security.c (ffffffff8140fd53)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8141c89e)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81437da1)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81453d4b)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In kernel/audit_watch.c (ffffffff81172c17)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812de03c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812e7022)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (ffffffff813721aa)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81374eb8)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff814175e8)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81419de5)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (ffffffff8143d3b8)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8144a294)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81465a0d)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81481619)
Location: include/linux/dcache.h:392
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
In kernel/audit_watch.c (ffffffff8117eab3)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812efb5c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812f8b92)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (ffffffff8138a7ba)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8138d138)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff814314a8)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81433c35)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (ffffffff81456e58)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff81463fac)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff8147f8bd)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff8149b349)
Location: include/linux/dcache.h:392
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
In kernel/audit_watch.c (ffffffff8119203c)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff81327e0d)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:atomic_open
  - fs/namei.c:may_delete
```
```
In fs/dcache.c (ffffffff81331cc2)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:394
Inline: True
```
```
In fs/configfs/dir.c (ffffffff813d5b6d)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813d85ab)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In security/security.c (ffffffff814a9c68)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff814b803f)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff814d4c7d)
Location: include/linux/dcache.h:394
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff814f3d98)
Location: include/linux/dcache.h:394
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
In kernel/audit_watch.c (ffffffff8118f1cc)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff81334904)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:atomic_open
  - fs/namei.c:may_delete
```
```
In fs/dcache.c (ffffffff8133d6e2)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:395
Inline: True
```
```
In fs/configfs/dir.c (ffffffff813e785d)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813ea228)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In security/security.c (ffffffff814c7268)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff814d5d4f)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff814f227d)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81510ef8)
Location: include/linux/dcache.h:395
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
In kernel/audit_watch.c (ffffffff8118fff9)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff8133aa3e)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:may_delete
```
```
In fs/dcache.c (ffffffff81343b62)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:398
Inline: True
```
```
In fs/configfs/dir.c (ffffffff813ee22d)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813f0d68)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In security/security.c (ffffffff814cd6a8)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff814dcbb2)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff814f929d)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81517878)
Location: include/linux/dcache.h:398
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff815371d5)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff81538961)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
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
In kernel/audit_watch.c (ffffffff811b8ed9)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff81388648)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:may_delete
```
```
In fs/dcache.c (ffffffff81391b07)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:398
Inline: True
```
```
In fs/configfs/dir.c (ffffffff8143fa56)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81442c74)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In security/security.c (ffffffff815265f8)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff81536082)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff81553e8d)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81575878)
Location: include/linux/dcache.h:398
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff815957f5)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff815970c1)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
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
In kernel/audit_watch.c (ffffffff811ebf0a)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff81409656)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:may_delete
```
```
In fs/dcache.c (ffffffff81411ba2)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:388
Inline: True
```
```
In fs/configfs/dir.c (ffffffff814bbfbb)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff814bea30)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In security/security.c (ffffffff815bae88)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff815cc4f9)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff815edd2d)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81613358)
Location: include/linux/dcache.h:388
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff81637a99)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff8163b1af)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
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
In kernel/audit_watch.c (ffffffff8123236a)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff81493d06)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:may_delete
```
```
In fs/dcache.c (ffffffff8149c5c2)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:388
Inline: True
```
```
In fs/configfs/dir.c (ffffffff81553ae6)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff815568f0)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In security/security.c (ffffffff81666938)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff81679719)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff8169e1cd)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff816c5fa8)
Location: include/linux/dcache.h:388
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff816eee69)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff816f29a7)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
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
In kernel/audit_watch.c (ffffffff81248ffa)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff814c8d74)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:may_delete
```
```
In fs/dcache.c (ffffffff814d1912)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:388
Inline: True
```
```
In fs/configfs/dir.c (ffffffff8158b876)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8158e6b0)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In security/security.c (ffffffff8169ef28)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff816b18ab)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff816d6b6d)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff816fed88)
Location: include/linux/dcache.h:388
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff817292fe)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff8172ce04)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
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
In kernel/audit_watch.c (ffffffff81262e8a)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff814fb633)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:may_delete
```
```
In fs/dcache.c (ffffffff8150422e)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:395
Inline: True
```
```
In fs/configfs/dir.c (ffffffff815c45ac)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff815c73c3)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In security/security.c (ffffffff816db878)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff816ee93e)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff8171341d)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff8173c318)
Location: include/linux/dcache.h:395
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff8176a6ca)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - security/landlock/syscalls.c:add_rule_path_beneath
```
```
In security/landlock/fs.c (ffffffff8176dbd5)
Location: include/linux/dcache.h:395
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:find_rule
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
In kernel/audit_watch.c (ffff8000101f39dc)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffff8000103992c0)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffff8000103a6c30)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (ffff80001045ade0)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffff80001045ee50)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffff8000105161dc)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (ffff8000105196dc)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (ffff8000105428d0)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffff80001055203c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffff800010570c30)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffff80001059161c)
Location: include/linux/dcache.h:392
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
In kernel/audit_watch.c (c0433e4c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (c057f94c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (c05878ec)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (c061c998)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (c061f868)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (c06d0f64)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (c06d3d98)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (c06f8878)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (c070433c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (c07241ac)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (c0742220)
Location: include/linux/dcache.h:392
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
In kernel/audit_watch.c (c000000000268654)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (c000000000493ac0)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (c00000000049f7cc)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (c000000000576838)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (c00000000057b018)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (c00000000065ecd0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (c000000000662ba0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (c000000000695f04)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (c0000000006a887c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (c0000000006d749c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (c00000000070526c)
Location: include/linux/dcache.h:392
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
In kernel/audit_watch.c (ffffffe000166dd0)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffe000266d6c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffe00026d55a)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (ffffffe0002eb6ec)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffe0002ee954)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffe00037f8fa)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (ffffffe000382a18)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (ffffffe00039f122)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffe0003ab06e)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffe0003c38ea)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffe0003def88)
Location: include/linux/dcache.h:392
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
In kernel/audit_watch.c (ffffffff811770d3)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812e813c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812f1172)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (ffffffff81382d9a)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81385718)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff81429a88)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8142c215)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (ffffffff8144f438)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8145c58c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81477e9d)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81493929)
Location: include/linux/dcache.h:392
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
In kernel/audit_watch.c (ffffffff8116a273)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812d8d7c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812e1da2)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (ffffffff8137382a)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813761a8)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff8141a508)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8141cc95)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (ffffffff8143fe88)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8144cfbc)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff814688bd)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81484349)
Location: include/linux/dcache.h:392
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
In kernel/audit_watch.c (ffffffff81174ea3)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812e5f4c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812eef82)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (ffffffff8138086a)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813831e8)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff81425c28)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814283b5)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (ffffffff8144b4d8)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8145862c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81473f3d)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff8148f9c9)
Location: include/linux/dcache.h:392
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
In kernel/audit_watch.c (ffffffff81182783)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812f6ecc)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812ff2e4)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/configfs/dir.c (ffffffff81394326)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81396d08)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff8143cae8)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8143f275)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (ffffffff814628a8)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8146d44c)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff8148b84d)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff814a78d7)
Location: include/linux/dcache.h:392
Inline: True
```
</details>
</li>
</ul>

## Differences
