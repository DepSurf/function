# Function: <code>dentry_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120b430)
Location: fs/open.c:861
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_create
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff8120b430-ffffffff8120b4ea: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81231110)
Location: fs/open.c:857
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_create
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff81231110-ffffffff812311ca: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812436c0)
Location: fs/open.c:874
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_create
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff812436c0-ffffffff8124377a: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124ee20)
Location: fs/open.c:874
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff8124ee20-ffffffff8124eeda: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81270da0)
Location: fs/open.c:874
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81270da0-ffffffff81270e5a: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81296a50)
Location: fs/open.c:916
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81296a50-ffffffff81296ae3: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812aa1b0)
Location: fs/open.c:893
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812aa1b0-ffffffff812aa21e: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c6960)
Location: fs/open.c:913
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812c6960-ffffffff812c69d0: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d8370)
Location: fs/open.c:918
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812d8370-ffffffff812d83e0: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130e410)
Location: fs/open.c:946
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_open_file
```
**Symbols:**

```
ffffffff8130e410-ffffffff8130e480: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131a4e0)
Location: fs/open.c:935
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_open_file
```
**Symbols:**

```
ffffffff8131a4e0-ffffffff8131a550: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813205c0)
Location: fs/open.c:943
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:__do_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff813205c0-ffffffff81320630: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136db80)
Location: fs/open.c:961
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:__do_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff8136db80-ffffffff8136dbf0: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ebcc0)
Location: fs/open.c:984
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff813ebcc0-ffffffff813ebd46: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81474150)
Location: fs/open.c:1016
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81474150-ffffffff814741d6: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a8b00)
Location: fs/open.c:1051
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff814a8b00-ffffffff814a8b8c: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d9b60)
Location: fs/open.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff814d9b60-ffffffff814d9bec: dentry_open (STB_GLOBAL)
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
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037df50)
Location: fs/open.c:918
Inline: True
Direct callers:
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffff80001037df50-ffff80001037dfec: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (c0567c90)
Location: fs/open.c:918
Inline: True
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__se_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:__se_sys_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
c0567c90-c0567d14: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000472e70)
Location: fs/open.c:918
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__se_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
c000000000472e70-c000000000472f3c: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253ac4)
Location: fs/open.c:918
Inline: True
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__se_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:__se_sys_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffe000253ac4-ffffffe000253b4a: dentry_open (STB_GLOBAL)
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
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d0950)
Location: fs/open.c:918
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812d0950-ffffffff812d09c0: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c15d0)
Location: fs/open.c:918
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812c15d0-ffffffff812c1640: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ce760)
Location: fs/open.c:918
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812ce760-ffffffff812ce7d0: dentry_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct file *dentry_open(const struct path *path, int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812df570)
Location: fs/open.c:918
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:open_detached_copy
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/exportfs/expfs.c:get_name
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_read
  - security/apparmor/file.c:aa_inherit_files
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - drivers/tty/pty.c:ptm_open_peer
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812df570-ffffffff812df5e0: dentry_open (STB_GLOBAL)
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
