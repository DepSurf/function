# Function: <code>__do_sys_vmsplice</code>

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
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d1410)
Location: fs/splice.c:1345
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff812d1410-ffffffff812d1520: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e6870)
Location: fs/splice.c:1349
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff812e6870-ffffffff812e6980: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813054f0)
Location: fs/splice.c:1355
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff813054f0-ffffffff813055fa: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81318580)
Location: fs/splice.c:1363
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff81318580-ffffffff8131868a: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813514a0)
Location: fs/splice.c:1351
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff813514a0-ffffffff813515b2: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135dd90)
Location: fs/splice.c:1291
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff8135dd90-ffffffff8135df50: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81364c00)
Location: fs/splice.c:1296
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff81364c00-ffffffff81364e48: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/splice.c (0)
Location: fs/splice.c:1298
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff813b30d0-ffffffff813b3318: __do_sys_vmsplice (STB_LOCAL)
ffffffff81cc416f-ffffffff81cc4184: __do_sys_vmsplice.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/splice.c (0)
Location: fs/splice.c:1294
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff814381a0-ffffffff8143843e: __do_sys_vmsplice (STB_LOCAL)
ffffffff81e76a80-ffffffff81e76a94: __do_sys_vmsplice.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c6640)
Location: fs/splice.c:1294
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff814c6640-ffffffff814c68e5: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fc050)
Location: fs/splice.c:1535
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff814fc050-ffffffff814fc35e: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81530e30)
Location: fs/splice.c:1598
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff81530e30-ffffffff81531122: __do_sys_vmsplice (STB_LOCAL)
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
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103ce678)
Location: fs/splice.c:1363
Inline: False
Direct callers:
  - fs/splice.c:__arm64_sys_vmsplice
```
**Symbols:**

```
ffff8000103ce678-ffff8000103ce77c: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a9c70)
Location: fs/splice.c:1363
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_vmsplice
```
**Symbols:**

```
c05a9c70-c05a9e68: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d1ac0)
Location: fs/splice.c:1363
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_vmsplice
```
**Symbols:**

```
c0000000004d1ac0-c0000000004d1c20: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028b538)
Location: fs/splice.c:1363
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_vmsplice
```
**Symbols:**

```
ffffffe00028b538-ffffffe00028b6ca: __do_sys_vmsplice (STB_LOCAL)
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
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81310b60)
Location: fs/splice.c:1363
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff81310b60-ffffffff81310c6a: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81301770)
Location: fs/splice.c:1363
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff81301770-ffffffff8130187a: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130e950)
Location: fs/splice.c:1363
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff8130e950-ffffffff8130ea5a: __do_sys_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81320150)
Location: fs/splice.c:1363
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_vmsplice
  - fs/splice.c:__x64_sys_vmsplice
```
**Symbols:**

```
ffffffff81320150-ffffffff8132025a: __do_sys_vmsplice (STB_LOCAL)
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
