# Function: <code>do_sys_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120b6a0)
Location: fs/open.c:1015
Inline: False
Direct callers:
  - fs/open.c:SyS_openat
  - fs/open.c:SyS_creat
  - fs/compat.c:compat_SyS_open
  - fs/compat.c:compat_SyS_openat
```
**Symbols:**

```
ffffffff8120b6a0-ffffffff8120b932: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812313d0)
Location: fs/open.c:1026
Inline: False
Direct callers:
  - fs/open.c:SyS_creat
  - fs/open.c:SyS_openat
  - fs/compat.c:compat_SyS_openat
  - fs/compat.c:compat_SyS_open
```
**Symbols:**

```
ffffffff812313d0-ffffffff8123164a: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81243980)
Location: fs/open.c:1043
Inline: False
Direct callers:
  - fs/open.c:SyS_creat
  - fs/open.c:SyS_openat
  - fs/compat.c:compat_SyS_openat
  - fs/compat.c:compat_SyS_open
```
**Symbols:**

```
ffffffff81243980-ffffffff81243bfa: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124f120)
Location: fs/open.c:1049
Inline: False
Direct callers:
  - fs/open.c:SyS_creat
  - fs/open.c:compat_SyS_openat
  - fs/open.c:compat_SyS_open
  - fs/open.c:SyS_openat
```
**Symbols:**

```
ffffffff8124f120-ffffffff8124f3cf: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812710a0)
Location: fs/open.c:1049
Inline: False
Direct callers:
  - fs/open.c:SyS_creat
  - fs/open.c:compat_SyS_openat
  - fs/open.c:compat_SyS_open
  - fs/open.c:SyS_openat
```
**Symbols:**

```
ffffffff812710a0-ffffffff81271351: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81296d00)
Location: fs/open.c:1091
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff81296d00-ffffffff81296f69: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab9a0)
Location: fs/open.c:1058
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff812ab9a0-ffffffff812abc20: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c81a0)
Location: fs/open.c:1078
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff812c81a0-ffffffff812c842d: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d9bb0)
Location: fs/open.c:1083
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff812d9bb0-ffffffff812d9e3d: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130fc5f)
Location: fs/open.c:1193
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
Direct callers:
  - init/main.c:console_on_rootfs
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff813103f0-ffffffff81310463: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131bf1f)
Location: fs/open.c:1186
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff8131c6b0-ffffffff8131c723: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8132208f)
Location: fs/open.c:1208
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff81322820-ffffffff81322893: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136f57f)
Location: fs/open.c:1226
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x64_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x64_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff8136fd10-ffffffff8136fd83: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ee05f)
Location: fs/open.c:1291
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff813ee690-ffffffff813ee712: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8147682f)
Location: fs/open.c:1323
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff81476ef0-ffffffff81476f72: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814ab19f)
Location: fs/open.c:1419
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff814ab840-ffffffff814ab8c2: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814dc63f)
Location: fs/open.c:1416
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff814dcce0-ffffffff814dcd62: do_sys_open (STB_GLOBAL)
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
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037ef40)
Location: fs/open.c:1083
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__arm64_sys_creat
  - fs/open.c:__arm64_compat_sys_openat
  - fs/open.c:__arm64_compat_sys_open
  - fs/open.c:__arm64_sys_openat
  - fs/open.c:__arm64_sys_open
```
**Symbols:**

```
ffff80001037ef40-ffff80001037f1ec: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0569828)
Location: fs/open.c:1083
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_creat
  - fs/open.c:__se_sys_openat
  - fs/open.c:__se_sys_open
```
**Symbols:**

```
c0569828-c0569ad4: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474d80)
Location: fs/open.c:1083
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_creat
  - fs/open.c:__se_compat_sys_openat
  - fs/open.c:__se_compat_sys_open
  - fs/open.c:__se_sys_openat
  - fs/open.c:__se_sys_open
```
**Symbols:**

```
c000000000474d80-c000000000475190: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254b30)
Location: fs/open.c:1083
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_creat
  - fs/open.c:__se_sys_openat
  - fs/open.c:__se_sys_open
```
**Symbols:**

```
ffffffe000254b30-ffffffe000254d84: do_sys_open (STB_GLOBAL)
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
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d2190)
Location: fs/open.c:1083
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff812d2190-ffffffff812d241d: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2e10)
Location: fs/open.c:1083
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff812c2e10-ffffffff812c309d: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cffa0)
Location: fs/open.c:1083
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff812cffa0-ffffffff812d022d: do_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e0db0)
Location: fs/open.c:1083
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff812e0db0-ffffffff812e1056: do_sys_open (STB_GLOBAL)
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
