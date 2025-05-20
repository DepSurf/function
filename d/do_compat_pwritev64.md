# Function: <code>do_compat_pwritev64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff81233990)
Location: fs/read_write.c:1264
Inline: True
Direct callers:
  - fs/read_write.c:compat_SyS_pwritev2
  - fs/read_write.c:compat_SyS_pwritev64v2
  - fs/read_write.c:compat_SyS_pwritev
  - fs/read_write.c:compat_SyS_pwritev64
```
**Symbols:**

```
ffffffff81233990-ffffffff81233a1a: do_compat_pwritev64.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff81246520)
Location: fs/read_write.c:1293
Inline: True
Direct callers:
  - fs/read_write.c:compat_SyS_pwritev2
  - fs/read_write.c:compat_SyS_pwritev64v2
  - fs/read_write.c:compat_SyS_pwritev
  - fs/read_write.c:compat_SyS_pwritev64
```
**Symbols:**

```
ffffffff81246520-ffffffff812465aa: do_compat_pwritev64.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251b30)
Location: fs/read_write.c:1304
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_pwritev2
  - fs/read_write.c:compat_SyS_pwritev64v2
  - fs/read_write.c:compat_SyS_pwritev
  - fs/read_write.c:compat_SyS_pwritev64
```
**Symbols:**

```
ffffffff81251b30-ffffffff81251bc5: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812734a0)
Location: fs/read_write.c:1307
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_pwritev2
  - fs/read_write.c:compat_SyS_pwritev64v2
  - fs/read_write.c:compat_SyS_pwritev
  - fs/read_write.c:compat_SyS_pwritev64
```
**Symbols:**

```
ffffffff812734a0-ffffffff81273535: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81299660)
Location: fs/read_write.c:1334
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
```
**Symbols:**

```
ffffffff81299660-ffffffff81299708: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ae4e0)
Location: fs/read_write.c:1331
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
```
**Symbols:**

```
ffffffff812ae4e0-ffffffff812ae588: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cb180)
Location: fs/read_write.c:1356
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
```
**Symbols:**

```
ffffffff812cb180-ffffffff812cb218: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dcba0)
Location: fs/read_write.c:1356
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
```
**Symbols:**

```
ffffffff812dcba0-ffffffff812dcc38: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81313ca7)
Location: fs/read_write.c:1440
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
```
**Symbols:**

```
ffffffff81313a60-ffffffff81313af8: do_compat_pwritev64 (STB_LOCAL)
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff8000103825d8)
Location: fs/read_write.c:1356
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_compat_sys_pwritev2
  - fs/read_write.c:__arm64_compat_sys_pwritev
```
**Symbols:**

```
ffff8000103825d8-ffff80001038269c: do_compat_pwritev64 (STB_LOCAL)
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478d50)
Location: fs/read_write.c:1356
Inline: False
Direct callers:
  - fs/read_write.c:__se_compat_sys_pwritev2
  - fs/read_write.c:__se_compat_sys_pwritev
```
**Symbols:**

```
c000000000478d50-c000000000478e50: do_compat_pwritev64 (STB_LOCAL)
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d5180)
Location: fs/read_write.c:1356
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
```
**Symbols:**

```
ffffffff812d5180-ffffffff812d5218: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5e00)
Location: fs/read_write.c:1356
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
```
**Symbols:**

```
ffffffff812c5e00-ffffffff812c5e98: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2f90)
Location: fs/read_write.c:1356
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
```
**Symbols:**

```
ffffffff812d2f90-ffffffff812d3028: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e3df0)
Location: fs/read_write.c:1356
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__ia32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_pwritev
  - fs/read_write.c:__ia32_compat_sys_pwritev
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
```
**Symbols:**

```
ffffffff812e3df0-ffffffff812e3e88: do_compat_pwritev64 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
