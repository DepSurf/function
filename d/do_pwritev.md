# Function: <code>do_pwritev</code>

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
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233370)
Location: fs/read_write.c:980
Inline: False
Direct callers:
  - fs/read_write.c:SyS_pwritev2
  - fs/read_write.c:SyS_pwritev
```
**Symbols:**

```
ffffffff81233370-ffffffff81233433: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245ef0)
Location: fs/read_write.c:1009
Inline: False
Direct callers:
  - fs/read_write.c:SyS_pwritev2
  - fs/read_write.c:SyS_pwritev
```
**Symbols:**

```
ffffffff81245ef0-ffffffff81245fb3: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251840)
Location: fs/read_write.c:1076
Inline: False
Direct callers:
  - fs/read_write.c:SyS_pwritev2
  - fs/read_write.c:SyS_pwritev
```
**Symbols:**

```
ffffffff81251840-ffffffff81251914: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812731b0)
Location: fs/read_write.c:1079
Inline: False
Direct callers:
  - fs/read_write.c:SyS_pwritev2
  - fs/read_write.c:SyS_pwritev
```
**Symbols:**

```
ffffffff812731b0-ffffffff81273284: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812992a0)
Location: fs/read_write.c:1106
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
```
**Symbols:**

```
ffffffff812992a0-ffffffff81299376: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ae120)
Location: fs/read_write.c:1103
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
```
**Symbols:**

```
ffffffff812ae120-ffffffff812ae1f6: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cadd0)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
```
**Symbols:**

```
ffffffff812cadd0-ffffffff812cae9d: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dc7f0)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
```
**Symbols:**

```
ffffffff812dc7f0-ffffffff812dc8bd: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81313767)
Location: fs/read_write.c:1209
Inline: True
Inline callers:
  - fs/read_write.c:__x64_sys_pwritev
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_pwritev
```
**Symbols:**

```
ffffffff813135d0-ffffffff8131369d: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131f327)
Location: fs/read_write.c:1025
Inline: True
Inline callers:
  - fs/read_write.c:__x64_sys_pwritev
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
```
**Symbols:**

```
ffffffff8131ef40-ffffffff8131f00d: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81324d57)
Location: fs/read_write.c:1023
Inline: True
Inline callers:
  - fs/read_write.c:__x64_sys_pwritev
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
```
**Symbols:**

```
ffffffff81324970-ffffffff81324a3d: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81372997)
Location: fs/read_write.c:1014
Inline: True
Inline callers:
  - fs/read_write.c:__x64_sys_pwritev
Direct callers:
  - fs/read_write.c:__x64_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x64_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x64_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
```
**Symbols:**

```
ffffffff813725b0-ffffffff8137267d: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f0f0e)
Location: fs/read_write.c:1025
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
```
**Symbols:**

```
ffffffff813f0750-ffffffff813f0830: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147928e)
Location: fs/read_write.c:1018
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
```
**Symbols:**

```
ffffffff81478b30-ffffffff81478c10: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814adcee)
Location: fs/read_write.c:1017
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
```
**Symbols:**

```
ffffffff814ad590-ffffffff814ad670: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814df43e)
Location: fs/read_write.c:1059
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
```
**Symbols:**

```
ffffffff814def10-ffffffff814deff0: do_pwritev (STB_LOCAL)
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010382228)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_sys_pwritev2
  - fs/read_write.c:__arm64_sys_pwritev
```
**Symbols:**

```
ffff800010382228-ffff80001038230c: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056c5e0)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pwritev2
  - fs/read_write.c:__se_sys_pwritev
```
**Symbols:**

```
c056c5e0-c056c708: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004788e0)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pwritev2
  - fs/read_write.c:__se_sys_pwritev
```
**Symbols:**

```
c0000000004788e0-c000000000478a08: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000256c80)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pwritev2
  - fs/read_write.c:__se_sys_pwritev
```
**Symbols:**

```
ffffffe000256c80-ffffffe000256d44: do_pwritev (STB_LOCAL)
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4dd0)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
```
**Symbols:**

```
ffffffff812d4dd0-ffffffff812d4e9d: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5a50)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
```
**Symbols:**

```
ffffffff812c5a50-ffffffff812c5b1d: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2be0)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
```
**Symbols:**

```
ffffffff812d2be0-ffffffff812d2cad: do_pwritev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_pwritev(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e3a40)
Location: fs/read_write.c:1125
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev2
  - fs/read_write.c:__x64_sys_pwritev2
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
```
**Symbols:**

```
ffffffff812e3a40-ffffffff812e3b0d: do_pwritev (STB_LOCAL)
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
