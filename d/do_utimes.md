# Function: <code>do_utimes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81240e10)
Location: fs/utimes.c:136
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:SyS_utime
  - fs/utimes.c:SyS_utimensat
  - fs/utimes.c:SyS_utimes
  - fs/compat.c:compat_SyS_utime
  - fs/compat.c:compat_SyS_utimensat
  - fs/compat.c:compat_SyS_utimes
```
**Symbols:**

```
ffffffff81240e10-ffffffff81240f65: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81269140)
Location: fs/utimes.c:137
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:SyS_utimes
  - fs/utimes.c:SyS_utimensat
  - fs/utimes.c:SyS_utime
  - fs/compat.c:compat_SyS_utimes
  - fs/compat.c:compat_SyS_utimensat
  - fs/compat.c:compat_SyS_utime
```
**Symbols:**

```
ffffffff81269140-ffffffff81269296: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff8127c0f0)
Location: fs/utimes.c:122
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:SyS_utimes
  - fs/utimes.c:SyS_utimensat
  - fs/utimes.c:SyS_utime
  - fs/compat.c:compat_SyS_utimes
  - fs/compat.c:compat_SyS_utimensat
  - fs/compat.c:compat_SyS_utime
```
**Symbols:**

```
ffffffff8127c0f0-ffffffff8127c246: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81289410)
Location: fs/utimes.c:118
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:compat_SyS_utimes
  - fs/utimes.c:compat_SyS_utimensat
  - fs/utimes.c:compat_SyS_utime
  - fs/utimes.c:SyS_utimes
  - fs/utimes.c:SyS_utimensat
  - fs/utimes.c:SyS_utime
```
**Symbols:**

```
ffffffff81289410-ffffffff8128955f: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812abf30)
Location: fs/utimes.c:119
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:compat_SyS_utimes
  - fs/utimes.c:compat_SyS_utimensat
  - fs/utimes.c:compat_SyS_utime
  - fs/utimes.c:SyS_utimes
  - fs/utimes.c:SyS_utimensat
  - fs/utimes.c:SyS_utime
```
**Symbols:**

```
ffffffff812abf30-ffffffff812ac07f: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812d2c10)
Location: fs/utimes.c:119
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__x32_compat_sys_utimensat
  - fs/utimes.c:__ia32_compat_sys_utimensat
  - fs/utimes.c:__x32_compat_sys_utime
  - fs/utimes.c:__ia32_compat_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
```
**Symbols:**

```
ffffffff812d2c10-ffffffff812d2d7d: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812e7ff0)
Location: fs/utimes.c:90
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__x32_compat_sys_utimensat
  - fs/utimes.c:__ia32_compat_sys_utimensat
  - fs/utimes.c:__x32_compat_sys_utime
  - fs/utimes.c:__ia32_compat_sys_utime
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff812e7ff0-ffffffff812e815d: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81306900)
Location: fs/utimes.c:90
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff81306900-ffffffff81306a5f: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81319960)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff81319960-ffffffff81319abf: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81353900)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff81353900-ffffffff81353a5d: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81360230)
Location: fs/utimes.c:138
Inline: False
Direct callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff81360230-ffffffff8136034f: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81366cd0)
Location: fs/utimes.c:139
Inline: False
Direct callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff81366cd0-ffffffff81366def: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff813b5820)
Location: fs/utimes.c:139
Inline: False
Direct callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff813b5820-ffffffff813b593f: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff8143ab50)
Location: fs/utimes.c:139
Inline: False
Direct callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff8143ab50-ffffffff8143aca9: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff814c9010)
Location: fs/utimes.c:139
Inline: False
Direct callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff814c9010-ffffffff814c9169: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff814ff250)
Location: fs/utimes.c:140
Inline: False
Direct callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff814ff250-ffffffff814ff3ac: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81533e80)
Location: fs/utimes.c:140
Inline: False
Direct callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff81533e80-ffffffff81533fc8: do_utimes (STB_GLOBAL)
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
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffff8000103d0920)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__arm64_sys_utimensat_time32
  - fs/utimes.c:__arm64_sys_utime32
  - fs/utimes.c:__arm64_sys_utimensat
```
**Symbols:**

```
ffff8000103d0920-ffff8000103d0ac8: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c05abcb0)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__se_sys_utimensat_time32
  - fs/utimes.c:__se_sys_utime32
  - fs/utimes.c:__se_sys_utimensat
```
**Symbols:**

```
c05abcb0-c05abe10: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c0000000004d32a0)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__se_sys_utimensat_time32
  - fs/utimes.c:__se_sys_utime32
  - fs/utimes.c:__se_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__se_sys_utimensat
```
**Symbols:**

```
c0000000004d32a0-c0000000004d34d0: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffe00028cb2e)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:__se_sys_utimensat
```
**Symbols:**

```
ffffffe00028cb2e-ffffffe00028cc68: do_utimes (STB_GLOBAL)
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
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81311f40)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff81311f40-ffffffff8131209f: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81302b50)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff81302b50-ffffffff81302caf: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff8130fd30)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff8130fd30-ffffffff8130fe8f: do_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char *filename, struct timespec64 *times, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81321530)
Location: fs/utimes.c:88
Inline: False
Direct callers:
  - init/initramfs.c:do_utime
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
  - fs/utimes.c:__ia32_sys_utime
  - fs/utimes.c:__x64_sys_utime
  - fs/utimes.c:do_futimesat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
```
**Symbols:**

```
ffffffff81321530-ffffffff8132168f: do_utimes (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *times</code> ➡️ <code>struct timespec64 *times</code>
</li>
</ul>
</details>
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
