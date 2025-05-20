# Function: <code>smk_of_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8135e72d)
Location: security/smack/smack.h:358
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8139487d)
Location: security/smack/smack.h:358
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ab3bd)
Location: security/smack/smack.h:367
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c42d3)
Location: security/smack/smack.h:447
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ea233)
Location: security/smack/smack.h:447
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814188b5)
Location: security/smack/smack.h:371
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81434f05)
Location: security/smack/smack.h:404
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81462805)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147c5b5)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d1fb5)
Location: security/smack/smack.h:385
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814ef495)
Location: security/smack/smack.h:378
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f6515)
Location: security/smack/smack.h:384
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815510a5)
Location: security/smack/smack.h:384
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815edacd)
Location: security/smack/smack.h:384
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169dc8d)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d68f5)
Location: security/smack/smack.h:376
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81713278)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getlsmblob
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056d37c)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0720aec)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d1c10)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c1bec)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81474b95)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814655b5)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81470c35)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814884f5)
Location: security/smack/smack.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
```
</details>
</li>
</ul>

## Differences
