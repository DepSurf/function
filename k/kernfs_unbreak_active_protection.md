# Function: <code>kernfs_unbreak_active_protection</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128acf0)
Location: fs/kernfs/dir.c:1297
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_kn_unlock
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8128acf0-ffffffff8128acff: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b82fd)
Location: fs/kernfs/dir.c:1346
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_kn_unlock
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff812b8210-ffffffff812b821f: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cda9d)
Location: fs/kernfs/dir.c:1297
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_kn_unlock
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff812cd9b0-ffffffff812cd9bf: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812db037)
Location: fs/kernfs/dir.c:1307
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff812dafb0-ffffffff812dafbf: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff927)
Location: fs/kernfs/dir.c:1372
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff812ff8a0-ffffffff812ff8af: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132d5d7)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff8132d550-ffffffff8132d55f: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344977)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff813448f0-ffffffff813448ff: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136cb95)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff8136cb10-ffffffff8136cb1f: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384d45)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff81384cc0-ffffffff81384ccf: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf8d8)
Location: fs/kernfs/dir.c:1399
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff813cf7f0-ffffffff813cf7ff: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e1508)
Location: fs/kernfs/dir.c:1398
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff813e1420-ffffffff813e142f: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e8138)
Location: fs/kernfs/dir.c:1400
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff813e8050-ffffffff813e805f: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439e78)
Location: fs/kernfs/dir.c:1427
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff81439d90-ffffffff81439d9f: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4fdf)
Location: fs/kernfs/dir.c:1469
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff814b4ee0-ffffffff814b4ef5: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154c01f)
Location: fs/kernfs/dir.c:1538
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff8154bf10-ffffffff8154bf25: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583cdf)
Location: fs/kernfs/dir.c:1545
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff81583bd0-ffffffff81583be5: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bc7bf)
Location: fs/kernfs/dir.c:1561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff815bc6b0-ffffffff815bc6c5: kernfs_unbreak_active_protection (STB_GLOBAL)
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
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453d20)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffff800010453c48-ffff800010453c94: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c061680c)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
c0616744-c0616778: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056d29c)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
c00000000056d1d0-c00000000056d1f0: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e62a6)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffe0002e6190-ffffffe0002e61ba: kernfs_unbreak_active_protection (STB_GLOBAL)
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
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137d325)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff8137d2a0-ffffffff8137d2af: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136dde5)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff8136dd60-ffffffff8136dd6f: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137adf5)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff8137ad70-ffffffff8137ad7f: kernfs_unbreak_active_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kernfs_unbreak_active_protection(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e8f5)
Location: fs/kernfs/dir.c:1395
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
```
**Symbols:**

```
ffffffff8138e870-ffffffff8138e87f: kernfs_unbreak_active_protection (STB_GLOBAL)
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
