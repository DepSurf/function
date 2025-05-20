# Function: <code>get_fs_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8122b260)
Location: fs/filesystems.c:271
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:mnt_init
  - fs/namespace.c:do_mount
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff8122b260-ffffffff8122b303: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812539c0)
Location: fs/filesystems.c:271
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812539c0-ffffffff81253a63: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81266c10)
Location: fs/filesystems.c:271
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81266c10-ffffffff81266cb3: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81274490)
Location: fs/filesystems.c:272
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81274490-ffffffff81274578: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81296d90)
Location: fs/filesystems.c:273
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81296d90-ffffffff81296e75: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812bd0c0)
Location: fs/filesystems.c:261
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812bd0c0-ffffffff812bd1a1: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812d2380)
Location: fs/filesystems.c:261
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mount
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812d2380-ffffffff812d2461: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812ef3d0)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812ef3d0-ffffffff812ef4b6: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81300ea0)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81300ea0-ffffffff81300f86: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/filesystems.c (0)
Location: fs/filesystems.c:266
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff8133a2d4-ffffffff8133a2f2: get_fs_type.cold (STB_LOCAL)
ffffffff81339ff0-ffffffff8133a0bb: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/filesystems.c (0)
Location: fs/filesystems.c:266
Inline: False
Direct callers:
  - kernel/usermode_driver.c:blob_to_mnt
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81bea75c-ffffffff81bea77a: get_fs_type.cold (STB_LOCAL)
ffffffff81345d00-ffffffff81345dcb: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/filesystems.c (0)
Location: fs/filesystems.c:266
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81bdc791-ffffffff81bdc7af: get_fs_type.cold (STB_LOCAL)
ffffffff8134c0c0-ffffffff8134c18a: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/filesystems.c (0)
Location: fs/filesystems.c:273
Inline: False
Direct callers:
  - init/do_mounts.c:mount_root
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81cc3e41-ffffffff81cc3e73: get_fs_type.cold (STB_LOCAL)
ffffffff81399f00-ffffffff81399fd5: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/filesystems.c (0)
Location: fs/filesystems.c:273
Inline: False
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81e76741-ffffffff81e76774: get_fs_type.cold (STB_LOCAL)
ffffffff8141cc50-ffffffff8141cd1e: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/filesystems.c (0)
Location: fs/filesystems.c:273
Inline: False
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff82068bc0-ffffffff82068bd5: get_fs_type.cold (STB_LOCAL)
ffffffff814a8df0-ffffffff814a8ed3: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/filesystems.c (0)
Location: fs/filesystems.c:273
Inline: False
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff820e84fe-ffffffff820e8513: get_fs_type.cold (STB_LOCAL)
ffffffff814dddc0-ffffffff814ddea3: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/filesystems.c (0)
Location: fs/filesystems.c:273
Inline: False
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff821c5258-ffffffff821c526d: get_fs_type.cold (STB_LOCAL)
ffffffff81510810-ffffffff815108f3: get_fs_type (STB_GLOBAL)
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
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffff8000103b3110)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__arm64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffff8000103b3110-ffff8000103b3228: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0591fb8)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
c0591fb8-c05920d8: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0000000004af2b0)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
c0000000004af2b0-c0000000004af440: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffe000276c48)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffe000276c48-ffffffe000276d30: get_fs_type (STB_GLOBAL)
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
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f9480)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812f9480-ffffffff812f9566: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812ea0a0)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812ea0a0-ffffffff812ea186: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f7270)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff812f7270-ffffffff812f7356: get_fs_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file_system_type *get_fs_type(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81308590)
Location: fs/filesystems.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff81308590-ffffffff81308676: get_fs_type (STB_GLOBAL)
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
