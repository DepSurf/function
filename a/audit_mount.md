# Function: <code>audit_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_mount(struct aa_profile *profile, const char *op, const char *name, const char *src_name, const char *type, const char *trans, long unsigned int flags, const void *data, u32 request, struct aa_perms *perms, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8138e560)
Location: security/apparmor/mount.c:133
Inline: False
Direct callers:
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8138e560-ffffffff8138e6bc: audit_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_mount(struct aa_profile *profile, const char *op, const char *name, const char *src_name, const char *type, const char *trans, long unsigned int flags, const void *data, u32 request, struct aa_perms *perms, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813c94f0)
Location: security/apparmor/mount.c:133
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff813c94f0-ffffffff813c9646: audit_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_mount(struct aa_profile *profile, const char *op, const char *name, const char *src_name, const char *type, const char *trans, long unsigned int flags, const void *data, u32 request, struct aa_perms *perms, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e0b60)
Location: security/apparmor/mount.c:133
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff813e0b60-ffffffff813e0cb6: audit_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff813efea0)
Location: security/apparmor/mount.c:133
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff813efea0-ffffffff813f0007: audit_mount.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff81417de0)
Location: security/apparmor/mount.c:133
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff81417de0-ffffffff81417f47: audit_mount.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff8144a270)
Location: security/apparmor/mount.c:133
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8144a270-ffffffff8144a3d3: audit_mount.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff814671e0)
Location: security/apparmor/mount.c:134
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814671e0-ffffffff81467343: audit_mount.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff81494270)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff81494270-ffffffff814943d7: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff814ae1a0)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814ae1a0-ffffffff814ae307: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150d100)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8150d100-ffffffff8150d265: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff81529f70)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff81529f70-ffffffff8152a0d5: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff81530360)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff81530360-ffffffff815304c5: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158e780)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8158e780-ffffffff8158e8e5: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff8162f840)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8162f840-ffffffff8162f9e1: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e4460)
Location: security/apparmor/mount.c:132
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff816e4460-ffffffff816e45e9: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171dab0)
Location: security/apparmor/mount.c:132
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8171dab0-ffffffff8171dc39: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175c500)
Location: security/apparmor/mount.c:132
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8175c500-ffffffff8175c689: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a5900)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffff8000105a5900-ffff8000105a5a9c: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (c075589c)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
c075589c-c0755a54: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (c0000000007217e0)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
c0000000007217e0-c000000000721a34: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003ef538)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffe0003ef538-ffffffe0003ef686: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a6780)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814a6780-ffffffff814a68e7: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff814971a0)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814971a0-ffffffff81497307: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a2820)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814a2820-ffffffff814a2987: audit_mount.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bafe0)
Location: security/apparmor/mount.c:130
Inline: True
Direct callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814bafe0-ffffffff814bb147: audit_mount.constprop.0 (STB_LOCAL)
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
</ul>
