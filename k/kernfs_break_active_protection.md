# Function: <code>kernfs_break_active_protection</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128ace0)
Location: fs/kernfs/dir.c:1273
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8128ace0-ffffffff8128acf0: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b8250)
Location: fs/kernfs/dir.c:1322
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff812b8200-ffffffff812b8210: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd9f0)
Location: fs/kernfs/dir.c:1273
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff812cd9a0-ffffffff812cd9b0: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812daff0)
Location: fs/kernfs/dir.c:1283
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff812dafa0-ffffffff812dafb0: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff8e0)
Location: fs/kernfs/dir.c:1348
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff812ff890-ffffffff812ff8a0: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132d590)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff8132d540-ffffffff8132d550: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344930)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff813448e0-ffffffff813448f0: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136cb4e)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff8136cb00-ffffffff8136cb10: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384cfe)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff81384cb0-ffffffff81384cc0: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf82e)
Location: fs/kernfs/dir.c:1375
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff813cf7a0-ffffffff813cf7e3: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e145e)
Location: fs/kernfs/dir.c:1374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff813e13d0-ffffffff813e1413: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e808e)
Location: fs/kernfs/dir.c:1376
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff813e8000-ffffffff813e8043: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439dce)
Location: fs/kernfs/dir.c:1403
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff81439d40-ffffffff81439d83: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4f3d)
Location: fs/kernfs/dir.c:1445
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff814b4e80-ffffffff814b4edf: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154bf7d)
Location: fs/kernfs/dir.c:1514
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff8154bea0-ffffffff8154beff: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583c3d)
Location: fs/kernfs/dir.c:1521
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff81583b60-ffffffff81583bbf: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bc71d)
Location: fs/kernfs/dir.c:1537
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff815bc640-ffffffff815bc69f: kernfs_break_active_protection (STB_GLOBAL)
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
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453cd4)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffff800010453c18-ffff800010453c44: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c06167b4)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
c0616728-c0616744: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056d240)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
c00000000056d1b0-c00000000056d1c4: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e61e8)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffe0002e614c-ffffffe0002e6190: kernfs_break_active_protection (STB_GLOBAL)
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
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137d2de)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff8137d290-ffffffff8137d2a0: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136dd9e)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff8136dd50-ffffffff8136dd60: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137adae)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff8137ad60-ffffffff8137ad70: kernfs_break_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kernfs_break_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e8ae)
Location: fs/kernfs/dir.c:1371
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_break_active_protection
```
**Symbols:**

```
ffffffff8138e860-ffffffff8138e870: kernfs_break_active_protection (STB_GLOBAL)
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
