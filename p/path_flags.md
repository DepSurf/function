# Function: <code>path_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int path_flags(struct aa_profile *profile, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8138e4d0)
Location: security/apparmor/mount.c:333
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8138e4d0-ffffffff8138e553: path_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int path_flags(struct aa_profile *profile, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813c9460)
Location: security/apparmor/mount.c:296
Inline: False
Direct callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff813c9460-ffffffff813c94e3: path_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int path_flags(struct aa_profile *profile, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e0ad0)
Location: security/apparmor/mount.c:296
Inline: False
Direct callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff813e0ad0-ffffffff813e0b53: path_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813f052c)
Location: security/apparmor/mount.c:296
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814184aa)
Location: security/apparmor/mount.c:295
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8144a941)
Location: security/apparmor/mount.c:295
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814678b1)
Location: security/apparmor/mount.c:296
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81494921)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814ae851)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150da41)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152a8b1)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81530b12)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158ef52)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8162ff14)
Location: security/apparmor/mount.c:275
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e4b95)
Location: security/apparmor/mount.c:279
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171e1f8)
Location: security/apparmor/mount.c:279
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175cc26)
Location: security/apparmor/mount.c:279
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a5f80)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c0755f08)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c000000000722074)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003efabe)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a6e31)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81497851)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a2ed1)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bb691)
Location: security/apparmor/mount.c:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
