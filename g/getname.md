# Function: <code>getname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c030)
Location: fs/namei.c:204
Inline: True
Inline callers:
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
  - fs/open.c:do_sys_open
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_execve
  - fs/exec.c:compat_SyS_execve
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_unlink
```
**Symbols:**

```
ffffffff8121c030-ffffffff8121c044: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81245dfa)
Location: fs/namei.c:206
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:compat_SyS_execve
  - fs/exec.c:SyS_execve
  - fs/exec.c:SyS_uselib
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff812434b0-ffffffff812434c4: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81258d56)
Location: fs/namei.c:206
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:compat_SyS_execve
  - fs/exec.c:SyS_execve
  - fs/exec.c:SyS_uselib
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff81256430-ffffffff81256444: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81264e90)
Location: fs/namei.c:206
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:compat_SyS_execve
  - fs/exec.c:SyS_execve
  - fs/exec.c:SyS_uselib
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812625c0-ffffffff812625d4: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81287720)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_unlink
  - fs/namei.c:SyS_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:compat_SyS_execve
  - fs/exec.c:SyS_execve
  - fs/exec.c:SyS_uselib
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/quota.c:SyS_quotactl
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81284e10-ffffffff81284e24: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ac787)
Location: fs/namei.c:209
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812abf60-ffffffff812abf74: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c1887)
Location: fs/namei.c:209
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812c1060-ffffffff812c1074: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dde07)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812dd840-ffffffff812dd854: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ef927)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812ef370-ffffffff812ef384: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81327c11)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
Direct callers:
  - init/initramfs.c:clean_path
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/io_uring.c:__io_openat_prep
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81327350-ffffffff8132739b: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334c75)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:do_mkdirat
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_openat_prep
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81332760-ffffffff813327ab: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133ae05)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:do_mkdirat
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_openat_prep
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff813387b0-ffffffff813387fb: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81388a25)
Location: fs/namei.c:215
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/exec.c:__x64_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff813864a0-ffffffff813864eb: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81409a74)
Location: fs/namei.c:216
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:__io_openat_prep
  - io_uring/io_uring.c:io_linkat_prep
  - io_uring/io_uring.c:io_linkat_prep
  - io_uring/io_uring.c:io_symlinkat_prep
  - io_uring/io_uring.c:io_symlinkat_prep
  - io_uring/io_uring.c:io_mkdirat_prep
  - io_uring/io_uring.c:io_unlinkat_prep
  - io_uring/io_uring.c:io_renameat_prep
  - io_uring/io_uring.c:io_renameat_prep
```
**Symbols:**

```
ffffffff814070d0-ffffffff8140712e: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81494164)
Location: fs/namei.c:216
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_mkdirat_prep
  - io_uring/fs.c:io_unlinkat_prep
  - io_uring/fs.c:io_renameat_prep
  - io_uring/fs.c:io_renameat_prep
  - io_uring/openclose.c:__io_openat_prep
```
**Symbols:**

```
ffffffff81491470-ffffffff814914ce: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c91d4)
Location: fs/namei.c:217
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_mkdirat_prep
  - io_uring/fs.c:io_unlinkat_prep
  - io_uring/fs.c:io_renameat_prep
  - io_uring/fs.c:io_renameat_prep
  - io_uring/openclose.c:__io_openat_prep
```
**Symbols:**

```
ffffffff814c6b00-ffffffff814c6b5e: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fba94)
Location: fs/namei.c:217
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:user_path_locked_at
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_openat2
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:quotactl_block
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_mkdirat_prep
  - io_uring/fs.c:io_unlinkat_prep
  - io_uring/fs.c:io_renameat_prep
  - io_uring/fs.c:io_renameat_prep
  - io_uring/openclose.c:__io_openat_prep
```
**Symbols:**

```
ffffffff814f9450-ffffffff814f94ae: getname (STB_GLOBAL)
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
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103990d8)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__arm64_sys_unlink
  - fs/namei.c:__arm64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__arm64_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__arm64_compat_sys_execve
  - fs/exec.c:__arm64_sys_execve
  - fs/exec.c:__arm64_sys_uselib
  - fs/filesystems.c:__arm64_sys_sysfs
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffff800010398b10-ffff800010398b44: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057f754)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__se_sys_unlink
  - fs/namei.c:__se_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__se_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__se_sys_execve
  - fs/exec.c:__se_sys_uselib
  - fs/filesystems.c:__se_sys_sysfs
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
c057f1c0-c057f1e4: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0000000004937e0)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__se_sys_unlink
  - fs/namei.c:__se_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__se_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__se_compat_sys_execve
  - fs/exec.c:__se_sys_execve
  - fs/exec.c:__se_sys_uselib
  - fs/filesystems.c:__se_sys_sysfs
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
c000000000493040-c00000000049305c: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000266b92)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__se_sys_unlink
  - fs/namei.c:__se_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__se_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__se_sys_execve
  - fs/exec.c:__se_sys_uselib
  - fs/filesystems.c:__se_sys_sysfs
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
ffffffe000266716-ffffffe000266744: getname (STB_GLOBAL)
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
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7f07)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812e7950-ffffffff812e7964: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8b47)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812d8590-ffffffff812d85a4: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5d17)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812e5760-ffffffff812e5774: getname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname(const char *filename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f6c97)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:do_sys_open
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:fs_index
  - fs/quota/quota.c:kernel_quotactl
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812f66e0-ffffffff812f66f4: getname (STB_GLOBAL)
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
