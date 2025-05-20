# Function: <code>vfs_fallocate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81209580)
Location: fs/open.c:231
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - fs/open.c:SyS_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff81209580-ffffffff8120979a: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122f370)
Location: fs/open.c:231
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - fs/open.c:SyS_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff8122f370-ffffffff8122f58a: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812418c0)
Location: fs/open.c:242
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - fs/open.c:SyS_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff812418c0-ffffffff81241adf: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124cc20)
Location: fs/open.c:243
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - fs/open.c:SyS_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff8124cc20-ffffffff8124ce7d: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126eb90)
Location: fs/open.c:243
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - fs/open.c:SyS_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff8126eb90-ffffffff8126edef: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81294780)
Location: fs/open.c:243
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff81294780-ffffffff812949eb: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812a9750)
Location: fs/open.c:232
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff812a9750-ffffffff812a99ce: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c5ed0)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff812c5ed0-ffffffff812c6165: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d78e0)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff812d78e0-ffffffff812d7b75: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130db00)
Location: fs/open.c:230
Inline: False
Direct callers:
  - mm/madvise.c:madvise_remove
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/ioctl.c:compat_ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8130db00-ffffffff8130dd8a: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81319df0)
Location: fs/open.c:230
Inline: False
Direct callers:
  - mm/madvise.c:madvise_remove
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/ioctl.c:compat_ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81319df0-ffffffff8131a0d2: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131fed0)
Location: fs/open.c:231
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/ioctl.c:compat_ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8131fed0-ffffffff813201b2: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136d470)
Location: fs/open.c:228
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/ioctl.c:compat_ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8136d470-ffffffff8136d762: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ec000)
Location: fs/open.c:243
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/ioctl.c:compat_ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - io_uring/io_uring.c:io_fallocate
```
**Symbols:**

```
ffffffff813ec000-ffffffff813ec362: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814744d0)
Location: fs/open.c:243
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/ioctl.c:compat_ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - io_uring/sync.c:io_fallocate
```
**Symbols:**

```
ffffffff814744d0-ffffffff81474832: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a8e90)
Location: fs/open.c:244
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/ioctl.c:compat_ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - io_uring/sync.c:io_fallocate
```
**Symbols:**

```
ffffffff814a8e90-ffffffff814a921b: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d9ef0)
Location: fs/open.c:244
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/ioctl.c:compat_ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - io_uring/sync.c:io_fallocate
```
**Symbols:**

```
ffffffff814d9ef0-ffffffff814da264: vfs_fallocate (STB_GLOBAL)
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
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037cd00)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffff80001037cd00-ffff80001037cf78: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c05679b8)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
c05679b8-c0567c5c: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0000000004720e0)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
c0000000004720e0-c000000000472470: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe00025323a)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffe00025323a-ffffffe000253432: vfs_fallocate (STB_GLOBAL)
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
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cfec0)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff812cfec0-ffffffff812d0155: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c0b40)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff812c0b40-ffffffff812c0dd5: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cdcd0)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff812cdcd0-ffffffff812cdf65: vfs_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812deae0)
Location: fs/open.c:233
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - fs/open.c:ksys_fallocate
  - fs/ioctl.c:ioctl_preallocate
```
**Symbols:**

```
ffffffff812deae0-ffffffff812ded75: vfs_fallocate (STB_GLOBAL)
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
