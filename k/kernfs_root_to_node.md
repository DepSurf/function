# Function: <code>kernfs_root_to_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *kernfs_root_to_node(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4860)
Location: fs/kernfs/dir.c:984
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff814b4860-ffffffff814b4874: kernfs_root_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *kernfs_root_to_node(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b780)
Location: fs/kernfs/dir.c:1006
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8154b780-ffffffff8154b794: kernfs_root_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *kernfs_root_to_node(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815833f0)
Location: fs/kernfs/dir.c:1010
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff815833f0-ffffffff81583404: kernfs_root_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_root_to_node(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bbf30)
Location: fs/kernfs/dir.c:1026
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff815bbf30-ffffffff815bbf44: kernfs_root_to_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
