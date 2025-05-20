# Function: <code>kernfs_rename_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128aef0)
Location: fs/kernfs/dir.c:1431
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rename
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff8128aef0-ffffffff8128b088: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b8410)
Location: fs/kernfs/dir.c:1480
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff812b8410-ffffffff812b85b2: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cdbb0)
Location: fs/kernfs/dir.c:1431
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff812cdbb0-ffffffff812cdd52: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812db1b0)
Location: fs/kernfs/dir.c:1441
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff812db1b0-ffffffff812db351: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ffaa0)
Location: fs/kernfs/dir.c:1506
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff812ffaa0-ffffffff812ffc41: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132d750)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff8132d750-ffffffff8132d8e1: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344af0)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff81344af0-ffffffff81344c96: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136cd10)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff8136cd10-ffffffff8136cec6: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384ec0)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff81384ec0-ffffffff81385076: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf9f0)
Location: fs/kernfs/dir.c:1533
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff813cf9f0-ffffffff813cfc27: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e1620)
Location: fs/kernfs/dir.c:1532
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff813e1620-ffffffff813e1857: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e8250)
Location: fs/kernfs/dir.c:1534
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff813e8250-ffffffff813e8487: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439f90)
Location: fs/kernfs/dir.c:1561
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff81439f90-ffffffff8143a1b7: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b5120)
Location: fs/kernfs/dir.c:1606
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff814b5120-ffffffff814b533d: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154c1a0)
Location: fs/kernfs/dir.c:1683
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff8154c1a0-ffffffff8154c3bd: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583e60)
Location: fs/kernfs/dir.c:1690
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff81583e60-ffffffff8158407d: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bc940)
Location: fs/kernfs/dir.c:1706
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff815bc940-ffffffff815bcb5d: kernfs_rename_ns (STB_GLOBAL)
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
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453ed0)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffff800010453ed0-ffff8000104540b4: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0616a04)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
c0616a04-c0616bb4: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056d4e0)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
c00000000056d4e0-c00000000056d994: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e63da)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffe0002e63da-ffffffe0002e65e0: kernfs_rename_ns (STB_GLOBAL)
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
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137d4a0)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff8137d4a0-ffffffff8137d656: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136df60)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff8136df60-ffffffff8136e10c: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137af70)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff8137af70-ffffffff8137b126: kernfs_rename_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node *kn, struct kernfs_node *new_parent, const char *new_name, const void *new_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138ea70)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_move_dir_ns
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
```
**Symbols:**

```
ffffffff8138ea70-ffffffff8138ec19: kernfs_rename_ns (STB_GLOBAL)
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
