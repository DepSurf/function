# Function: <code>path_openat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121a960)
Location: fs/namei.c:3307
Inline: False
Direct callers:
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
```
**Symbols:**

```
ffffffff8121a960-ffffffff8121bcc0: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81241d00)
Location: fs/namei.c:3466
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff81241d00-ffffffff81243146: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81254be0)
Location: fs/namei.c:3423
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff81254be0-ffffffff812560cb: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81260c40)
Location: fs/namei.c:3488
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff81260c40-ffffffff81262261: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81283340)
Location: fs/namei.c:3486
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff81283340-ffffffff81284aa8: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812aa4f0)
Location: fs/namei.c:3508
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812aa4f0-ffffffff812ab2ba: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bf650)
Location: fs/namei.c:3517
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812bf650-ffffffff812c0d13: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namei.c (0)
Location: fs/namei.c:3516
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812dd270-ffffffff812dd4de: path_openat (STB_LOCAL)
ffffffff812dfd4c-ffffffff812dfd6e: path_openat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eed80)
Location: fs/namei.c:3511
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812eed80-ffffffff812ef008: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81326310)
Location: fs/namei.c:3340
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff81326310-ffffffff813264da: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813317b0)
Location: fs/namei.c:3342
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff813317b0-ffffffff8133197a: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81338170)
Location: fs/namei.c:3474
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff81338170-ffffffff81338416: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81385bd0)
Location: fs/namei.c:3541
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff81385bd0-ffffffff81385e76: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81406a30)
Location: fs/namei.c:3637
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff81406a30-ffffffff81406d06: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81490d80)
Location: fs/namei.c:3694
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff81490d80-ffffffff81491053: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c6590)
Location: fs/namei.c:3773
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff814c6590-ffffffff814c6852: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f8e80)
Location: fs/namei.c:3782
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff814f8e80-ffffffff814f9142: path_openat (STB_LOCAL)
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
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010398540)
Location: fs/namei.c:3511
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffff800010398540-ffff800010398794: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057ebc8)
Location: fs/namei.c:3511
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
c057ebc8-c057ee80: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000492760)
Location: fs/namei.c:3511
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
c000000000492760-c000000000492ad4: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000266234)
Location: fs/namei.c:3511
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffe000266234-ffffffe000266442: path_openat (STB_LOCAL)
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
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7360)
Location: fs/namei.c:3511
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812e7360-ffffffff812e75e8: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7fa0)
Location: fs/namei.c:3511
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812d7fa0-ffffffff812d8228: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5170)
Location: fs/namei.c:3511
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812e5170-ffffffff812e53f8: path_openat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *path_openat(struct nameidata *nd, const struct open_flags *op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f60f0)
Location: fs/namei.c:3511
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812f60f0-ffffffff812f6378: path_openat (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
