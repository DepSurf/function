# Function: <code>do_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233280)
Location: fs/read_write.c:931
Inline: False
Direct callers:
  - fs/read_write.c:SyS_pwritev2
  - fs/read_write.c:SyS_writev
```
**Symbols:**

```
ffffffff81233280-ffffffff8123336d: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245e00)
Location: fs/read_write.c:960
Inline: False
Direct callers:
  - fs/read_write.c:SyS_pwritev2
  - fs/read_write.c:SyS_writev
```
**Symbols:**

```
ffffffff81245e00-ffffffff81245eed: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251750)
Location: fs/read_write.c:1027
Inline: False
Direct callers:
  - fs/read_write.c:SyS_pwritev2
  - fs/read_write.c:SyS_writev
```
**Symbols:**

```
ffffffff81251750-ffffffff8125183d: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812730c0)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:SyS_pwritev2
  - fs/read_write.c:SyS_writev
```
**Symbols:**

```
ffffffff812730c0-ffffffff812731ad: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81299170)
Location: fs/read_write.c:1057
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff81299170-ffffffff81299256: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812adff0)
Location: fs/read_write.c:1054
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff812adff0-ffffffff812ae0d6: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cac70)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff812cac70-ffffffff812cad82: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dc690)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff812dc690-ffffffff812dc7a2: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81313470)
Location: fs/read_write.c:1156
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff81313470-ffffffff81313582: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131ede0)
Location: fs/read_write.c:972
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff8131ede0-ffffffff8131eef2: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81324810)
Location: fs/read_write.c:970
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff81324810-ffffffff81324922: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81372450)
Location: fs/read_write.c:961
Inline: False
Direct callers:
  - fs/read_write.c:__x64_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x64_compat_sys_pwritev64v2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff81372450-ffffffff81372562: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f0580)
Location: fs/read_write.c:972
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff813f0580-ffffffff813f06e6: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81478930)
Location: fs/read_write.c:965
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff81478930-ffffffff81478a96: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ad390)
Location: fs/read_write.c:964
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff814ad390-ffffffff814ad4f6: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ded10)
Location: fs/read_write.c:1006
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff814ded10-ffffffff814dee76: do_writev (STB_LOCAL)
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
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff8000103820c0)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_sys_pwritev2
  - fs/read_write.c:__arm64_sys_writev
```
**Symbols:**

```
ffff8000103820c0-ffff8000103821f0: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056c480)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pwritev2
  - fs/read_write.c:__se_sys_writev
```
**Symbols:**

```
c056c480-c056c5e0: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478720)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pwritev2
  - fs/read_write.c:__se_sys_writev
```
**Symbols:**

```
c000000000478720-c0000000004788bc: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000256b94)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pwritev2
  - fs/read_write.c:__se_sys_writev
```
**Symbols:**

```
ffffffe000256b94-ffffffe000256c80: do_writev (STB_LOCAL)
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
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4c70)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff812d4c70-ffffffff812d4d82: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c58f0)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff812c58f0-ffffffff812c5a02: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2a80)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff812d2a80-ffffffff812d2b92: do_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_writev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e38e0)
Location: fs/read_write.c:1072
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_writev
  - fs/read_write.c:__x64_sys_writev
```
**Symbols:**

```
ffffffff812e38e0-ffffffff812e39f2: do_writev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flags</code> ➡️ <code>rwf_t flags</code>
</li>
</ul>
</details>
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
