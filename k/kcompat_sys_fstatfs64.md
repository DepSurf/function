# Function: <code>kcompat_sys_fstatfs64</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea9b0)
Location: fs/statfs.c:357
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff812ea9b0-ffffffff812eaa18: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81309420)
Location: fs/statfs.c:371
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff81309420-ffffffff8130948a: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131c490)
Location: fs/statfs.c:362
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff8131c490-ffffffff8131c4fa: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813561b0)
Location: fs/statfs.c:362
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff813561b0-ffffffff81356218: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81362af0)
Location: fs/statfs.c:364
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff81362af0-ffffffff81362b58: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81369590)
Location: fs/statfs.c:367
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff81369590-ffffffff813695f8: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b8290)
Location: fs/statfs.c:367
Inline: False
Direct callers:
  - fs/statfs.c:__x64_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff813b8290-ffffffff813b82f8: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143db50)
Location: fs/statfs.c:367
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff8143db50-ffffffff8143dbdb: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cc4d0)
Location: fs/statfs.c:367
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff814cc4d0-ffffffff814cc55b: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81502710)
Location: fs/statfs.c:367
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff81502710-ffffffff8150279b: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81537360)
Location: fs/statfs.c:367
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff81537360-ffffffff815373eb: kcompat_sys_fstatfs64 (STB_GLOBAL)
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d3e30)
Location: fs/statfs.c:362
Inline: False
Direct callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_fstatfs64
  - fs/statfs.c:__arm64_compat_sys_fstatfs64
```
**Symbols:**

```
ffff8000103d3e30-ffff8000103d3ebc: kcompat_sys_fstatfs64 (STB_GLOBAL)
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6950)
Location: fs/statfs.c:362
Inline: False
Direct callers:
  - fs/statfs.c:__se_compat_sys_fstatfs64
```
**Symbols:**

```
c0000000004d6950-c0000000004d6a0c: kcompat_sys_fstatfs64 (STB_GLOBAL)
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81314a70)
Location: fs/statfs.c:362
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff81314a70-ffffffff81314ada: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81305680)
Location: fs/statfs.c:362
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff81305680-ffffffff813056ea: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81312860)
Location: fs/statfs.c:362
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff81312860-ffffffff813128ca: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813240a0)
Location: fs/statfs.c:362
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs64
  - fs/statfs.c:__ia32_compat_sys_fstatfs64
```
**Symbols:**

```
ffffffff813240a0-ffffffff8132410a: kcompat_sys_fstatfs64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
