# Function: <code>fuse_do_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813159c0)
Location: fs/fuse/file.c:2448
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff813159c0-ffffffff81316123: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134a300)
Location: fs/fuse/file.c:2518
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff8134a300-ffffffff8134aa6d: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8135faf0)
Location: fs/fuse/file.c:2482
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff8135faf0-ffffffff81360378: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813746e0)
Location: fs/fuse/file.c:2475
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff813746e0-ffffffff81374f9c: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813993b0)
Location: fs/fuse/file.c:2483
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff813993b0-ffffffff81399c2d: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c7f90)
Location: fs/fuse/file.c:2484
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff813c7f90-ffffffff813c8955: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e11c0)
Location: fs/fuse/file.c:2498
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff813e11c0-ffffffff813e1b05: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:2564
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff8141296c-ffffffff81412992: fuse_do_ioctl.cold (STB_LOCAL)
ffffffff8140ce50-ffffffff8140d7ce: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81428280)
Location: fs/fuse/file.c:2710
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff81428280-ffffffff81428b33: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81475f30)
Location: fs/fuse/file.c:2727
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff81475f30-ffffffff8147680e: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81490990)
Location: fs/fuse/file.c:2774
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff81490990-ffffffff81491266: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff814a1650)
Location: fs/fuse/ioctl.c:147
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff814a1650-ffffffff814a1ec7: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff814f9710)
Location: fs/fuse/ioctl.c:147
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff814f9710-ffffffff814f9f68: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff81589a80)
Location: fs/fuse/ioctl.c:158
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff81589a80-ffffffff8158a1cf: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff816300f0)
Location: fs/fuse/ioctl.c:158
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff816300f0-ffffffff816308f3: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff81668170)
Location: fs/fuse/ioctl.c:167
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff81668170-ffffffff81668961: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff816a2470)
Location: fs/fuse/ioctl.c:167
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
**Symbols:**

```
ffffffff816a2470-ffffffff816a2c61: fuse_do_ioctl (STB_GLOBAL)
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
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050a790)
Location: fs/fuse/file.c:2710
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffff80001050a790-ffff80001050aed8: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c7aa0)
Location: fs/fuse/file.c:2710
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
c06c7aa0-c06c8138: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c0000000006529c0)
Location: fs/fuse/file.c:2710
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
c0000000006529c0-c000000000653404: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000376f5a)
Location: fs/fuse/file.c:2710
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffe000376f5a-ffffffe0003774c4: fuse_do_ioctl (STB_GLOBAL)
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
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81420860)
Location: fs/fuse/file.c:2710
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff81420860-ffffffff81421113: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814112e0)
Location: fs/fuse/file.c:2710
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff814112e0-ffffffff81411b93: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141ca00)
Location: fs/fuse/file.c:2710
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff8141ca00-ffffffff8141d2b3: fuse_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int fuse_do_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814337e0)
Location: fs/fuse/file.c:2710
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff814337e0-ffffffff8143401d: fuse_do_ioctl (STB_GLOBAL)
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
