# Function: <code>fcntl_getlk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812629f0)
Location: fs/locks.c:2025
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff812629f0-ffffffff81262bb4: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128ec10)
Location: fs/locks.c:2051
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff8128ec10-ffffffff8128eddf: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a3bc0)
Location: fs/locks.c:2089
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff812a3bc0-ffffffff812a3d8f: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b2850)
Location: fs/locks.c:2087
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812b2850-ffffffff812b29c2: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d63b0)
Location: fs/locks.c:2121
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812d63b0-ffffffff812d64b9: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81300fe0)
Location: fs/locks.c:2126
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81300fe0-ffffffff813010f2: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81316a40)
Location: fs/locks.c:2240
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81316a40-ffffffff81316bce: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133e2b0)
Location: fs/locks.c:2258
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8133e2b0-ffffffff8133e465: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813568a0)
Location: fs/locks.c:2347
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813568a0-ffffffff81356a55: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139da80)
Location: fs/locks.c:2350
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8139da80-ffffffff8139dc89: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813af430)
Location: fs/locks.c:2351
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813af430-ffffffff813af639: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b66f0)
Location: fs/locks.c:2354
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813b66f0-ffffffff813b68f9: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814063f0)
Location: fs/locks.c:2257
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff814063f0-ffffffff814065f9: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147aee0)
Location: fs/locks.c:2243
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8147aee0-ffffffff8147b100: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150da30)
Location: fs/locks.c:2224
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8150da30-ffffffff8150dc61: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81545210)
Location: fs/locks.c:2201
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81545210-ffffffff81545444: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157a700)
Location: fs/locks.c:2208
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8157a700-ffffffff8157a9a4: fcntl_getlk (STB_GLOBAL)
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
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff8000104193c8)
Location: fs/locks.c:2347
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffff8000104193c8-ffff800010419568: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e5484)
Location: fs/locks.c:2347
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c05e5484-c05e55f0: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000528ea0)
Location: fs/locks.c:2347
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c000000000528ea0-c000000000529058: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bfc18)
Location: fs/locks.c:2347
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
ffffffe0002bfc18-ffffffe0002bfd44: fcntl_getlk (STB_GLOBAL)
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
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134ee80)
Location: fs/locks.c:2347
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8134ee80-ffffffff8134f035: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133fb60)
Location: fs/locks.c:2347
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8133fb60-ffffffff8133fd15: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134c950)
Location: fs/locks.c:2347
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8134c950-ffffffff8134cb05: fcntl_getlk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fcntl_getlk(struct file *filp, unsigned int cmd, struct flock *flock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135fe90)
Location: fs/locks.c:2347
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8135fe90-ffffffff81360045: fcntl_getlk (STB_GLOBAL)
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
