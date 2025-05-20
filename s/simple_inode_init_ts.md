# Function: <code>simple_inode_init_ts</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 simple_inode_init_ts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81523435)
Location: fs/libfs.c:1967
Inline: True
Inline callers:
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:__shmem_get_inode
  - fs/pipe.c:create_pipe_files
  - fs/bad_inode.c:iget_failed
  - fs/nsfs.c:__ns_get_path
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/ialloc.c:__ext4_new_inode
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
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81520eb0-ffffffff81520ede: simple_inode_init_ts (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
