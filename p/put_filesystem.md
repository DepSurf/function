# Function: <code>put_filesystem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8122b2f6)
Location: fs/filesystems.c:41
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:SyS_sysfs
Direct callers:
  - kernel/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:mnt_init
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff8122b3b0-ffffffff8122b3c4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81253a56)
Location: fs/filesystems.c:41
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:SyS_sysfs
Direct callers:
  - kernel/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81253b10-ffffffff81253b24: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81266ca6)
Location: fs/filesystems.c:41
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:SyS_sysfs
Direct callers:
  - kernel/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81266d60-ffffffff81266d74: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81274543)
Location: fs/filesystems.c:42
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:SyS_sysfs
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812745a0-ffffffff812745b4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81296e37)
Location: fs/filesystems.c:43
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:SyS_sysfs
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81296ea0-ffffffff81296eb4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812bd15a)
Location: fs/filesystems.c:43
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812bd2a0-ffffffff812bd2b4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812d241a)
Location: fs/filesystems.c:43
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812d2560-ffffffff812d2574: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812ef461)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812ef5b0-ffffffff812ef5c4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81300f31)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81301080-ffffffff81301094: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8133a094)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff8133a2c0-ffffffff8133a2d4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81345da4)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/usermode_driver.c:blob_to_mnt
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81345fd0-ffffffff81345fe4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8134c163)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff8134c390-ffffffff8134c3a4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81399fa3)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - init/do_mounts.c:mount_root
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff8139a1e0-ffffffff8139a1f4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8141ccee)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff8141cd50-ffffffff8141cd6a: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814a8e8e)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff814a8f30-ffffffff814a8f4a: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814dde5e)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff814ddf00-ffffffff814ddf1a: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff815108ae)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81510950-ffffffff8151096a: put_filesystem (STB_GLOBAL)
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
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffff8000103b31cc)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__arm64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffff8000103b37e0-ffff8000103b380c: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0592064)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:__se_sys_sysfs
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__se_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
c05921b4-c05921d4: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0000000004af3f0)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:__se_sys_sysfs
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__se_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
c0000000004af590-c0000000004af5c8: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffe000276cf4)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:__se_sys_sysfs
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__se_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffe000276de2-ffffffe000276e0c: put_filesystem (STB_GLOBAL)
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
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f9511)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812f9660-ffffffff812f9674: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812ea131)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812ea280-ffffffff812ea294: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f7301)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812f7450-ffffffff812f7464: put_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81308621)
Location: fs/filesystems.c:44
Inline: True
Inline callers:
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:fs_name
Direct callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/trace/trace.c:trace_automount
  - fs/super.c:deactivate_locked_super
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:put_fs_context
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff813086f0-ffffffff81308704: put_filesystem (STB_GLOBAL)
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
