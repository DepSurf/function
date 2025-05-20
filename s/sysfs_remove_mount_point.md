# Function: <code>sysfs_remove_mount_point</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8128cc40)
Location: fs/sysfs/dir.c:151
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
  - security/selinux/selinuxfs.c:exit_sel_fs
```
**Symbols:**

```
ffffffff8128cc40-ffffffff8128cc56: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff812ba2c0)
Location: fs/sysfs/dir.c:151
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
  - security/selinux/selinuxfs.c:exit_sel_fs
```
**Symbols:**

```
ffffffff812ba2c0-ffffffff812ba2d6: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff812cf9f0)
Location: fs/sysfs/dir.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
  - security/selinux/selinuxfs.c:exit_sel_fs
```
**Symbols:**

```
ffffffff812cf9f0-ffffffff812cfa06: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff812dd0f0)
Location: fs/sysfs/dir.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
```
**Symbols:**

```
ffffffff812dd0f0-ffffffff812dd106: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81301a20)
Location: fs/sysfs/dir.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
```
**Symbols:**

```
ffffffff81301a20-ffffffff81301a36: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8132f870)
Location: fs/sysfs/dir.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:exit_pstore_fs
  - fs/pstore/inode.c:init_pstore_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff8132f870-ffffffff8132f886: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81346c10)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81346c10-ffffffff81346c26: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8136ef50)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff8136ef50-ffffffff8136ef66: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff813872d0)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff813872d0-ffffffff813872e6: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff813d1fa0)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff813d1fa0-ffffffff813d1fb6: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff813e3cf0)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff813e3cf0-ffffffff813e3d06: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff813ea8f0)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff813ea8f0-ffffffff813ea906: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8143c670)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff8143c670-ffffffff8143c686: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff814b7ce0)
Location: fs/sysfs/dir.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff814b7ce0-ffffffff814b7d02: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8154f1b0)
Location: fs/sysfs/dir.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff8154f1b0-ffffffff8154f1d2: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81586e80)
Location: fs/sysfs/dir.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81586e80-ffffffff81586ea2: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff815bf9e0)
Location: fs/sysfs/dir.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff815bf9e0-ffffffff815bfa02: sysfs_remove_mount_point (STB_GLOBAL)
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
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffff800010457090)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffff800010457090-ffff8000104570c8: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (c0619098)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
c0619098-c06190bc: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (c0000000005713d0)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
c0000000005713d0-c00000000057140c: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffe0002e8612)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffe0002e8612-ffffffe0002e8648: sysfs_remove_mount_point (STB_GLOBAL)
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
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8137f8b0)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff8137f8b0-ffffffff8137f8c6: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81370340)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81370340-ffffffff81370356: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8137d380)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff8137d380-ffffffff8137d396: sysfs_remove_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sysfs_remove_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81390e60)
Location: fs/sysfs/dir.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - fs/debugfs/inode.c:debugfs_init
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81390e60-ffffffff81390e76: sysfs_remove_mount_point (STB_GLOBAL)
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
