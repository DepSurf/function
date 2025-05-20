# Function: <code>aa_path_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81388410)
Location: security/apparmor/file.c:312
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
ffffffff81388410-ffffffff8138853a: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813c3010)
Location: security/apparmor/file.c:332
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff813c3010-ffffffff813c3143: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813da520)
Location: security/apparmor/file.c:332
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff813da520-ffffffff813da653: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813eb660)
Location: security/apparmor/file.c:335
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
ffffffff813eb660-ffffffff813eb790: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81412fa0)
Location: security/apparmor/file.c:329
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
ffffffff81412fa0-ffffffff814130d0: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81445330)
Location: security/apparmor/file.c:329
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81445330-ffffffff8144545b: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81462220)
Location: security/apparmor/file.c:330
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81462220-ffffffff8146234b: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8148f4f0)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff8148f4f0-ffffffff8148f616: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814a93b0)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814a93b0-ffffffff814a94d6: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81506d80)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
```
**Symbols:**

```
ffffffff81506d80-ffffffff81506efc: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81523e70)
Location: security/apparmor/file.c:315
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
```
**Symbols:**

```
ffffffff81523e70-ffffffff81523fec: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8152a060)
Location: security/apparmor/file.c:317
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff8152a060-ffffffff8152a1d5: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81588400)
Location: security/apparmor/file.c:317
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff81588400-ffffffff81588575: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81628a10)
Location: security/apparmor/file.c:276
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff81628a10-ffffffff81628b6a: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_path_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff816dd200)
Location: security/apparmor/file.c:403
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff816dd200-ffffffff816dd3bd: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_path_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81716810)
Location: security/apparmor/file.c:423
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff81716810-ffffffff817169cd: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_path_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff817552e0)
Location: security/apparmor/file.c:430
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff817552e0-ffffffff817554b5: aa_path_perm (STB_GLOBAL)
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
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffff80001059fd48)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffff80001059fd48-ffff80001059fe78: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (c07509c4)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
c07509c4-c0750afc: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (c000000000719dd0)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
c000000000719dd0-c000000000719f74: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffe0003eae8c)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
ffffffe0003eae8c-ffffffe0003eaf8a: aa_path_perm (STB_GLOBAL)
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
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814a1990)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814a1990-ffffffff814a1ab6: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814923b0)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814923b0-ffffffff814924d6: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8149da30)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff8149da30-ffffffff8149db56: aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_path_perm(const char *op, struct aa_label *label, const struct path *path, int flags, u32 request, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814b5fd0)
Location: security/apparmor/file.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814b5fd0-ffffffff814b610d: aa_path_perm (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, label, path, flags, request, cond</code> ➡️ <code>op, subj_cred, label, path, flags, request, cond</code>
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
