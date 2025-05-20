# Function: <code>d_alloc_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81225970)
Location: fs/dcache.c:1651
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81225970-ffffffff812259da: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124dac0)
Location: fs/dcache.c:1688
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_mount
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
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
ffffffff8124dac0-ffffffff8124db14: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81260ba0)
Location: fs/dcache.c:1697
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
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
ffffffff81260ba0-ffffffff81260bf4: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126e370)
Location: fs/dcache.c:1727
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
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
ffffffff8126e370-ffffffff8126e3c4: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290c90)
Location: fs/dcache.c:1739
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
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
ffffffff81290c90-ffffffff81290ce4: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b7490)
Location: fs/dcache.c:1747
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
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
ffffffff812b7490-ffffffff812b74e4: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc5f0)
Location: fs/dcache.c:1750
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
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
ffffffff812cc5f0-ffffffff812cc644: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e91e0)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
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
ffffffff812e91e0-ffffffff812e9236: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fad80)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
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
ffffffff812fad80-ffffffff812fadd6: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813311c0)
Location: fs/dcache.c:1845
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:mknod_ptmx
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
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
ffffffff813311c0-ffffffff81331214: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133cb50)
Location: fs/dcache.c:1852
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:mknod_ptmx
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
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
ffffffff8133cb50-ffffffff8133cba4: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342fd0)
Location: fs/dcache.c:1879
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
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
ffffffff81342fd0-ffffffff81343024: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390930)
Location: fs/dcache.c:1880
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
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
ffffffff81390930-ffffffff81390984: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81412a70)
Location: fs/dcache.c:1905
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
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
ffffffff81412a70-ffffffff81412b30: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149e7d0)
Location: fs/dcache.c:1905
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
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
ffffffff8149e7d0-ffffffff8149e890: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d3af0)
Location: fs/dcache.c:1905
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
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
ffffffff814d3af0-ffffffff814d3bb0: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff815049c0)
Location: fs/dcache.c:1765
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
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
ffffffff815049c0-ffffffff81504a1d: d_alloc_name (STB_GLOBAL)
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
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aa048)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
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
ffff8000103aa048-ffff8000103aa0c0: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058b07c)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
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
c058b07c-c058b0f0: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a4e80)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
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
c0000000004a4e80-c0000000004a4f00: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026fe26)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - security/selinux/selinuxfs.c:sel_fill_super
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
ffffffe00026fe26-ffffffe00026fe70: d_alloc_name (STB_GLOBAL)
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
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f3360)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
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
ffffffff812f3360-ffffffff812f33b6: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e3f90)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
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
ffffffff812e3f90-ffffffff812e3fe6: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1170)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
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
ffffffff812f1170-ffffffff812f11c6: d_alloc_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *d_alloc_name(struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81302330)
Location: fs/dcache.c:1824
Inline: False
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_new
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
ffffffff81302330-ffffffff81302386: d_alloc_name (STB_GLOBAL)
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
