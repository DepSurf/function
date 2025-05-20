# Function: <code>do_compat_fcntl64</code>

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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812aee20)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff812aee20-ffffffff812af0a5: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c3f10)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff812c3f10-ffffffff812c41c4: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e0910)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff812e0910-ffffffff812e0c3e: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f23c0)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff812f23c0-ffffffff812f26ee: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8132a5e0)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff8132a5e0-ffffffff8132a97b: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81335b50)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff81335b50-ffffffff81335eeb: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8133bce0)
Location: fs/fcntl.c:618
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff8133bce0-ffffffff8133c076: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81389960)
Location: fs/fcntl.c:622
Inline: False
Direct callers:
  - fs/fcntl.c:__x64_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x64_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff81389960-ffffffff81389cf6: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8140a9d0)
Location: fs/fcntl.c:600
Inline: False
Direct callers:
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff8140a9d0-ffffffff8140ad88: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81495240)
Location: fs/fcntl.c:601
Inline: False
Direct callers:
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff81495240-ffffffff814955f8: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814ca290)
Location: fs/fcntl.c:602
Inline: False
Direct callers:
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff814ca290-ffffffff814ca640: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fcb60)
Location: fs/fcntl.c:603
Inline: False
Direct callers:
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff814fcb60-ffffffff814fcf10: do_compat_fcntl64 (STB_LOCAL)
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039c5a0)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__arm64_compat_sys_fcntl
  - fs/fcntl.c:__arm64_compat_sys_fcntl64
```
**Symbols:**

```
ffff80001039c5a0-ffff80001039ca38: do_compat_fcntl64 (STB_LOCAL)
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000497340)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__se_compat_sys_fcntl
  - fs/fcntl.c:__se_compat_sys_fcntl64
```
**Symbols:**

```
c000000000497340-c000000000497720: do_compat_fcntl64 (STB_LOCAL)
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ea9a0)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff812ea9a0-ffffffff812eacce: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812db5e0)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff812db5e0-ffffffff812db90e: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e87b0)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff812e87b0-ffffffff812e8ade: do_compat_fcntl64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f9780)
Location: fs/fcntl.c:613
Inline: False
Direct callers:
  - fs/fcntl.c:__x32_compat_sys_fcntl
  - fs/fcntl.c:__ia32_compat_sys_fcntl
  - fs/fcntl.c:__x32_compat_sys_fcntl64
  - fs/fcntl.c:__ia32_compat_sys_fcntl64
```
**Symbols:**

```
ffffffff812f9780-ffffffff812f9aae: do_compat_fcntl64 (STB_LOCAL)
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
