# Function: <code>compat_process_vm_rw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff811d0d70)
Location: mm/process_vm_access.c:305
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_SyS_process_vm_readv
  - mm/process_vm_access.c:compat_SyS_process_vm_writev
```
**Symbols:**

```
ffffffff811d0d70-ffffffff811d0e8f: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff811edef0)
Location: mm/process_vm_access.c:310
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_SyS_process_vm_writev
  - mm/process_vm_access.c:compat_SyS_process_vm_readv
```
**Symbols:**

```
ffffffff811edef0-ffffffff811ee006: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff811fe830)
Location: mm/process_vm_access.c:317
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_SyS_process_vm_writev
  - mm/process_vm_access.c:compat_SyS_process_vm_readv
```
**Symbols:**

```
ffffffff811fe830-ffffffff811fe946: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812093e0)
Location: mm/process_vm_access.c:318
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_SyS_process_vm_writev
  - mm/process_vm_access.c:compat_SyS_process_vm_readv
```
**Symbols:**

```
ffffffff812093e0-ffffffff81209532: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81222530)
Location: mm/process_vm_access.c:318
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_SyS_process_vm_writev
  - mm/process_vm_access.c:compat_SyS_process_vm_readv
```
**Symbols:**

```
ffffffff81222530-ffffffff81222682: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812444c0)
Location: mm/process_vm_access.c:316
Inline: False
Direct callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
**Symbols:**

```
ffffffff812444c0-ffffffff812445d9: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81258bc0)
Location: mm/process_vm_access.c:316
Inline: False
Direct callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81258bc0-ffffffff81258cd9: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff8126c390)
Location: mm/process_vm_access.c:312
Inline: False
Direct callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
**Symbols:**

```
ffffffff8126c390-ffffffff8126c4b3: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff8127b1a0)
Location: mm/process_vm_access.c:312
Inline: False
Direct callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
**Symbols:**

```
ffffffff8127b1a0-ffffffff8127b2c3: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812ad0d0)
Location: mm/process_vm_access.c:314
Inline: False
Direct callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
**Symbols:**

```
ffffffff812ad0d0-ffffffff812ad201: compat_process_vm_rw (STB_LOCAL)
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffff8000103126e0)
Location: mm/process_vm_access.c:312
Inline: False
Direct callers:
  - mm/process_vm_access.c:__arm64_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__arm64_compat_sys_process_vm_readv
```
**Symbols:**

```
ffff8000103126e0-ffff800010312818: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (c0000000003e3660)
Location: mm/process_vm_access.c:312
Inline: False
Direct callers:
  - mm/process_vm_access.c:__se_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__se_compat_sys_process_vm_readv
```
**Symbols:**

```
c0000000003e3660-c0000000003e37e4: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812737f0)
Location: mm/process_vm_access.c:312
Inline: False
Direct callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
**Symbols:**

```
ffffffff812737f0-ffffffff81273913: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81265760)
Location: mm/process_vm_access.c:312
Inline: False
Direct callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81265760-ffffffff81265883: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81271590)
Location: mm/process_vm_access.c:312
Inline: False
Direct callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81271590-ffffffff812716b3: compat_process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec *lvec, long unsigned int liovcnt, const struct compat_iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81281000)
Location: mm/process_vm_access.c:312
Inline: False
Direct callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81281000-ffffffff81281123: compat_process_vm_rw (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
