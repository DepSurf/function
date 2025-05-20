# Function: <code>vfs_statx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812567e0)
Location: fs/stat.c:165
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
  - fs/stat.c:C_SYSC_newfstatat
  - fs/stat.c:C_SYSC_newlstat
  - fs/stat.c:C_SYSC_newstat
  - fs/stat.c:SYSC_statx
  - fs/stat.c:SYSC_newfstatat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_stat
```
**Symbols:**

```
ffffffff812567e0-ffffffff812568b5: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81278a30)
Location: fs/stat.c:166
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
  - fs/stat.c:C_SYSC_newfstatat
  - fs/stat.c:C_SYSC_newlstat
  - fs/stat.c:C_SYSC_newstat
  - fs/stat.c:SYSC_statx
  - fs/stat.c:SYSC_newfstatat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_stat
```
**Symbols:**

```
ffffffff81278a30-ffffffff81278b05: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f380)
Location: fs/stat.c:166
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff8129f380-ffffffff8129f455: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4360)
Location: fs/stat.c:166
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812b4360-ffffffff812b4435: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d10d0)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812d10d0-ffffffff812d11ad: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e2c60)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812e2c60-ffffffff812e2d3d: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131a780)
Location: fs/stat.c:192
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:do_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff8131a780-ffffffff8131a89d: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81325e10)
Location: fs/stat.c:166
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:do_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff81325e10-ffffffff81325f2d: vfs_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132bf20)
Location: fs/stat.c:184
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:do_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff8132bf20-ffffffff8132c03d: vfs_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379690)
Location: fs/stat.c:202
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:do_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff81379690-ffffffff813797ad: vfs_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_statx(int dfd, struct filename *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f8cc0)
Location: fs/stat.c:216
Inline: False
Direct callers:
  - fs/stat.c:do_statx
  - fs/stat.c:vfs_fstatat
```
**Symbols:**

```
ffffffff813f8cc0-ffffffff813f8e08: vfs_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_statx(int dfd, struct filename *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814822b0)
Location: fs/stat.c:220
Inline: False
Direct callers:
  - fs/stat.c:do_statx
  - fs/stat.c:vfs_fstatat
```
**Symbols:**

```
ffffffff814822b0-ffffffff8148242b: vfs_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_statx(int dfd, struct filename *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b6ec0)
Location: fs/stat.c:226
Inline: False
Direct callers:
  - fs/stat.c:do_statx
  - fs/stat.c:vfs_fstatat
```
**Symbols:**

```
ffffffff814b6ec0-ffffffff814b703b: vfs_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_statx(int dfd, struct filename *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e91f0)
Location: fs/stat.c:232
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:do_statx
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff814e91f0-ffffffff814e93b2: vfs_statx (STB_LOCAL)
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
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038a658)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_fstatat64
  - fs/stat.c:__do_sys_lstat64
  - fs/stat.c:__do_sys_stat64
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffff80001038a658-ffff80001038a758: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c057280c)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_fstatat64
  - fs/stat.c:__do_sys_lstat64
  - fs/stat.c:__do_sys_stat64
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
c057280c-c05728fc: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0000000004818e0)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_fstatat64
  - fs/stat.c:__do_sys_lstat64
  - fs/stat.c:__do_sys_stat64
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
c0000000004818e0-c000000000481a6c: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c572)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
```
**Symbols:**

```
ffffffe00025c572-ffffffe00025c63c: vfs_statx (STB_GLOBAL)
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
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db240)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812db240-ffffffff812db31d: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cbec0)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812cbec0-ffffffff812cbf9d: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9050)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812d9050-ffffffff812d912d: vfs_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_statx(int dfd, const char *filename, int flags, struct kstat *stat, u32 request_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e9f60)
Location: fs/stat.c:168
Inline: False
Direct callers:
  - init/do_mounts_md.c:bstat
  - init/initramfs.c:clean_path
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_statx
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff812e9f60-ffffffff812ea03d: vfs_statx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char *filename</code> ➡️ <code>struct filename *filename</code>
</li>
</ul>
</details>
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
