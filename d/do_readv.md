# Function: <code>do_readv</code>

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
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233070)
Location: fs/read_write.c:911
Inline: False
Direct callers:
  - fs/read_write.c:SyS_preadv2
  - fs/read_write.c:SyS_readv
```
**Symbols:**

```
ffffffff81233070-ffffffff8123315d: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245bf0)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:SyS_preadv2
  - fs/read_write.c:SyS_readv
```
**Symbols:**

```
ffffffff81245bf0-ffffffff81245cdd: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251050)
Location: fs/read_write.c:1007
Inline: False
Direct callers:
  - fs/read_write.c:SyS_preadv2
  - fs/read_write.c:SyS_readv
```
**Symbols:**

```
ffffffff81251050-ffffffff8125113d: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81274700)
Location: fs/read_write.c:1010
Inline: False
Direct callers:
  - fs/read_write.c:SyS_preadv2
  - fs/read_write.c:SyS_readv
```
**Symbols:**

```
ffffffff81274700-ffffffff812747ed: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129b550)
Location: fs/read_write.c:1037
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff8129b550-ffffffff8129b636: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812b0450)
Location: fs/read_write.c:1034
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff812b0450-ffffffff812b0536: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ccd70)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff812ccd70-ffffffff812cce82: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812de790)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff812de790-ffffffff812de8a2: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81315510)
Location: fs/read_write.c:1132
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff81315510-ffffffff81315622: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131e300)
Location: fs/read_write.c:948
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff8131e300-ffffffff8131e412: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81323d40)
Location: fs/read_write.c:946
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff81323d40-ffffffff81323e52: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81371960)
Location: fs/read_write.c:937
Inline: False
Direct callers:
  - fs/read_write.c:__x64_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x64_compat_sys_preadv64v2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff81371960-ffffffff81371a72: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813ef9b0)
Location: fs/read_write.c:948
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff813ef9b0-ffffffff813efb16: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81477f90)
Location: fs/read_write.c:941
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff81477f90-ffffffff814780f6: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ac520)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff814ac520-ffffffff814ac686: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ddf90)
Location: fs/read_write.c:982
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff814ddf90-ffffffff814de0f6: do_readv (STB_LOCAL)
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
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010384d48)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_sys_preadv2
  - fs/read_write.c:__arm64_sys_readv
```
**Symbols:**

```
ffff800010384d48-ffff800010384e78: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056d6d8)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_preadv2
  - fs/read_write.c:__se_sys_readv
```
**Symbols:**

```
c056d6d8-c056d838: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047ad50)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_preadv2
  - fs/read_write.c:__se_sys_readv
```
**Symbols:**

```
c00000000047ad50-c00000000047aeec: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe00025796a)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_preadv2
  - fs/read_write.c:__se_sys_readv
```
**Symbols:**

```
ffffffe00025796a-ffffffe000257a56: do_readv (STB_LOCAL)
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
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d6d70)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff812d6d70-ffffffff812d6e82: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c79f0)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff812c79f0-ffffffff812c7b02: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4b80)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff812d4b80-ffffffff812d4c92: do_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_readv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e59e0)
Location: fs/read_write.c:1048
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_readv
  - fs/read_write.c:__x64_sys_readv
```
**Symbols:**

```
ffffffff812e59e0-ffffffff812e5af2: do_readv (STB_LOCAL)
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
