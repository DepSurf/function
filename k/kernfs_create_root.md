# Function: <code>kernfs_create_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128aba0)
Location: fs/kernfs/dir.c:860
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8128aba0-ffffffff8128ac88: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b80c0)
Location: fs/kernfs/dir.c:908
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff812b80c0-ffffffff812b81a8: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd860)
Location: fs/kernfs/dir.c:858
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff812cd860-ffffffff812cd948: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812dae30)
Location: fs/kernfs/dir.c:868
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff812dae30-ffffffff812daf26: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff710)
Location: fs/kernfs/dir.c:934
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff812ff710-ffffffff812ff814: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132d3b0)
Location: fs/kernfs/dir.c:951
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8132d3b0-ffffffff8132d4c6: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344750)
Location: fs/kernfs/dir.c:951
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff81344750-ffffffff81344866: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c970)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8136c970-ffffffff8136ca82: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384b20)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff81384b20-ffffffff81384c32: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf640)
Location: fs/kernfs/dir.c:946
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff813cf640-ffffffff813cf750: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e1270)
Location: fs/kernfs/dir.c:945
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff813e1270-ffffffff813e1380: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7ea0)
Location: fs/kernfs/dir.c:945
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff813e7ea0-ffffffff813e7fb0: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439be0)
Location: fs/kernfs/dir.c:904
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff81439be0-ffffffff81439cf0: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4c90)
Location: fs/kernfs/dir.c:914
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff814b4c90-ffffffff814b4db6: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154bbc0)
Location: fs/kernfs/dir.c:934
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8154bbc0-ffffffff8154bce6: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583850)
Location: fs/kernfs/dir.c:936
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff81583850-ffffffff815839aa: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bc300)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff815bc300-ffffffff815bc487: kernfs_create_root (STB_GLOBAL)
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
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453a58)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffff800010453a58-ffff800010453b88: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0616590)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
c0616590-c06166a8: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056cf30)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
c00000000056cf30-c00000000056d0f4: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5fd6)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffe0002e5fd6-ffffffe0002e60c8: kernfs_create_root (STB_GLOBAL)
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
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137d100)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8137d100-ffffffff8137d212: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136dbc0)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8136dbc0-ffffffff8136dcd2: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137abd0)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8137abd0-ffffffff8137ace2: kernfs_create_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_root *kernfs_create_root(struct kernfs_syscall_ops *scops, unsigned int flags, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e6d0)
Location: fs/kernfs/dir.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8138e6d0-ffffffff8138e7e2: kernfs_create_root (STB_GLOBAL)
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
