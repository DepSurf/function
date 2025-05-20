# Function: <code>fcntl_setlk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81262bc0)
Location: fs/locks.c:2156
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff81262bc0-ffffffff81262e69: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128ede0)
Location: fs/locks.c:2182
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff8128ede0-ffffffff8128f0cc: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a3d90)
Location: fs/locks.c:2220
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff812a3d90-ffffffff812a4080: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b29d0)
Location: fs/locks.c:2211
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812b29d0-ffffffff812b2c90: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d64c0)
Location: fs/locks.c:2247
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812d64c0-ffffffff812d672f: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81301100)
Location: fs/locks.c:2252
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81301100-ffffffff813013be: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81316bd0)
Location: fs/locks.c:2364
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81316bd0-ffffffff81316eae: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133e470)
Location: fs/locks.c:2382
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8133e470-ffffffff8133e759: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81356a60)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81356a60-ffffffff81356d49: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139dc90)
Location: fs/locks.c:2475
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8139dc90-ffffffff8139dfb8: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813af640)
Location: fs/locks.c:2476
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813af640-ffffffff813af948: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b6900)
Location: fs/locks.c:2478
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813b6900-ffffffff813b6bde: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81406600)
Location: fs/locks.c:2381
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81406600-ffffffff814068db: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147b100)
Location: fs/locks.c:2367
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8147b100-ffffffff8147b3f9: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150dc80)
Location: fs/locks.c:2349
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8150dc80-ffffffff8150df79: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81545460)
Location: fs/locks.c:2326
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81545460-ffffffff8154574d: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157a9c0)
Location: fs/locks.c:2336
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8157a9c0-ffffffff8157aca6: fcntl_setlk (STB_GLOBAL)
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
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010419568)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffff800010419568-ffff8000104198a0: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e55f0)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c05e55f0-c05e58b4: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000529060)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c000000000529060-c000000000529404: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bfd44)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
ffffffe0002bfd44-ffffffe0002bffca: fcntl_setlk (STB_GLOBAL)
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
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134f040)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8134f040-ffffffff8134f329: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133fd20)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8133fd20-ffffffff81340009: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134cb10)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8134cb10-ffffffff8134cdf9: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fcntl_setlk(unsigned int fd, struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81360050)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81360050-ffffffff81360353: fcntl_setlk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct flock *flock</code>
</li>
<li>
<b>Param removed. </b>
<code>struct flock *l</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
