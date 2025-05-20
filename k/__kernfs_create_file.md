# Function: <code>__kernfs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8128c0d0)
Location: fs/kernfs/file.c:908
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff8128c0d0-ffffffff8128c15e: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff812b96f0)
Location: fs/kernfs/file.c:929
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff812b96f0-ffffffff812b977d: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff812cee30)
Location: fs/kernfs/file.c:930
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff812cee30-ffffffff812ceebd: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff812dc4e0)
Location: fs/kernfs/file.c:976
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff812dc4e0-ffffffff812dc594: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81300e10)
Location: fs/kernfs/file.c:976
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff81300e10-ffffffff81300ec4: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8132eaf0)
Location: fs/kernfs/file.c:978
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff8132eaf0-ffffffff8132eba1: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81345ea0)
Location: fs/kernfs/file.c:977
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff81345ea0-ffffffff81345f51: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8136e1b0)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff8136e1b0-ffffffff8136e265: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81386370)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff81386370-ffffffff81386425: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813d0f70)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_add_file
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff813d0f70-ffffffff813d1025: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e2b80)
Location: fs/kernfs/file.c:971
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_add_file
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff813e2b80-ffffffff813e2c35: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e9790)
Location: fs/kernfs/file.c:971
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff813e9790-ffffffff813e9845: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8143b500)
Location: fs/kernfs/file.c:971
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff8143b500-ffffffff8143b5b5: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff814b67a0)
Location: fs/kernfs/file.c:973
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_bin_file_mode_ns
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff814b67a0-ffffffff814b6884: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8154da70)
Location: fs/kernfs/file.c:1033
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_bin_file_mode_ns
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff8154da70-ffffffff8154db54: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81585730)
Location: fs/kernfs/file.c:1033
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_bin_file_mode_ns
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff81585730-ffffffff81585814: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815be1e0)
Location: fs/kernfs/file.c:1011
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_bin_file_mode_ns
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff815be1e0-ffffffff815be2c4: __kernfs_create_file (STB_GLOBAL)
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
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffff800010455ca0)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffff800010455ca0-ffff800010455dcc: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (c0617f10)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
c0617f10-c0617fdc: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (c00000000056f940)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
c00000000056f940-c00000000056fa94: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffe0002e7766)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffe0002e7766-ffffffe0002e7838: __kernfs_create_file (STB_GLOBAL)
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
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8137e950)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff8137e950-ffffffff8137ea05: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8136f3e0)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff8136f3e0-ffffffff8136f495: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8137c420)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff8137c420-ffffffff8137c4d5: __kernfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_create_file(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops *ops, void *priv, const void *ns, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8138ff00)
Location: fs/kernfs/file.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
```
**Symbols:**

```
ffffffff8138ff00-ffffffff8138ffb5: __kernfs_create_file (STB_GLOBAL)
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
<code>parent, name, mode, size, ops, priv, ns, key</code> ➡️ <code>parent, name, mode, uid, gid, size, ops, priv, ns, key</code>
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
