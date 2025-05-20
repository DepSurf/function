# Function: <code>path_noexec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81211ff0)
Location: fs/exec.c:103
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:SyS_access
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff81211ff0-ffffffff81212017: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81238c04)
Location: fs/exec.c:104
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:SyS_access
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff81238ac0-ffffffff81238ae7: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124b8b4)
Location: fs/exec.c:104
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:SyS_access
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff8124b770-ffffffff8124b797: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812579ae)
Location: fs/exec.c:109
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:SyS_access
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff812578a0-ffffffff812578c7: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81279c7e)
Location: fs/exec.c:109
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:SyS_access
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff81279af0-ffffffff81279b17: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a085a)
Location: fs/exec.c:109
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff812a06d0-ffffffff812a06f7: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b583e)
Location: fs/exec.c:109
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff812b56b0-ffffffff812b56d7: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d2624)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff812d2460-ffffffff812d2487: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e4134)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff812e3ff0-ffffffff812e4017: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131c64e)
Location: fs/exec.c:109
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff8131b3a0-ffffffff8131b3c7: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813281a3)
Location: fs/exec.c:112
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - fs/namei.c:may_open
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff813269d0-ffffffff813269f7: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132e0c7)
Location: fs/exec.c:112
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - fs/namei.c:may_open
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff8132f510-ffffffff8132f537: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137b8b7)
Location: fs/exec.c:109
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - fs/namei.c:may_open
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff8137a2d0-ffffffff8137a2f7: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fc14f)
Location: fs/exec.c:109
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - fs/namei.c:may_open
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff813fc9f0-ffffffff813fca1f: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81485bbf)
Location: fs/exec.c:109
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - fs/namei.c:may_open
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff81486540-ffffffff8148656f: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814b98b1)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - fs/namei.c:may_open
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff814bb1f0-ffffffff814bb21f: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ebda1)
Location: fs/exec.c:111
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - fs/namei.c:may_open
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff814ed760-ffffffff814ed78f: path_noexec (STB_GLOBAL)
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
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038cf8c)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__arm64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffff80001038bb30-ffff80001038bb7c: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (c05738e8)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
c05735a0-c05735d4: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000483280)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
c000000000482fa0-c000000000482fd8: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025d094)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffe00025ceca-ffffffe00025cefc: path_noexec (STB_GLOBAL)
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
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dc714)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff812dc5d0-ffffffff812dc5f7: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cd394)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff812cd250-ffffffff812cd277: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812da524)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff812da3e0-ffffffff812da407: path_noexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool path_noexec(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812eb3c4)
Location: fs/exec.c:110
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - fs/open.c:do_faccessat
  - security/security.c:security_mmap_file
```
**Symbols:**

```
ffffffff812eb210-ffffffff812eb237: path_noexec (STB_GLOBAL)
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
