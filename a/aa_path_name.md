# Function: <code>aa_path_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_path_name(struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff81379820)
Location: security/apparmor/path.c:201
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/file.c:path_name
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
ffffffff81379820-ffffffff81379ba9: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff813b25d0)
Location: security/apparmor/path.c:201
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff813b25d0-ffffffff813b29a5: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff813c9790)
Location: security/apparmor/path.c:201
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff813c9790-ffffffff813c9b65: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff813dee50)
Location: security/apparmor/path.c:201
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff813dee50-ffffffff813df21a: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff814057f0)
Location: security/apparmor/path.c:201
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814057f0-ffffffff81405b50: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff81436da0)
Location: security/apparmor/path.c:201
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff81436da0-ffffffff8143713f: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff81453a00)
Location: security/apparmor/path.c:201
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff81453a00-ffffffff81453d9f: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff81481670)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff81481670-ffffffff81481714: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff8149b3a0)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8149b3a0-ffffffff8149b444: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff814f3e00)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814f3e00-ffffffff814f3ea4: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff81510f60)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff81510f60-ffffffff81511004: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff815178e0)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff815178e0-ffffffff81517984: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff815758e0)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff815758e0-ffffffff81575984: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff816133c0)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff816133c0-ffffffff81613474: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff816c6020)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff816c6020-ffffffff816c60d4: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff816fedf0)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff816fedf0-ffffffff816feea4: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff8173c380)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8173c380-ffffffff8173c434: aa_path_name (STB_GLOBAL)
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
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffff800010591680)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffff800010591680-ffff800010591774: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (c07422f4)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
c07422f4-c07423c4: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (c000000000705340)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
c000000000705340-c000000000705448: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffe0003deff6)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffe0003deff6-ffffffe0003df09a: aa_path_name (STB_GLOBAL)
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
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff81493980)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff81493980-ffffffff81493a24: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff814843a0)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814843a0-ffffffff81484444: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff8148fa20)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8148fa20-ffffffff8148fac4: aa_path_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_path_name(const struct path *path, int flags, char *buffer, const char **name, const char **info, const char *disconnected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/path.c (ffffffff814a7930)
Location: security/apparmor/path.c:197
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814a7930-ffffffff814a79d4: aa_path_name (STB_GLOBAL)
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
