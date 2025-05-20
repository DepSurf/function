# Function: <code>fuse_allow_current_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81314230)
Location: fs/fuse/dir.c:1013
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_listxattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
```
**Symbols:**

```
ffffffff81314230-ffffffff8131428c: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81348890)
Location: fs/fuse/dir.c:1018
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_listxattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
```
**Symbols:**

```
ffffffff81348890-ffffffff813488e8: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135e230)
Location: fs/fuse/dir.c:1032
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff8135e230-ffffffff8135e28b: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81372d20)
Location: fs/fuse/dir.c:1032
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff81372d20-ffffffff81372d7c: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813979e0)
Location: fs/fuse/dir.c:1028
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff813979e0-ffffffff81397a3d: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c6c40)
Location: fs/fuse/dir.c:1037
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff813c6c40-ffffffff813c6c9d: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813dfe10)
Location: fs/fuse/dir.c:1039
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff813dfe10-ffffffff813dfe6d: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140ba10)
Location: fs/fuse/dir.c:1026
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff8140ba10-ffffffff8140ba6b: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814254c0)
Location: fs/fuse/dir.c:1084
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff814254c0-ffffffff8142551b: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814737af)
Location: fs/fuse/dir.c:1084
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff81474bf0-ffffffff81474c4b: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148f5c0)
Location: fs/fuse/dir.c:1184
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff8148f5c0-ffffffff8148f61b: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81494fe0)
Location: fs/fuse/dir.c:1201
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff81494fe0-ffffffff8149503b: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814eca70)
Location: fs/fuse/dir.c:1149
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff814eca70-ffffffff814ecacb: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157b7c0)
Location: fs/fuse/dir.c:1229
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff8157b7c0-ffffffff8157b839: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:1266
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff82072685-ffffffff820726a0: fuse_allow_current_process.cold (STB_LOCAL)
ffffffff81621140-ffffffff816211e1: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:1332
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff820f2305-ffffffff820f2320: fuse_allow_current_process.cold (STB_LOCAL)
ffffffff81659590-ffffffff81659631: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:1433
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff821cf5b6-ffffffff821cf5d1: fuse_allow_current_process.cold (STB_LOCAL)
ffffffff81693280-ffffffff81693321: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010508c20)
Location: fs/fuse/dir.c:1084
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffff800010508c20-ffff800010508cc4: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c4bac)
Location: fs/fuse/dir.c:1084
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
c06c4bac-c06c4c4c: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064e6d0)
Location: fs/fuse/dir.c:1084
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
c00000000064e6d0-c00000000064e78c: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe0003747d2)
Location: fs/fuse/dir.c:1084
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffe0003747d2-ffffffe000374846: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141daa0)
Location: fs/fuse/dir.c:1084
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff8141daa0-ffffffff8141dafb: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140e520)
Location: fs/fuse/dir.c:1084
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff8140e520-ffffffff8140e57b: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81419c40)
Location: fs/fuse/dir.c:1084
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff81419c40-ffffffff81419c9b: fuse_allow_current_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fuse_allow_current_process(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814309b0)
Location: fs/fuse/dir.c:1084
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/xattr.c:fuse_listxattr
```
**Symbols:**

```
ffffffff814309b0-ffffffff81430a0b: fuse_allow_current_process (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
