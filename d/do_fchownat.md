# Function: <code>do_fchownat</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812966e0)
Location: fs/open.c:657
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff812966e0-ffffffff812967c6: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab4d0)
Location: fs/open.c:646
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff812ab4d0-ffffffff812ab5b6: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c7cd0)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff812c7cd0-ffffffff812c7db6: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d96e0)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff812d96e0-ffffffff812d97c6: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130f4a0)
Location: fs/open.c:695
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff8130f4a0-ffffffff8130f586: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131b6d0)
Location: fs/open.c:685
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff8131b6d0-ffffffff8131b7b6: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81321820)
Location: fs/open.c:693
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff81321820-ffffffff81321906: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136ed00)
Location: fs/open.c:690
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff8136ed00-ffffffff8136ede6: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ed5d0)
Location: fs/open.c:715
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff813ed5d0-ffffffff813ed6d8: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81475c70)
Location: fs/open.c:747
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff81475c70-ffffffff81475d78: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814aa590)
Location: fs/open.c:779
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff814aa590-ffffffff814aa698: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814dba30)
Location: fs/open.c:799
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff814dba30-ffffffff814dbb3a: do_fchownat (STB_GLOBAL)
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
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037ea50)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__arm64_sys_lchown16
  - kernel/uid16.c:__arm64_sys_chown16
  - fs/open.c:__arm64_sys_lchown
  - fs/open.c:__arm64_sys_chown
  - fs/open.c:__arm64_sys_fchownat
```
**Symbols:**

```
ffff80001037ea50-ffff80001037eb5c: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c05693c0)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__se_sys_lchown16
  - kernel/uid16.c:__se_sys_chown16
  - fs/open.c:__se_sys_lchown
  - fs/open.c:__se_sys_chown
  - fs/open.c:__se_sys_fchownat
```
**Symbols:**

```
c05693c0-c05694bc: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0000000004746c0)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_lchown
  - fs/open.c:__se_sys_chown
  - fs/open.c:__se_sys_fchownat
```
**Symbols:**

```
c0000000004746c0-c00000000047485c: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe0002546ca)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_lchown
  - fs/open.c:__se_sys_chown
  - fs/open.c:__se_sys_fchownat
```
**Symbols:**

```
ffffffe0002546ca-ffffffe0002547a8: do_fchownat (STB_GLOBAL)
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
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1cc0)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff812d1cc0-ffffffff812d1da6: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2940)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff812c2940-ffffffff812c2a26: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cfad0)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff812cfad0-ffffffff812cfbb6: do_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_fchownat(int dfd, const char *filename, uid_t user, gid_t group, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e08e0)
Location: fs/open.c:666
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
  - fs/open.c:__ia32_sys_lchown
  - fs/open.c:__x64_sys_lchown
  - fs/open.c:__ia32_sys_chown
  - fs/open.c:__x64_sys_chown
  - fs/open.c:__ia32_sys_fchownat
  - fs/open.c:__x64_sys_fchownat
```
**Symbols:**

```
ffffffff812e08e0-ffffffff812e09c6: do_fchownat (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
