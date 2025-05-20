# Function: <code>ksys_getdents64</code>

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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812b1490)
Location: fs/readdir.c:295
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
```
**Symbols:**

```
ffffffff812b1490-ffffffff812b15b7: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812c66e0)
Location: fs/readdir.c:295
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
```
**Symbols:**

```
ffffffff812c66e0-ffffffff812c680a: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812e31b0)
Location: fs/readdir.c:295
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
```
**Symbols:**

```
ffffffff812e31b0-ffffffff812e32e0: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812f4c30)
Location: fs/readdir.c:353
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
```
**Symbols:**

```
ffffffff812f4c30-ffffffff812f4d65: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8132d2b0)
Location: fs/readdir.c:351
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
```
**Symbols:**

```
ffffffff8132d2b0-ffffffff8132d3b1: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffff8000103a1918)
Location: fs/readdir.c:353
Inline: False
Direct callers:
  - fs/readdir.c:__arm64_sys_getdents64
```
**Symbols:**

```
ffff8000103a1918-ffff8000103a1bb0: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (c0584880)
Location: fs/readdir.c:353
Inline: False
Direct callers:
  - fs/readdir.c:__se_sys_getdents64
```
**Symbols:**

```
c0584880-c05849f0: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (c00000000049b580)
Location: fs/readdir.c:353
Inline: False
Direct callers:
  - fs/readdir.c:__se_sys_getdents64
```
**Symbols:**

```
c00000000049b580-c00000000049b75c: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffe00026a52c)
Location: fs/readdir.c:353
Inline: False
Direct callers:
  - fs/readdir.c:__se_sys_getdents64
```
**Symbols:**

```
ffffffe00026a52c-ffffffe00026a616: ksys_getdents64 (STB_GLOBAL)
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812ed210)
Location: fs/readdir.c:353
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
```
**Symbols:**

```
ffffffff812ed210-ffffffff812ed345: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812dde40)
Location: fs/readdir.c:353
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
```
**Symbols:**

```
ffffffff812dde40-ffffffff812ddf75: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812eb020)
Location: fs/readdir.c:353
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
```
**Symbols:**

```
ffffffff812eb020-ffffffff812eb155: ksys_getdents64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 *dirent, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812fc010)
Location: fs/readdir.c:353
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
```
**Symbols:**

```
ffffffff812fc010-ffffffff812fc145: ksys_getdents64 (STB_GLOBAL)
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
