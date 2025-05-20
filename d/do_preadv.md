# Function: <code>do_preadv</code>

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
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233160)
Location: fs/read_write.c:957
Inline: False
Direct callers:
  - fs/read_write.c:SyS_preadv2
  - fs/read_write.c:SyS_preadv
```
**Symbols:**

```
ffffffff81233160-ffffffff81233223: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245ce0)
Location: fs/read_write.c:986
Inline: False
Direct callers:
  - fs/read_write.c:SyS_preadv2
  - fs/read_write.c:SyS_preadv
```
**Symbols:**

```
ffffffff81245ce0-ffffffff81245da3: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251140)
Location: fs/read_write.c:1053
Inline: False
Direct callers:
  - fs/read_write.c:SyS_preadv2
  - fs/read_write.c:SyS_preadv
```
**Symbols:**

```
ffffffff81251140-ffffffff81251214: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812747f0)
Location: fs/read_write.c:1056
Inline: False
Direct callers:
  - fs/read_write.c:SyS_preadv2
  - fs/read_write.c:SyS_preadv
```
**Symbols:**

```
ffffffff812747f0-ffffffff812748c4: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129b680)
Location: fs/read_write.c:1083
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
```
**Symbols:**

```
ffffffff8129b680-ffffffff8129b756: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812b0580)
Location: fs/read_write.c:1080
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
```
**Symbols:**

```
ffffffff812b0580-ffffffff812b0656: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cced0)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
```
**Symbols:**

```
ffffffff812cced0-ffffffff812ccf9d: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812de8f0)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
```
**Symbols:**

```
ffffffff812de8f0-ffffffff812de9bd: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81315807)
Location: fs/read_write.c:1186
Inline: True
Inline callers:
  - fs/read_write.c:__x64_sys_preadv
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_preadv
```
**Symbols:**

```
ffffffff81315670-ffffffff8131573d: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131e847)
Location: fs/read_write.c:1002
Inline: True
Inline callers:
  - fs/read_write.c:__x64_sys_preadv
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
```
**Symbols:**

```
ffffffff8131e460-ffffffff8131e52d: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81324287)
Location: fs/read_write.c:1000
Inline: True
Inline callers:
  - fs/read_write.c:__x64_sys_preadv
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x32_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
```
**Symbols:**

```
ffffffff81323ea0-ffffffff81323f6d: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81371ea7)
Location: fs/read_write.c:991
Inline: True
Inline callers:
  - fs/read_write.c:__x64_sys_preadv
Direct callers:
  - fs/read_write.c:__x64_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__x64_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__x64_compat_sys_preadv
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
```
**Symbols:**

```
ffffffff81371ac0-ffffffff81371b8d: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f0e0e)
Location: fs/read_write.c:1002
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
```
**Symbols:**

```
ffffffff813efb80-ffffffff813efc60: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147939e)
Location: fs/read_write.c:995
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
```
**Symbols:**

```
ffffffff81478190-ffffffff81478270: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814addfe)
Location: fs/read_write.c:994
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
```
**Symbols:**

```
ffffffff814ac720-ffffffff814ac800: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814de6be)
Location: fs/read_write.c:1036
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv64v2
  - fs/read_write.c:__ia32_compat_sys_preadv
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
```
**Symbols:**

```
ffffffff814de190-ffffffff814de270: do_preadv (STB_LOCAL)
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
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010384eb0)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_sys_preadv2
  - fs/read_write.c:__arm64_sys_preadv
```
**Symbols:**

```
ffff800010384eb0-ffff800010384f94: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056d838)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_preadv2
  - fs/read_write.c:__se_sys_preadv
```
**Symbols:**

```
c056d838-c056d960: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047af10)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_preadv2
  - fs/read_write.c:__se_sys_preadv
```
**Symbols:**

```
c00000000047af10-c00000000047b038: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000257a56)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_preadv2
  - fs/read_write.c:__se_sys_preadv
```
**Symbols:**

```
ffffffe000257a56-ffffffe000257b1a: do_preadv (STB_LOCAL)
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
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d6ed0)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
```
**Symbols:**

```
ffffffff812d6ed0-ffffffff812d6f9d: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c7b50)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
```
**Symbols:**

```
ffffffff812c7b50-ffffffff812c7c1d: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4ce0)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
```
**Symbols:**

```
ffffffff812d4ce0-ffffffff812d4dad: do_preadv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec *vec, long unsigned int vlen, loff_t pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e5b40)
Location: fs/read_write.c:1102
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv2
  - fs/read_write.c:__x64_sys_preadv2
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
```
**Symbols:**

```
ffffffff812e5b40-ffffffff812e5c0d: do_preadv (STB_LOCAL)
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
