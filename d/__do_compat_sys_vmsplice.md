# Function: <code>__do_compat_sys_vmsplice</code>

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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d1560)
Location: fs/splice.c:1371
Inline: False
Direct callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
**Symbols:**

```
ffffffff812d1560-ffffffff812d1670: __do_compat_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e69c0)
Location: fs/splice.c:1375
Inline: False
Direct callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
**Symbols:**

```
ffffffff812e69c0-ffffffff812e6ad0: __do_compat_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81305640)
Location: fs/splice.c:1381
Inline: False
Direct callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
**Symbols:**

```
ffffffff81305640-ffffffff81305747: __do_compat_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813186d0)
Location: fs/splice.c:1389
Inline: False
Direct callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
**Symbols:**

```
ffffffff813186d0-ffffffff813187d7: __do_compat_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81351600)
Location: fs/splice.c:1377
Inline: False
Direct callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
**Symbols:**

```
ffffffff81351600-ffffffff81351712: __do_compat_sys_vmsplice (STB_LOCAL)
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103ce7b8)
Location: fs/splice.c:1389
Inline: False
Direct callers:
  - fs/splice.c:__arm64_compat_sys_vmsplice
```
**Symbols:**

```
ffff8000103ce7b8-ffff8000103ce8bc: __do_compat_sys_vmsplice (STB_LOCAL)
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d1c40)
Location: fs/splice.c:1389
Inline: False
Direct callers:
  - fs/splice.c:__se_compat_sys_vmsplice
```
**Symbols:**

```
c0000000004d1c40-c0000000004d1da0: __do_compat_sys_vmsplice (STB_LOCAL)
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81310cb0)
Location: fs/splice.c:1389
Inline: False
Direct callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
**Symbols:**

```
ffffffff81310cb0-ffffffff81310db7: __do_compat_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813018c0)
Location: fs/splice.c:1389
Inline: False
Direct callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
**Symbols:**

```
ffffffff813018c0-ffffffff813019c7: __do_compat_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130eaa0)
Location: fs/splice.c:1389
Inline: False
Direct callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
**Symbols:**

```
ffffffff8130eaa0-ffffffff8130eba7: __do_compat_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec *iov32, unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813202a0)
Location: fs/splice.c:1389
Inline: False
Direct callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
**Symbols:**

```
ffffffff813202a0-ffffffff813203a7: __do_compat_sys_vmsplice (STB_LOCAL)
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
