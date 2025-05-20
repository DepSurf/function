# Function: <code>kernfs_activate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128a860)
Location: fs/kernfs/dir.c:1159
Inline: False
Direct callers:
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_setup_root
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_create_root
```
**Symbols:**

```
ffffffff8128a860-ffffffff8128a93a: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7db0)
Location: fs/kernfs/dir.c:1207
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff812b7db0-ffffffff812b7e8a: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd550)
Location: fs/kernfs/dir.c:1158
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff812cd550-ffffffff812cd62a: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812dab60)
Location: fs/kernfs/dir.c:1168
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff812dab60-ffffffff812dabdf: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff440)
Location: fs/kernfs/dir.c:1233
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff812ff440-ffffffff812ff4bf: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132d100)
Location: fs/kernfs/dir.c:1256
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff8132d100-ffffffff8132d17f: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813444a0)
Location: fs/kernfs/dir.c:1256
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff813444a0-ffffffff8134451f: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c6c0)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff8136c6c0-ffffffff8136c73e: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384870)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff81384870-ffffffff813848ee: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf2a0)
Location: fs/kernfs/dir.c:1261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff813cf2a0-ffffffff813cf3a9: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0ed0)
Location: fs/kernfs/dir.c:1260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff813e0ed0-ffffffff813e0fd9: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7b00)
Location: fs/kernfs/dir.c:1262
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff813e7b00-ffffffff813e7c09: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439820)
Location: fs/kernfs/dir.c:1289
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff81439820-ffffffff81439929: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4880)
Location: fs/kernfs/dir.c:1320
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff814b4880-ffffffff814b496f: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b7b0)
Location: fs/kernfs/dir.c:1369
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff8154b7b0-ffffffff8154b870: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583420)
Location: fs/kernfs/dir.c:1373
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff81583420-ffffffff815834e0: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bbf60)
Location: fs/kernfs/dir.c:1389
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff815bbf60-ffffffff815bc020: kernfs_activate (STB_GLOBAL)
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
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff8000104536d8)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffff8000104536d8-ffff8000104537a0: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c061620c)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
c061620c-c0616318: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056cab0)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
c00000000056cab0-c00000000056cba8: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5cd8)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffe0002e5cd8-ffffffe0002e5d84: kernfs_activate (STB_GLOBAL)
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
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137ce50)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff8137ce50-ffffffff8137cece: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d910)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff8136d910-ffffffff8136d98e: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a920)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff8137a920-ffffffff8137a99e: kernfs_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e420)
Location: fs/kernfs/dir.c:1257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_add_one
```
**Symbols:**

```
ffffffff8138e420-ffffffff8138e49e: kernfs_activate (STB_GLOBAL)
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
