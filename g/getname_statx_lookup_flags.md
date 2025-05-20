# Function: <code>getname_statx_lookup_flags</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int getname_statx_lookup_flags(int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f98bc)
Location: fs/stat.c:187
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_fstatat
  - fs/stat.c:vfs_statx
Direct callers:
  - io_uring/io_uring.c:io_statx_prep
```
**Symbols:**

```
ffffffff813f90d0-ffffffff813f910a: getname_statx_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int getname_statx_lookup_flags(int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814830fc)
Location: fs/stat.c:191
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_fstatat
  - fs/stat.c:vfs_statx
Direct callers:
  - io_uring/statx.c:io_statx_prep
```
**Symbols:**

```
ffffffff81482790-ffffffff814827ca: getname_statx_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int getname_statx_lookup_flags(int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7d1c)
Location: fs/stat.c:197
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_fstatat
  - fs/stat.c:vfs_statx
Direct callers:
  - io_uring/statx.c:io_statx_prep
```
**Symbols:**

```
ffffffff814b73b0-ffffffff814b73ea: getname_statx_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int getname_statx_lookup_flags(int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814ea21c)
Location: fs/stat.c:203
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/stat.c:vfs_statx
Direct callers:
  - io_uring/statx.c:io_statx_prep
```
**Symbols:**

```
ffffffff814e9df0-ffffffff814e9e2a: getname_statx_lookup_flags (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
