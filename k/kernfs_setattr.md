# Function: <code>kernfs_setattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81289040)
Location: fs/kernfs/inode.c:102
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_chmod_file
```
**Symbols:**

```
ffffffff81289040-ffffffff8128907e: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812b6540)
Location: fs/kernfs/inode.c:105
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_chmod_file
```
**Symbols:**

```
ffffffff812b6540-ffffffff812b657e: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812cbd70)
Location: fs/kernfs/inode.c:102
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_chmod_file
```
**Symbols:**

```
ffffffff812cbd70-ffffffff812cbdae: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812d91c0)
Location: fs/kernfs/inode.c:102
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_chmod_file
```
**Symbols:**

```
ffffffff812d91c0-ffffffff812d91fe: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812fda20)
Location: fs/kernfs/inode.c:102
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_chmod_file
```
**Symbols:**

```
ffffffff812fda20-ffffffff812fda5e: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8132b680)
Location: fs/kernfs/inode.c:102
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_chmod_file
```
**Symbols:**

```
ffffffff8132b680-ffffffff8132b6be: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813429e0)
Location: fs/kernfs/inode.c:102
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_chmod_file
```
**Symbols:**

```
ffffffff813429e0-ffffffff81342a1e: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136ab40)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_chmod_file
```
**Symbols:**

```
ffffffff8136ab40-ffffffff8136ab82: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81382d00)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:internal_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff81382d00-ffffffff81382d42: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd780)
Location: fs/kernfs/inode.c:105
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff813cd780-ffffffff813cd7c2: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813df3b0)
Location: fs/kernfs/inode.c:105
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff813df3b0-ffffffff813df3f2: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e5f80)
Location: fs/kernfs/inode.c:105
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff813e5f80-ffffffff813e5fc2: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81437b80)
Location: fs/kernfs/inode.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff81437b80-ffffffff81437bc2: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b28d0)
Location: fs/kernfs/inode.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff814b28d0-ffffffff814b2925: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815494a0)
Location: fs/kernfs/inode.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff815494a0-ffffffff815494f5: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81581080)
Location: fs/kernfs/inode.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff81581080-ffffffff815810d8: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b9b30)
Location: fs/kernfs/inode.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff815b9b30-ffffffff815b9b88: kernfs_setattr (STB_GLOBAL)
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
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffff8000104511d8)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:internal_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffff8000104511d8-ffff800010451234: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c06141b4)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:internal_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
c06141b4-c0614200: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c000000000569800)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:internal_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
c000000000569800-c000000000569878: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffe0002e409e)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:internal_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffe0002e409e-ffffffe0002e40f4: kernfs_setattr (STB_GLOBAL)
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
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8137b2e0)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:internal_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff8137b2e0-ffffffff8137b322: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136bdb0)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:internal_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff8136bdb0-ffffffff8136bdf2: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81378db0)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:internal_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff81378db0-ffffffff81378df2: kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8138c860)
Location: fs/kernfs/inode.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - fs/sysfs/file.c:internal_change_owner
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
```
**Symbols:**

```
ffffffff8138c860-ffffffff8138c8a2: kernfs_setattr (STB_GLOBAL)
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
