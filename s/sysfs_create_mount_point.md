# Function: <code>sysfs_create_mount_point</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8128cce0)
Location: fs/sysfs/dir.c:130
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_init
  - fs/tracefs/inode.c:tracefs_init
```
**Symbols:**

```
ffffffff8128cce0-ffffffff8128cd30: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff812ba360)
Location: fs/sysfs/dir.c:130
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_init
  - fs/tracefs/inode.c:tracefs_init
```
**Symbols:**

```
ffffffff812ba360-ffffffff812ba3b0: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff812cfa90)
Location: fs/sysfs/dir.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup.c:cgroup_init
  - fs/tracefs/inode.c:tracefs_init
```
**Symbols:**

```
ffffffff812cfa90-ffffffff812cfae0: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff812dd180)
Location: fs/sysfs/dir.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/configfs/mount.c:configfs_init
  - fs/tracefs/inode.c:tracefs_init
```
**Symbols:**

```
ffffffff812dd180-ffffffff812dd1d0: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81301ab0)
Location: fs/sysfs/dir.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/configfs/mount.c:configfs_init
  - fs/tracefs/inode.c:tracefs_init
```
**Symbols:**

```
ffffffff81301ab0-ffffffff81301b00: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8132f8e0)
Location: fs/sysfs/dir.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:init_pstore_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8132f8e0-ffffffff8132f930: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81346c80)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81346c80-ffffffff81346cd0: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8136efc0)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8136efc0-ffffffff8136f023: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81387340)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81387340-ffffffff813873a3: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff813d2010)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff813d2010-ffffffff813d2073: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff813e3d60)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff813e3d60-ffffffff813e3dc3: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff813ea960)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff813ea960-ffffffff813ea9c3: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8143c6e0)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8143c6e0-ffffffff8143c743: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff814b7d60)
Location: fs/sysfs/dir.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff814b7d60-ffffffff814b7dd2: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8154f280)
Location: fs/sysfs/dir.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8154f280-ffffffff8154f2f2: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81586f50)
Location: fs/sysfs/dir.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81586f50-ffffffff81586fc2: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff815bfae0)
Location: fs/sysfs/dir.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff815bfae0-ffffffff815bfb52: sysfs_create_mount_point (STB_GLOBAL)
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
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffff800010457148)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffff800010457148-ffff8000104571c8: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (c0619130)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
c0619130-c0619184: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (c0000000005714d0)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
```
**Symbols:**

```
c0000000005714d0-c000000000571570: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffe0002e86c4)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
```
**Symbols:**

```
ffffffe0002e86c4-ffffffe0002e8732: sysfs_create_mount_point (STB_GLOBAL)
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
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8137f920)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8137f920-ffffffff8137f983: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff813703b0)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff813703b0-ffffffff81370413: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8137d3f0)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8137d3f0-ffffffff8137d453: sysfs_create_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_create_mount_point(struct kobject *parent_kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81390ed0)
Location: fs/sysfs/dir.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - fs/configfs/mount.c:configfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81390ed0-ffffffff81390f33: sysfs_create_mount_point (STB_GLOBAL)
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
