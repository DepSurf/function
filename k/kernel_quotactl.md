# Function: <code>kernel_quotactl</code>

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
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81315a60)
Location: fs/quota/quota.c:838
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
**Symbols:**

```
ffffffff81315a60-ffffffff813162f1: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8132c9f0)
Location: fs/quota/quota.c:837
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
**Symbols:**

```
ffffffff8132c9f0-ffffffff8132d2ab: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81354d80)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
**Symbols:**

```
ffffffff81354d80-ffffffff81354ffd: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8136d0f0)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
**Symbols:**

```
ffffffff8136d0f0-ffffffff8136d339: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b4ee0)
Location: fs/quota/quota.c:819
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
```
**Symbols:**

```
ffffffff813b4ee0-ffffffff813b512d: kernel_quotactl (STB_GLOBAL)
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
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffff800010436ff0)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__arm64_sys_quotactl
```
**Symbols:**

```
ffff800010436ff0-ffff800010437284: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c05fec90)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__se_sys_quotactl
```
**Symbols:**

```
c05fec90-c05feef0: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c0000000005492f0)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__se_sys_quotactl
```
**Symbols:**

```
c0000000005492f0-c00000000054965c: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffe0002d134a)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__se_sys_quotactl
```
**Symbols:**

```
ffffffe0002d134a-ffffffe0002d1548: kernel_quotactl (STB_GLOBAL)
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
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813656d0)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
**Symbols:**

```
ffffffff813656d0-ffffffff81365919: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81356370)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
**Symbols:**

```
ffffffff81356370-ffffffff813565b9: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813631a0)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
**Symbols:**

```
ffffffff813631a0-ffffffff813633e9: kernel_quotactl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char *special, qid_t id, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81376850)
Location: fs/quota/quota.c:823
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
**Symbols:**

```
ffffffff81376850-ffffffff81376a99: kernel_quotactl (STB_GLOBAL)
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
