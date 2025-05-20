# Function: <code>sysfs_warn_dup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8128cc60)
Location: fs/sysfs/dir.c:22
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8128cc60-ffffffff8128ccd1: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff812ba2e0)
Location: fs/sysfs/dir.c:22
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812ba2e0-ffffffff812ba351: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff812cfa10)
Location: fs/sysfs/dir.c:22
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812cfa10-ffffffff812cfa81: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff812dd110)
Location: fs/sysfs/dir.c:22
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812dd110-ffffffff812dd177: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81301a40)
Location: fs/sysfs/dir.c:22
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81301a40-ffffffff81301aa7: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8132faee-ffffffff8132fb14: sysfs_warn_dup.cold.4 (STB_LOCAL)
ffffffff8132f890-ffffffff8132f8dd: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81346e9e-ffffffff81346ec4: sysfs_warn_dup.cold.4 (STB_LOCAL)
ffffffff81346c30-ffffffff81346c7d: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136f1eb-ffffffff8136f212: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff8136ef70-ffffffff8136efbe: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8138756b-ffffffff81387592: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff813872f0-ffffffff8138733e: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813d223b-ffffffff813d2262: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff813d1fc0-ffffffff813d200e: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81bec14e-ffffffff81bec175: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff813e3d10-ffffffff813e3d5e: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81bde1ac-ffffffff81bde1d3: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff813ea910-ffffffff813ea95e: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81cc8697-ffffffff81cc86be: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff8143c690-ffffffff8143c6de: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_bin_file_mode_ns
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81e7b3e3-ffffffff81e7b417: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff814b7d10-ffffffff814b7d5d: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff8154f1f0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_bin_file_mode_ns
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8154f1f0-ffffffff8154f268: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff81586ec0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_bin_file_mode_ns
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81586ec0-ffffffff81586f38: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffff815bfa20)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_bin_file_mode_ns
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff815bfa20-ffffffff815bfac7: sysfs_warn_dup (STB_GLOBAL)
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
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffff8000104570c8)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffff8000104570c8-ffff800010457148: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (c06190bc)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c06190bc-c0619130: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (c000000000571410)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c000000000571410-c0000000005714c4: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/dir.c (ffffffe0002e8648)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffe0002e8648-ffffffe0002e86c4: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137fb4b-ffffffff8137fb72: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff8137f8d0-ffffffff8137f91e: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813705db-ffffffff81370602: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff81370360-ffffffff813703ae: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137d61b-ffffffff8137d642: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff8137d3a0-ffffffff8137d3ee: sysfs_warn_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void sysfs_warn_dup(struct kernfs_node *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/dir.c (0)
Location: fs/sysfs/dir.c:21
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_mode_ns
  - fs/sysfs/dir.c:sysfs_create_mount_point
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813910fb-ffffffff81391122: sysfs_warn_dup.cold (STB_LOCAL)
ffffffff81390e80-ffffffff81390ece: sysfs_warn_dup (STB_GLOBAL)
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
