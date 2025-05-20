# Function: <code>build_open_how</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct open_how build_open_how(int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130fc5f)
Location: fs/open.c:990
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
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
```
**Symbols:**

```
ffffffff8130f7d0-ffffffff8130f81f: build_open_how (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct open_how build_open_how(int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131bf1f)
Location: fs/open.c:979
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
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff8131ba80-ffffffff8131bacf: build_open_how (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct open_how build_open_how(int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8132208f)
Location: fs/open.c:987
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
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff81321bd0-ffffffff81321c1f: build_open_how (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct open_how build_open_how(int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136f57f)
Location: fs/open.c:1005
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
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff8136f0b0-ffffffff8136f0ff: build_open_how (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct open_how build_open_how(int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ee05f)
Location: fs/open.c:1070
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
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - io_uring/io_uring.c:io_openat_prep
```
**Symbols:**

```
ffffffff813eda70-ffffffff813edad8: build_open_how (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct open_how build_open_how(int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8147682f)
Location: fs/open.c:1102
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
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - io_uring/openclose.c:io_openat_prep
```
**Symbols:**

```
ffffffff814761d0-ffffffff81476238: build_open_how (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct open_how build_open_how(int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814ab19f)
Location: fs/open.c:1191
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
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - io_uring/openclose.c:io_openat_prep
```
**Symbols:**

```
ffffffff814aab00-ffffffff814aab68: build_open_how (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct open_how build_open_how(int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814dc63f)
Location: fs/open.c:1188
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
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - io_uring/openclose.c:io_openat_prep
```
**Symbols:**

```
ffffffff814dbfa0-ffffffff814dc008: build_open_how (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
