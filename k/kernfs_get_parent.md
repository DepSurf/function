# Function: <code>kernfs_get_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128a540)
Location: fs/kernfs/dir.c:318
Inline: False
Direct callers:
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff8128a540-ffffffff8128a581: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7970)
Location: fs/kernfs/dir.c:317
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff812b7970-ffffffff812b79b1: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd100)
Location: fs/kernfs/dir.c:267
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff812cd100-ffffffff812cd141: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812da700)
Location: fs/kernfs/dir.c:277
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff812da700-ffffffff812da741: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fef60)
Location: fs/kernfs/dir.c:278
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff812fef60-ffffffff812fefa1: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132cbf0)
Location: fs/kernfs/dir.c:278
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff8132cbf0-ffffffff8132cc31: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81343f30)
Location: fs/kernfs/dir.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff81343f30-ffffffff81343f71: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c1a0)
Location: fs/kernfs/dir.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff8136c1a0-ffffffff8136c1e5: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384350)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff81384350-ffffffff81384395: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cee30)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff813cee30-ffffffff813cee75: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0a60)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff813e0a60-ffffffff813e0aa5: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7590)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff813e7590-ffffffff813e75d5: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814392a0)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff814392a0-ffffffff814392ed: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b42d0)
Location: fs/kernfs/dir.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff814b42d0-ffffffff814b431f: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b150)
Location: fs/kernfs/dir.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff8154b150-ffffffff8154b19f: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81582da0)
Location: fs/kernfs/dir.c:292
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff81582da0-ffffffff81582def: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bb9d0)
Location: fs/kernfs/dir.c:292
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff815bb9d0-ffffffff815bba1f: kernfs_get_parent (STB_GLOBAL)
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
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010452e90)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffff800010452e90-ffff800010452f50: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0615b54)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
c0615b54-c0615ba0: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056c160)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
c00000000056c160-c00000000056c1d8: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5722)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffe0002e5722-ffffffe0002e577a: kernfs_get_parent (STB_GLOBAL)
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
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137c930)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff8137c930-ffffffff8137c975: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d400)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff8136d400-ffffffff8136d445: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a400)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff8137a400-ffffffff8137a445: kernfs_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_parent(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138def0)
Location: fs/kernfs/dir.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
```
**Symbols:**

```
ffffffff8138def0-ffffffff8138df35: kernfs_get_parent (STB_GLOBAL)
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
