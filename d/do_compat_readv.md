# Function: <code>do_compat_readv</code>

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
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812336f0)
Location: fs/read_write.c:1132
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_preadv2
  - fs/read_write.c:compat_SyS_readv
```
**Symbols:**

```
ffffffff812336f0-ffffffff812337b8: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81246280)
Location: fs/read_write.c:1161
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_preadv2
  - fs/read_write.c:compat_SyS_readv
```
**Symbols:**

```
ffffffff81246280-ffffffff81246348: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251310)
Location: fs/read_write.c:1172
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_preadv2
  - fs/read_write.c:compat_SyS_readv
```
**Symbols:**

```
ffffffff81251310-ffffffff812513d8: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272c70)
Location: fs/read_write.c:1175
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_preadv2
  - fs/read_write.c:compat_SyS_readv
```
**Symbols:**

```
ffffffff81272c70-ffffffff81272d38: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81298b40)
Location: fs/read_write.c:1202
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
**Symbols:**

```
ffffffff81298b40-ffffffff81298bfa: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ad9c0)
Location: fs/read_write.c:1199
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
**Symbols:**

```
ffffffff812ad9c0-ffffffff812ada7a: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca650)
Location: fs/read_write.c:1221
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
**Symbols:**

```
ffffffff812ca650-ffffffff812ca709: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dc070)
Location: fs/read_write.c:1221
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
**Symbols:**

```
ffffffff812dc070-ffffffff812dc129: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81312c60)
Location: fs/read_write.c:1305
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
**Symbols:**

```
ffffffff81312c60-ffffffff81312d19: do_compat_readv (STB_LOCAL)
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
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381b28)
Location: fs/read_write.c:1221
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_compat_sys_preadv2
  - fs/read_write.c:__arm64_compat_sys_readv
```
**Symbols:**

```
ffff800010381b28-ffff800010381c00: do_compat_readv (STB_LOCAL)
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
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478030)
Location: fs/read_write.c:1221
Inline: False
Direct callers:
  - fs/read_write.c:__se_compat_sys_preadv2
  - fs/read_write.c:__se_compat_sys_readv
```
**Symbols:**

```
c000000000478030-c000000000478154: do_compat_readv (STB_LOCAL)
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
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4650)
Location: fs/read_write.c:1221
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
**Symbols:**

```
ffffffff812d4650-ffffffff812d4709: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c52d0)
Location: fs/read_write.c:1221
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
**Symbols:**

```
ffffffff812c52d0-ffffffff812c5389: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2460)
Location: fs/read_write.c:1221
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
**Symbols:**

```
ffffffff812d2460-ffffffff812d2519: do_compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t do_compat_readv(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e32c0)
Location: fs/read_write.c:1221
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
**Symbols:**

```
ffffffff812e32c0-ffffffff812e3379: do_compat_readv (STB_LOCAL)
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
