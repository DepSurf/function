# Function: <code>vfs_statx_fd</code>

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
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81256760)
Location: fs/stat.c:131
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - fs/stat.c:C_SYSC_newfstat
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_fstat
```
**Symbols:**

```
ffffffff81256760-ffffffff812567da: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812789b0)
Location: fs/stat.c:132
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - fs/stat.c:C_SYSC_newfstat
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_fstat
```
**Symbols:**

```
ffffffff812789b0-ffffffff81278a2a: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f2f0)
Location: fs/stat.c:132
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff8129f2f0-ffffffff8129f379: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b42d0)
Location: fs/stat.c:132
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff812b42d0-ffffffff812b4359: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1040)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff812d1040-ffffffff812d10c8: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e2bd0)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff812e2bd0-ffffffff812e2c58: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131aea0)
Location: fs/stat.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff8131aea0-ffffffff8131af42: vfs_statx_fd (STB_GLOBAL)
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
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038a5a8)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_fstat64
  - fs/stat.c:__do_sys_newfstat
```
**Symbols:**

```
ffff80001038a5a8-ffff80001038a658: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c057278c)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstat64
  - fs/stat.c:__do_sys_newfstat
```
**Symbols:**

```
c057278c-c057280c: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000481800)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_fstat64
  - fs/stat.c:__do_sys_newfstat
```
**Symbols:**

```
c000000000481800-c0000000004818d8: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c4ee)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_newfstat
```
**Symbols:**

```
ffffffe00025c4ee-ffffffe00025c572: vfs_statx_fd (STB_GLOBAL)
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
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db1b0)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff812db1b0-ffffffff812db238: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cbe30)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff812cbe30-ffffffff812cbeb8: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d8fc0)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff812d8fc0-ffffffff812d9048: vfs_statx_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e9ed0)
Location: fs/stat.c:134
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff812e9ed0-ffffffff812e9f58: vfs_statx_fd (STB_GLOBAL)
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
