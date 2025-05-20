# Function: <code>match_mnt_path_str</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813c9b20)
Location: security/apparmor/mount.c:319
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff813c9b20-ffffffff813c9f8a: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e1190)
Location: security/apparmor/mount.c:319
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff813e1190-ffffffff813e1601: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813f0010)
Location: security/apparmor/mount.c:319
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff813f0010-ffffffff813f03b2: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81417f50)
Location: security/apparmor/mount.c:318
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff81417f50-ffffffff8141831b: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8144a3e0)
Location: security/apparmor/mount.c:318
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff8144a3e0-ffffffff8144a79b: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81467350)
Location: security/apparmor/mount.c:319
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff81467350-ffffffff8146770b: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814943e0)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff814943e0-ffffffff8149476b: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814ae310)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff814ae310-ffffffff814ae69b: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150d710)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff8150d710-ffffffff8150d899: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152a580)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff8152a580-ffffffff8152a709: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff815307f0)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff815307f0-ffffffff81530979: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158ec10)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff8158ec10-ffffffff8158edb8: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8162f9f0)
Location: security/apparmor/mount.c:298
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff8162f9f0-ffffffff8162fbc0: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int match_mnt_path_str(const struct cred *subj_cred, struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e4600)
Location: security/apparmor/mount.c:303
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff816e4600-ffffffff816e47d9: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int match_mnt_path_str(const struct cred *subj_cred, struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171dc50)
Location: security/apparmor/mount.c:303
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff8171dc50-ffffffff8171de2b: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int match_mnt_path_str(const struct cred *subj_cred, struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175c6a0)
Location: security/apparmor/mount.c:303
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff8175c6a0-ffffffff8175c87b: match_mnt_path_str (STB_LOCAL)
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
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a5aa0)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffff8000105a5aa0-ffff8000105a5de4: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c0755a54)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
c0755a54-c0755d90: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c000000000721a40)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
c000000000721a40-c000000000721e60: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003ef686)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffe0003ef686-ffffffe0003ef99c: match_mnt_path_str (STB_LOCAL)
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
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a68f0)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff814a68f0-ffffffff814a6c7b: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81497310)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff81497310-ffffffff8149769b: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a2990)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff814a2990-ffffffff814a2d1b: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile *profile, const struct path *mntpath, char *buffer, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, const char *devinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bb150)
Location: security/apparmor/mount.c:315
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:match_mnt
```
**Symbols:**

```
ffffffff814bb150-ffffffff814bb4db: match_mnt_path_str (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, mntpath, buffer, devname, type, flags, data, binary, devinfo</code> ➡️ <code>subj_cred, profile, mntpath, buffer, devname, type, flags, data, binary, devinfo</code>
</li>
</ul>
</details>
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
