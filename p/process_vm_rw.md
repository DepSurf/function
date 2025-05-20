# Function: <code>process_vm_rw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff811d0c50)
Location: mm/process_vm_access.c:247
Inline: False
Direct callers:
  - mm/process_vm_access.c:SyS_process_vm_readv
  - mm/process_vm_access.c:SyS_process_vm_writev
```
**Symbols:**

```
ffffffff811d0c50-ffffffff811d0d6f: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff811eddd0)
Location: mm/process_vm_access.c:252
Inline: False
Direct callers:
  - mm/process_vm_access.c:SyS_process_vm_writev
  - mm/process_vm_access.c:SyS_process_vm_readv
```
**Symbols:**

```
ffffffff811eddd0-ffffffff811edee6: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff811fe710)
Location: mm/process_vm_access.c:259
Inline: False
Direct callers:
  - mm/process_vm_access.c:SyS_process_vm_writev
  - mm/process_vm_access.c:SyS_process_vm_readv
```
**Symbols:**

```
ffffffff811fe710-ffffffff811fe826: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81209280)
Location: mm/process_vm_access.c:260
Inline: False
Direct callers:
  - mm/process_vm_access.c:SyS_process_vm_writev
  - mm/process_vm_access.c:SyS_process_vm_readv
```
**Symbols:**

```
ffffffff81209280-ffffffff812093d2: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812223d0)
Location: mm/process_vm_access.c:260
Inline: False
Direct callers:
  - mm/process_vm_access.c:SyS_process_vm_writev
  - mm/process_vm_access.c:SyS_process_vm_readv
```
**Symbols:**

```
ffffffff812223d0-ffffffff81222522: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812442e0)
Location: mm/process_vm_access.c:258
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff812442e0-ffffffff812443f9: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812589e0)
Location: mm/process_vm_access.c:258
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff812589e0-ffffffff81258af9: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff8126c1a0)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff8126c1a0-ffffffff8126c2c3: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff8127afb0)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff8127afb0-ffffffff8127b0d3: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812ad270)
Location: mm/process_vm_access.c:256
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff812ad270-ffffffff812ad3a1: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812b8cf0)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff812b8cf0-ffffffff812b8e2e: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812be1c0)
Location: mm/process_vm_access.c:253
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff812be1c0-ffffffff812be2f6: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81300960)
Location: mm/process_vm_access.c:253
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81300960-ffffffff81300a96: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81367d60)
Location: mm/process_vm_access.c:253
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81367d60-ffffffff81367ece: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff813e3d40)
Location: mm/process_vm_access.c:253
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff813e3d40-ffffffff813e3eae: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81418a90)
Location: mm/process_vm_access.c:253
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81418a90-ffffffff81418bfe: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff814455e0)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff814455e0-ffffffff8144574e: process_vm_rw (STB_LOCAL)
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
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffff800010312528)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__arm64_sys_process_vm_writev
  - mm/process_vm_access.c:__arm64_sys_process_vm_readv
```
**Symbols:**

```
ffff800010312528-ffff800010312660: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (c052d3a8)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__se_sys_process_vm_writev
  - mm/process_vm_access.c:__se_sys_process_vm_readv
```
**Symbols:**

```
c052d3a8-c052d4c8: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (c0000000003e3490)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__se_sys_process_vm_writev
  - mm/process_vm_access.c:__se_sys_process_vm_readv
```
**Symbols:**

```
c0000000003e3490-c0000000003e3614: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffe000219ae4)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__se_sys_process_vm_writev
  - mm/process_vm_access.c:__se_sys_process_vm_readv
```
**Symbols:**

```
ffffffe000219ae4-ffffffe000219bc4: process_vm_rw (STB_LOCAL)
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
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81273600)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81273600-ffffffff81273723: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81265570)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81265570-ffffffff81265693: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812713a0)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff812713a0-ffffffff812714c3: process_vm_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec *lvec, long unsigned int liovcnt, const struct iovec *rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81280e10)
Location: mm/process_vm_access.c:254
Inline: False
Direct callers:
  - mm/process_vm_access.c:__ia32_sys_process_vm_writev
  - mm/process_vm_access.c:__x64_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_sys_process_vm_readv
  - mm/process_vm_access.c:__x64_sys_process_vm_readv
```
**Symbols:**

```
ffffffff81280e10-ffffffff81280f33: process_vm_rw (STB_LOCAL)
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
