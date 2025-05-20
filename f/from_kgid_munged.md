# Function: <code>from_kgid_munged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8111e0b0)
Location: kernel/user_namespace.c:356
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:sys_getgid
  - kernel/sys.c:sys_getegid
  - kernel/groups.c:SyS_getgroups
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getegid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_new_stat
  - fs/compat.c:cp_compat_stat
  - fs/compat.c:cp_compat_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff8111e0b0-ffffffff8111e126: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81125f80)
Location: kernel/user_namespace.c:356
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:sys_getegid
  - kernel/sys.c:sys_getgid
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/groups.c:SyS_getgroups
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/compat.c:cp_compat_stat
  - fs/compat.c:cp_compat_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81125f80-ffffffff81125ff7: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8112f9d0)
Location: kernel/user_namespace.c:402
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:sys_getegid
  - kernel/sys.c:sys_getgid
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/groups.c:SyS_getgroups
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/compat.c:cp_compat_stat
  - fs/compat.c:cp_compat_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8112f9d0-ffffffff8112fa47: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81130fe0)
Location: kernel/user_namespace.c:403
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:sys_getegid
  - kernel/sys.c:sys_getgid
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/groups.c:SyS_getgroups
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81130fe0-ffffffff81131056: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113e2b0)
Location: kernel/user_namespace.c:509
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:sys_getegid
  - kernel/sys.c:sys_getgid
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/sys.c:SyS_getresgid
  - kernel/groups.c:SyS_getgroups
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:SyS_getgroups16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/uid16.c:SyS_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8113e2b0-ffffffff8113e2ce: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8114cc50)
Location: kernel/user_namespace.c:509
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:__x64_sys_getegid
  - kernel/sys.c:__x64_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:groups_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8114cc50-ffffffff8114cc6e: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81159870)
Location: kernel/user_namespace.c:509
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:__x64_sys_getegid
  - kernel/sys.c:__x64_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:groups_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81159870-ffffffff8115988e: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81165fc0)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:__x64_sys_getegid
  - kernel/sys.c:__x64_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:groups_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81165fc0-ffffffff81165fde: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81171e80)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:__x64_sys_getegid
  - kernel/sys.c:__x64_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:groups_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81171e80-ffffffff81171e9e: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81183b60)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - kernel/sys.c:__do_sys_getegid
  - kernel/sys.c:__do_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81183b60-ffffffff81183b7e: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811808c0)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - kernel/sys.c:__do_sys_getegid
  - kernel/sys.c:__do_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff811808c0-ffffffff811808de: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81181920)
Location: kernel/user_namespace.c:504
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - kernel/sys.c:__do_sys_getegid
  - kernel/sys.c:__do_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81181920-ffffffff8118193e: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811a98c0)
Location: kernel/user_namespace.c:520
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - kernel/sys.c:__do_sys_getegid
  - kernel/sys.c:__do_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/kqid.c:from_kqid_munged
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff811a98c0-ffffffff811a98de: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811dad00)
Location: kernel/user_namespace.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - kernel/sys.c:__do_sys_getegid
  - kernel/sys.c:__do_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/kqid.c:from_kqid_munged
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff811dad00-ffffffff811dad26: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812204f0)
Location: kernel/user_namespace.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - kernel/sys.c:__do_sys_getegid
  - kernel/sys.c:__do_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/kqid.c:from_kqid_munged
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff812204f0-ffffffff81220516: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81236820)
Location: kernel/user_namespace.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - kernel/sys.c:__do_sys_getegid
  - kernel/sys.c:__do_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/kqid.c:from_kqid_munged
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff81236820-ffffffff81236846: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81251b30)
Location: kernel/user_namespace.c:528
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - kernel/sys.c:__do_sys_getegid
  - kernel/sys.c:__do_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:__ia32_sys_getgroups
  - kernel/groups.c:__x64_sys_getgroups
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/bpf/inode.c:bpf_show_options
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/kqid.c:from_kqid_munged
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - fs/efivarfs/super.c:efivarfs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff81251b30-ffffffff81251b56: from_kgid_munged (STB_GLOBAL)
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
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e5c00)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_getegid
  - kernel/sys.c:__arm64_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__arm64_sys_getresgid
  - kernel/sys.c:__arm64_sys_getresgid
  - kernel/sys.c:__arm64_sys_getresgid
  - kernel/groups.c:groups_to_user
  - kernel/uid16.c:__arm64_sys_getgroups16
  - kernel/uid16.c:__arm64_sys_getgroups16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:groups_to_user
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffff8000101e5c00-ffff8000101e5c44: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0426568)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - kernel/sys.c:sys_getegid
  - kernel/sys.c:sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/groups.c:__se_sys_getgroups
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:__se_sys_getgroups16
  - kernel/uid16.c:__se_sys_getgroups16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
c0426568-c0426598: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0000000002562d0)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - kernel/sys.c:sys_getegid
  - kernel/sys.c:sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/groups.c:__se_sys_getgroups
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
c0000000002562d0-c00000000025631c: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015b7ce)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - kernel/sys.c:sys_getegid
  - kernel/sys.c:sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/groups.c:__se_sys_getgroups
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffe00015b7ce-ffffffe00015b814: from_kgid_munged (STB_GLOBAL)
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
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116a4a0)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:__x64_sys_getegid
  - kernel/sys.c:__x64_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:groups_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8116a4a0-ffffffff8116a4be: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115d6a0)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:__x64_sys_getegid
  - kernel/sys.c:__x64_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:groups_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8115d6a0-ffffffff8115d6be: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81168270)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:__x64_sys_getegid
  - kernel/sys.c:__x64_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:groups_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81168270-ffffffff8116828e: from_kgid_munged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81175910)
Location: kernel/user_namespace.c:503
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - kernel/sys.c:__x64_sys_getegid
  - kernel/sys.c:__x64_sys_getgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__ia32_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/sys.c:__x64_sys_getresgid
  - kernel/groups.c:groups_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:groups16_to_user
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__ia32_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/uid16.c:__x64_sys_getresgid16
  - kernel/acct.c:do_acct_process
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_show_options
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/proc/inode.c:proc_show_options
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/devpts/inode.c:devpts_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/fat/inode.c:fat_show_options
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/inode.c:fuse_show_options
  - fs/debugfs/inode.c:debugfs_show_options
  - fs/tracefs/inode.c:tracefs_show_options
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/proc.c:proc_keys_show
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/net/tun.c:tun_fill_info
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81175910-ffffffff8117592e: from_kgid_munged (STB_GLOBAL)
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
