# Function: <code>do_compat_writev</code>

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
In fs/read_write.c (ffffffff812338d0)
Location: fs/read_write.c:1239
Inline: True
Direct callers:
  - fs/read_write.c:compat_SyS_pwritev2
  - fs/read_write.c:compat_SyS_writev
```
**Symbols:**

```
ffffffff812338d0-ffffffff8123398e: do_compat_writev.isra.27 (STB_LOCAL)
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
In fs/read_write.c (ffffffff81246460)
Location: fs/read_write.c:1268
Inline: True
Direct callers:
  - fs/read_write.c:compat_SyS_pwritev2
  - fs/read_write.c:compat_SyS_writev
```
**Symbols:**

```
ffffffff81246460-ffffffff8124651e: do_compat_writev.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251a60)
Location: fs/read_write.c:1279
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_pwritev2
  - fs/read_write.c:compat_SyS_writev
```
**Symbols:**

```
ffffffff81251a60-ffffffff81251b28: do_compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812733d0)
Location: fs/read_write.c:1282
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_pwritev2
  - fs/read_write.c:compat_SyS_writev
```
**Symbols:**

```
ffffffff812733d0-ffffffff81273498: do_compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81299560)
Location: fs/read_write.c:1309
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
**Symbols:**

```
ffffffff81299560-ffffffff8129961a: do_compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ae3e0)
Location: fs/read_write.c:1306
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
**Symbols:**

```
ffffffff812ae3e0-ffffffff812ae49a: do_compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cb080)
Location: fs/read_write.c:1331
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
**Symbols:**

```
ffffffff812cb080-ffffffff812cb139: do_compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dcaa0)
Location: fs/read_write.c:1331
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
**Symbols:**

```
ffffffff812dcaa0-ffffffff812dcb59: do_compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81313960)
Location: fs/read_write.c:1415
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
**Symbols:**

```
ffffffff81313960-ffffffff81313a19: do_compat_writev (STB_LOCAL)
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff8000103824c8)
Location: fs/read_write.c:1331
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_compat_sys_pwritev2
  - fs/read_write.c:__arm64_compat_sys_writev
```
**Symbols:**

```
ffff8000103824c8-ffff8000103825a0: do_compat_writev (STB_LOCAL)
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478c00)
Location: fs/read_write.c:1331
Inline: False
Direct callers:
  - fs/read_write.c:__se_compat_sys_pwritev2
  - fs/read_write.c:__se_compat_sys_writev
```
**Symbols:**

```
c000000000478c00-c000000000478d24: do_compat_writev (STB_LOCAL)
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d5080)
Location: fs/read_write.c:1331
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
**Symbols:**

```
ffffffff812d5080-ffffffff812d5139: do_compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5d00)
Location: fs/read_write.c:1331
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
**Symbols:**

```
ffffffff812c5d00-ffffffff812c5db9: do_compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2e90)
Location: fs/read_write.c:1331
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
**Symbols:**

```
ffffffff812d2e90-ffffffff812d2f49: do_compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec *vec, compat_ulong_t vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e3cf0)
Location: fs/read_write.c:1331
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev2
  - fs/read_write.c:__ia32_compat_sys_pwritev2
  - fs/read_write.c:__x32_compat_sys_pwritev64v2
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
**Symbols:**

```
ffffffff812e3cf0-ffffffff812e3da9: do_compat_writev (STB_LOCAL)
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
