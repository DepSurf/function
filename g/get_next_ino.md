# Function: <code>get_next_ino</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81226c70)
Location: fs/inode.c:842
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_file
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81226c70-ffffffff81226cb8: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f390)
Location: fs/inode.c:851
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:__securityfs_setup_d_inode
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff8124f390-ffffffff8124f3dc: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812623c0)
Location: fs/inode.c:853
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:__securityfs_setup_d_inode
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812623c0-ffffffff8126240c: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126fca0)
Location: fs/inode.c:854
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:__aafs_setup_d_inode
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff8126fca0-ffffffff8126fcec: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812925c0)
Location: fs/inode.c:854
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812925c0-ffffffff8129260c: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8070)
Location: fs/inode.c:859
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812b8070-ffffffff812b80af: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cd1c0)
Location: fs/inode.c:867
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812cd1c0-ffffffff812cd1ff: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ea200)
Location: fs/inode.c:880
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812ea200-ffffffff812ea24c: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fbce0)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812fbce0-ffffffff812fbd2c: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81334a80)
Location: fs/inode.c:892
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:get_pipe_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81334a80-ffffffff81334acc: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813403f0)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - fs/pipe.c:get_pipe_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff813403f0-ffffffff8134043c: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81346920)
Location: fs/inode.c:898
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81346920-ffffffff8134696c: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394380)
Location: fs/inode.c:902
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81394380-ffffffff813943cc: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814160e0)
Location: fs/inode.c:983
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff814160e0-ffffffff81416145: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a1160)
Location: fs/inode.c:982
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff814a1160-ffffffff814a11c5: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d6470)
Location: fs/inode.c:984
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff814d6470-ffffffff814d64d5: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81508840)
Location: fs/inode.c:969
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/event_inode.c:eventfs_iterate
  - fs/tracefs/event_inode.c:eventfs_root_lookup
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81508840-ffffffff815088a5: get_next_ino (STB_GLOBAL)
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
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103acc68)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffff8000103acc68-ffff8000103accf0: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c534)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
c058c534-c058c5ac: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a65a0)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
c0000000004a65a0-c0000000004a6624: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000270d4a)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffe000270d4a-ffffffe000270dae: get_next_ino (STB_GLOBAL)
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
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f42c0)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812f42c0-ffffffff812f430c: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e4ef0)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812e4ef0-ffffffff812e4f3c: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f20d0)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812f20d0-ffffffff812f211c: get_next_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int get_next_ino();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813036a0)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff813036a0-ffffffff813036f5: get_next_ino (STB_GLOBAL)
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
