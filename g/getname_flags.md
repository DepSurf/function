# Function: <code>getname_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121be40)
Location: fs/namei.c:125
Inline: True
Direct callers:
  - fs/exec.c:SyS_execveat
  - fs/exec.c:compat_SyS_execveat
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
```
**Symbols:**

```
ffffffff8121be40-ffffffff8121c02e: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812432c0)
Location: fs/namei.c:127
Inline: True
Direct callers:
  - fs/exec.c:compat_SyS_execveat
  - fs/exec.c:SyS_execveat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
```
**Symbols:**

```
ffffffff812432c0-ffffffff812434a1: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81256240)
Location: fs/namei.c:127
Inline: True
Direct callers:
  - fs/exec.c:compat_SyS_execveat
  - fs/exec.c:SyS_execveat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
```
**Symbols:**

```
ffffffff81256240-ffffffff81256421: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812623d0)
Location: fs/namei.c:127
Inline: True
Direct callers:
  - fs/exec.c:compat_SyS_execveat
  - fs/exec.c:SyS_execveat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
```
**Symbols:**

```
ffffffff812623d0-ffffffff812625b1: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81284c20)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:compat_SyS_execveat
  - fs/exec.c:SyS_execveat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_unlink
  - fs/namei.c:SyS_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
```
**Symbols:**

```
ffffffff81284c20-ffffffff81284e01: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812abd80)
Location: fs/namei.c:129
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
```
**Symbols:**

```
ffffffff812abd80-ffffffff812abf60: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c0e80)
Location: fs/namei.c:129
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
```
**Symbols:**

```
ffffffff812c0e80-ffffffff812c1060: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dd650)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812dd650-ffffffff812dd834: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ef180)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812ef180-ffffffff812ef364: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81329210)
Location: fs/namei.c:128
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81327140-ffffffff813272e3: getname_flags.part.0 (STB_LOCAL)
ffffffff813272f0-ffffffff8132734b: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81334580)
Location: fs/namei.c:128
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:do_mkdirat
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81332550-ffffffff813326f3: getname_flags.part.0 (STB_LOCAL)
ffffffff81332700-ffffffff8133275b: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff8133a660)
Location: fs/namei.c:128
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:do_mkdirat
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff813385a0-ffffffff8133874c: getname_flags.part.0 (STB_LOCAL)
ffffffff81338750-ffffffff813387ab: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81387bf0)
Location: fs/namei.c:128
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__x64_sys_mknod
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81386290-ffffffff8138643c: getname_flags.part.0 (STB_LOCAL)
ffffffff81386440-ffffffff8138649b: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81408aad)
Location: fs/namei.c:129
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__x64_sys_mknod
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_fstatat
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__do_sys_fsconfig
  - io_uring/io_uring.c:io_statx_prep
```
**Symbols:**

```
ffffffff81406eb0-ffffffff8140705d: getname_flags.part.0 (STB_LOCAL)
ffffffff81407060-ffffffff814070cc: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff8149307d)
Location: fs/namei.c:129
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__x64_sys_mknod
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_fstatat
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__do_sys_fsconfig
  - io_uring/xattr.c:io_setxattr_prep
  - io_uring/xattr.c:io_getxattr_prep
  - io_uring/statx.c:io_statx_prep
```
**Symbols:**

```
ffffffff81491230-ffffffff814913dd: getname_flags.part.0 (STB_LOCAL)
ffffffff814913f0-ffffffff8149145c: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff814c80cd)
Location: fs/namei.c:130
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__x64_sys_mknod
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_fstatat
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__do_sys_fsconfig
  - io_uring/xattr.c:io_setxattr_prep
  - io_uring/xattr.c:io_getxattr_prep
  - io_uring/statx.c:io_statx_prep
```
**Symbols:**

```
ffffffff814bfc60-ffffffff814bfe0d: getname_flags.part.0 (STB_LOCAL)
ffffffff814c6870-ffffffff814c68dc: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff814fa96d)
Location: fs/namei.c:130
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__x64_sys_mknod
Direct callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:user_path_locked_at
  - fs/fsopen.c:__do_sys_fsconfig
  - io_uring/xattr.c:io_setxattr_prep
  - io_uring/xattr.c:io_getxattr_prep
  - io_uring/statx.c:io_statx_prep
```
**Symbols:**

```
ffffffff814f2150-ffffffff814f232c: getname_flags.part.0 (STB_LOCAL)
ffffffff814f9160-ffffffff814f91cc: getname_flags (STB_GLOBAL)
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
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010398938)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__arm64_compat_sys_execveat
  - fs/exec.c:__arm64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__arm64_sys_unlink
  - fs/namei.c:__arm64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__arm64_sys_fsconfig
```
**Symbols:**

```
ffff800010398938-ffff800010398b10: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057f004)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__se_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__se_sys_unlink
  - fs/namei.c:__se_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c057f004-c057f1c0: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000492db0)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__se_compat_sys_execveat
  - fs/exec.c:__se_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__se_sys_unlink
  - fs/namei.c:__se_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c000000000492db0-c000000000493034: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000266594)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__se_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__se_sys_unlink
  - fs/namei.c:__se_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
ffffffe000266594-ffffffe000266716: getname_flags (STB_GLOBAL)
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
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7760)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812e7760-ffffffff812e7944: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d83a0)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812d83a0-ffffffff812d8584: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5570)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812e5570-ffffffff812e5754: getname_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_flags(const char *filename, int flags, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f64f0)
Location: fs/namei.c:128
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:user_path_mountpoint_at
  - fs/namei.c:user_path_at_empty
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812f64f0-ffffffff812f66d4: getname_flags (STB_GLOBAL)
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
