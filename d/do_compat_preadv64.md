# Function: <code>do_compat_preadv64</code>

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
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812337c0)
Location: fs/read_write.c:1158
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_preadv2
  - fs/read_write.c:compat_SyS_preadv64v2
  - fs/read_write.c:compat_SyS_preadv
  - fs/read_write.c:compat_SyS_preadv64
```
**Symbols:**

```
ffffffff812337c0-ffffffff81233855: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81246350)
Location: fs/read_write.c:1187
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_preadv2
  - fs/read_write.c:compat_SyS_preadv64v2
  - fs/read_write.c:compat_SyS_preadv
  - fs/read_write.c:compat_SyS_preadv64
```
**Symbols:**

```
ffffffff81246350-ffffffff812463e5: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812513e0)
Location: fs/read_write.c:1198
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_preadv2
  - fs/read_write.c:compat_SyS_preadv64v2
  - fs/read_write.c:compat_SyS_preadv
  - fs/read_write.c:compat_SyS_preadv64
```
**Symbols:**

```
ffffffff812513e0-ffffffff81251475: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272d40)
Location: fs/read_write.c:1201
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_preadv2
  - fs/read_write.c:compat_SyS_preadv64v2
  - fs/read_write.c:compat_SyS_preadv
  - fs/read_write.c:compat_SyS_preadv64
```
**Symbols:**

```
ffffffff81272d40-ffffffff81272dd5: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81298c40)
Location: fs/read_write.c:1228
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
```
**Symbols:**

```
ffffffff81298c40-ffffffff81298ce8: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812adac0)
Location: fs/read_write.c:1225
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
```
**Symbols:**

```
ffffffff812adac0-ffffffff812adb68: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca750)
Location: fs/read_write.c:1247
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
```
**Symbols:**

```
ffffffff812ca750-ffffffff812ca7e8: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dc170)
Location: fs/read_write.c:1247
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
```
**Symbols:**

```
ffffffff812dc170-ffffffff812dc208: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81312fa7)
Location: fs/read_write.c:1331
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
```
**Symbols:**

```
ffffffff81312d60-ffffffff81312df8: do_compat_preadv64 (STB_LOCAL)
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
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381c38)
Location: fs/read_write.c:1247
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_compat_sys_preadv2
  - fs/read_write.c:__arm64_compat_sys_preadv
```
**Symbols:**

```
ffff800010381c38-ffff800010381cfc: do_compat_preadv64 (STB_LOCAL)
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
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478180)
Location: fs/read_write.c:1247
Inline: False
Direct callers:
  - fs/read_write.c:__se_compat_sys_preadv2
  - fs/read_write.c:__se_compat_sys_preadv
```
**Symbols:**

```
c000000000478180-c000000000478280: do_compat_preadv64 (STB_LOCAL)
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
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4750)
Location: fs/read_write.c:1247
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
```
**Symbols:**

```
ffffffff812d4750-ffffffff812d47e8: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c53d0)
Location: fs/read_write.c:1247
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
```
**Symbols:**

```
ffffffff812c53d0-ffffffff812c5468: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2560)
Location: fs/read_write.c:1247
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
```
**Symbols:**

```
ffffffff812d2560-ffffffff812d25f8: do_compat_preadv64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_compat_preadv64(long unsigned int fd, const struct compat_iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e33c0)
Location: fs/read_write.c:1247
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
```
**Symbols:**

```
ffffffff812e33c0-ffffffff812e3458: do_compat_preadv64 (STB_LOCAL)
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
