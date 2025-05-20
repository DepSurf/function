# Function: <code>putname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121bde0)
Location: fs/namei.c:244
Inline: True
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
  - fs/open.c:filp_open
  - fs/open.c:do_sys_open
  - fs/exec.c:open_exec
  - fs/exec.c:SyS_uselib
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:do_file_open_root
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_unlink
```
**Symbols:**

```
ffffffff8121bde0-ffffffff8121be38: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81243260)
Location: fs/namei.c:246
Inline: True
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:SyS_uselib
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff81243260-ffffffff812432b8: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812561e0)
Location: fs/namei.c:246
Inline: True
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:SyS_uselib
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff812561e0-ffffffff81256238: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81262380)
Location: fs/namei.c:246
Inline: True
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:SyS_uselib
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81262380-ffffffff812623d0: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81284bc0)
Location: fs/namei.c:247
Inline: True
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:SyS_uselib
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81284bc0-ffffffff81284c11: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812abd30)
Location: fs/namei.c:250
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812abd30-ffffffff812abd7c: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c0e30)
Location: fs/namei.c:250
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812c0e30-ffffffff812c0e7c: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dd600)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812dd600-ffffffff812dd650: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ef130)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812ef130-ffffffff812ef180: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813270e0)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/open.c:filp_open
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:open_exec
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/io_uring.c:io_cleanup_req
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff813270e0-ffffffff81327134: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813324f0)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:do_execveat_common
  - fs/exec.c:open_exec
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/io_uring.c:__io_clean_op
  - fs/io_uring.c:__io_clean_op
  - fs/io_uring.c:__io_clean_op
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff813324f0-ffffffff81332544: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81338540)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:do_sys_openat2
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/io_uring.c:io_clean_op
  - fs/io_uring.c:io_clean_op
  - fs/io_uring.c:io_clean_op
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81338540-ffffffff81338594: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81386230)
Location: fs/namei.c:256
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:do_sys_openat2
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/io_uring.c:io_clean_op
  - fs/io_uring.c:io_clean_op
  - fs/io_uring.c:io_clean_op
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81386230-ffffffff8138628e: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81406e30)
Location: fs/namei.c:257
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:audit_reset_context
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:do_sys_openat2
  - fs/open.c:filp_open
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_fstatat
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_linkat_prep
  - io_uring/io_uring.c:io_symlinkat_prep
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_fsetxattr
  - io_uring/io_uring.c:io_getxattr
  - io_uring/io_uring.c:io_fgetxattr
  - io_uring/io_uring.c:io_renameat_prep
```
**Symbols:**

```
ffffffff81406e30-ffffffff81406eaa: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814911a0)
Location: fs/namei.c:257
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:audit_reset_context
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:do_sys_openat2
  - fs/open.c:filp_open
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_fstatat
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/fs.c:io_link_cleanup
  - io_uring/fs.c:io_link_cleanup
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_mkdirat_cleanup
  - io_uring/fs.c:io_unlinkat_cleanup
  - io_uring/fs.c:io_renameat_cleanup
  - io_uring/fs.c:io_renameat_cleanup
  - io_uring/fs.c:io_renameat_prep
  - io_uring/openclose.c:io_open_cleanup
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
  - io_uring/statx.c:io_statx_cleanup
```
**Symbols:**

```
ffffffff814911a0-ffffffff8149121a: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814bf110)
Location: fs/namei.c:259
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:audit_reset_context
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:do_sys_openat2
  - fs/open.c:filp_open
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_fstatat
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/fs.c:io_link_cleanup
  - io_uring/fs.c:io_link_cleanup
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_mkdirat_cleanup
  - io_uring/fs.c:io_unlinkat_cleanup
  - io_uring/fs.c:io_renameat_cleanup
  - io_uring/fs.c:io_renameat_cleanup
  - io_uring/fs.c:io_renameat_prep
  - io_uring/openclose.c:io_open_cleanup
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
  - io_uring/statx.c:io_statx_cleanup
```
**Symbols:**

```
ffffffff814bf110-ffffffff814bf18a: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f1980)
Location: fs/namei.c:259
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:audit_reset_context
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:do_sys_openat2
  - fs/open.c:filp_open
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:user_path_locked_at
  - fs/namei.c:kern_path_locked
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/fs.c:io_link_cleanup
  - io_uring/fs.c:io_link_cleanup
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_mkdirat_cleanup
  - io_uring/fs.c:io_unlinkat_cleanup
  - io_uring/fs.c:io_renameat_cleanup
  - io_uring/fs.c:io_renameat_cleanup
  - io_uring/fs.c:io_renameat_prep
  - io_uring/openclose.c:io_open_cleanup
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
  - io_uring/statx.c:io_statx_cleanup
```
**Symbols:**

```
ffffffff814f1980-ffffffff814f19fa: putname (STB_GLOBAL)
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
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103988c0)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__arm64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__arm64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:__arm64_sys_sysfs
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffff8000103988c0-ffff800010398938: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057ef94)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:open_exec
  - fs/exec.c:__se_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:__se_sys_sysfs
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
c057ef94-c057f004: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000492d00)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__se_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:__se_sys_sysfs
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
c000000000492d00-c000000000492db0: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026652c)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:open_exec
  - fs/exec.c:__se_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
ffffffe00026652c-ffffffe000266594: putname (STB_GLOBAL)
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
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7710)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812e7710-ffffffff812e7760: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8350)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812d8350-ffffffff812d83a0: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5520)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812e5520-ffffffff812e5570: putname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void putname(struct filename *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f64a0)
Location: fs/namei.c:248
Inline: True
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:filename_lookup
  - fs/filesystems.c:fs_index
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812f64a0-ffffffff812f64f0: putname (STB_GLOBAL)
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
