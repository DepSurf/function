# Function: <code>getname_uflags</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_uflags(const char *filename, int uflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81388283)
Location: fs/namei.c:207
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
Direct callers:
  - fs/exec.c:__x64_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff813864f0-ffffffff81386547: getname_uflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_uflags(const char *filename, int uflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814091e3)
Location: fs/namei.c:208
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
Direct callers:
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff81407130-ffffffff8140719b: getname_uflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_uflags(const char *filename, int uflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81493853)
Location: fs/namei.c:208
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
Direct callers:
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff814914e0-ffffffff8149154b: getname_uflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_uflags(const char *filename, int uflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c8893)
Location: fs/namei.c:209
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
Direct callers:
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff814c6a80-ffffffff814c6aeb: getname_uflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct filename *getname_uflags(const char *filename, int uflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fb143)
Location: fs/namei.c:209
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
Direct callers:
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - io_uring/fs.c:io_linkat_prep
```
**Symbols:**

```
ffffffff814f93d0-ffffffff814f943b: getname_uflags (STB_GLOBAL)
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
