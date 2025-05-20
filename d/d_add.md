# Function: <code>d_add</code>

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
In fs/libfs.c (ffffffff81233f98)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/libfs.c:simple_fill_super
```
```
In fs/proc/base.c (ffffffff8127d7c8)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/base.c:proc_task_instantiate
```
```
In fs/proc/generic.c (ffffffff8127f5f4)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/fd.c (ffffffff81281b9b)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
```
In fs/proc/namespaces.c (ffffffff8128368b)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_instantiate
```
```
In fs/proc/self.c (ffffffff81283c48)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81283ec8)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/proc_sysctl.c (ffffffff81284ee2)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
```
In fs/devpts/inode.c (ffffffff8128e119)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ecryptfs/inode.c (ffffffff81301d44)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
```
In fs/fuse/control.c (ffffffff8131cabd)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
```
In fs/pstore/inode.c (ffffffff8132001a)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In fs/efivarfs/super.c (ffffffff81321a54)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff8134a69e)
Location: include/linux/dcache.h:285
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124d420)
Location: fs/dcache.c:2553
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_mount
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8124d420-ffffffff8124d5a0: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812604e0)
Location: fs/dcache.c:2562
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff812604e0-ffffffff81260660: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126dcc0)
Location: fs/dcache.c:2592
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8126dcc0-ffffffff8126de3e: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812901e0)
Location: fs/dcache.c:2604
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff812901e0-ffffffff8129035e: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5000)
Location: fs/dcache.c:2624
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff812b5000-ffffffff812b517d: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9e00)
Location: fs/dcache.c:2605
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff812c9e00-ffffffff812c9f7d: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e67f0)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff812e67f0-ffffffff812e6982: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8350)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff812f8350-ffffffff812f84e2: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331970)
Location: fs/dcache.c:2696
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:mknod_ptmx
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81331970-ffffffff813319ab: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133d310)
Location: fs/dcache.c:2703
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:mknod_ptmx
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff8133d310-ffffffff8133d34b: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343790)
Location: fs/dcache.c:2730
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff81343790-ffffffff813437cb: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813910c0)
Location: fs/dcache.c:2731
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/dir.c:configfs_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff813910c0-ffffffff813910fb: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81413430)
Location: fs/dcache.c:2756
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/dir.c:configfs_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff81413430-ffffffff81413470: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149e780)
Location: fs/dcache.c:2811
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/dir.c:configfs_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff8149e780-ffffffff8149e7c0: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d3aa0)
Location: fs/dcache.c:2811
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/dir.c:configfs_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff814d3aa0-ffffffff814d3ae0: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81506220)
Location: fs/dcache.c:2635
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/dir.c:configfs_lookup
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/tracefs/event_inode.c:eventfs_root_lookup
  - fs/tracefs/event_inode.c:eventfs_root_lookup
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81506220-ffffffff81506260: d_add (STB_GLOBAL)
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
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a68c8)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffff8000103a68c8-ffff8000103a6b00: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c05896d8)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
c05896d8-c05898cc: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a1760)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
c0000000004a1760-c0000000004a1a0c: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026ca36)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffe00026ca36-ffffffe00026cc10: d_add (STB_GLOBAL)
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
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0930)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff812f0930-ffffffff812f0ac2: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1560)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff812e1560-ffffffff812e16f2: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee740)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff812ee740-ffffffff812ee8d2: d_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void d_add(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81300b20)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81300b20-ffffffff81300cda: d_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
