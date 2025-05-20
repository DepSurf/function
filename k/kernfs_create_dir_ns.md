# Function: <code>kernfs_create_dir_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128aaa0)
Location: fs/kernfs/dir.c:917
Inline: False
Direct callers:
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8128aaa0-ffffffff8128ab18: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7fc0)
Location: fs/kernfs/dir.c:965
Inline: False
Direct callers:
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812b7fc0-ffffffff812b803a: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd760)
Location: fs/kernfs/dir.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812cd760-ffffffff812cd7da: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812dad10)
Location: fs/kernfs/dir.c:925
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812dad10-ffffffff812dad97: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff5f0)
Location: fs/kernfs/dir.c:992
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812ff5f0-ffffffff812ff677: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132d2b0)
Location: fs/kernfs/dir.c:1012
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8132d2b0-ffffffff8132d326: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344650)
Location: fs/kernfs/dir.c:1012
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81344650-ffffffff813446c6: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c870)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136c870-ffffffff8136c8e8: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384a20)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81384a20-ffffffff81384a98: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf4e0)
Location: fs/kernfs/dir.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813cf4e0-ffffffff813cf58f: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e1110)
Location: fs/kernfs/dir.c:1016
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813e1110-ffffffff813e11bf: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7d40)
Location: fs/kernfs/dir.c:1016
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813e7d40-ffffffff813e7def: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439a60)
Location: fs/kernfs/dir.c:975
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81439a60-ffffffff81439b19: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4ab0)
Location: fs/kernfs/dir.c:1001
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff814b4ab0-ffffffff814b4b9a: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b9c0)
Location: fs/kernfs/dir.c:1023
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8154b9c0-ffffffff8154baaa: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583650)
Location: fs/kernfs/dir.c:1027
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81583650-ffffffff8158373a: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bc190)
Location: fs/kernfs/dir.c:1043
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff815bc190-ffffffff815bc22f: kernfs_create_dir_ns (STB_GLOBAL)
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
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff8000104538d0)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffff8000104538d0-ffff8000104539b0: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c061647c)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c061647c-c0616500: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056cd60)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c00000000056cd60-c00000000056ce48: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5ea8)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffe0002e5ea8-ffffffe0002e5f42: kernfs_create_dir_ns (STB_GLOBAL)
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
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137d000)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137d000-ffffffff8137d078: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136dac0)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136dac0-ffffffff8136db38: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137aad0)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137aad0-ffffffff8137ab48: kernfs_create_dir_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *kernfs_create_dir_ns(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, void *priv, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e5d0)
Location: fs/kernfs/dir.c:1013
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8138e5d0-ffffffff8138e648: kernfs_create_dir_ns (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>kuid_t uid</code>
</li>
<li>
<b>Param added. </b>
<code>kgid_t gid</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, name, mode, priv, ns</code> ➡️ <code>parent, name, mode, uid, gid, priv, ns</code>
</li>
</ul>
</details>
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
