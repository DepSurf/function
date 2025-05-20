# Function: <code>do_vfs_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8121fe60)
Location: fs/ioctl.c:555
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff8121fe60-ffffffff812202e9: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812477a0)
Location: fs/ioctl.c:618
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff812477a0-ffffffff81247da4: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8125a7e0)
Location: fs/ioctl.c:622
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff8125a7e0-ffffffff8125ade4: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812671e0)
Location: fs/ioctl.c:624
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff812671e0-ffffffff812677e9: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81289a70)
Location: fs/ioctl.c:625
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff81289a70-ffffffff8128a091: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812afe00)
Location: fs/ioctl.c:625
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff812afe00-ffffffff812b0417: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812c4f40)
Location: fs/ioctl.c:634
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff812c4f40-ffffffff812c5573: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e1990)
Location: fs/ioctl.c:634
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff812e1990-ffffffff812e1ff2: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812f3460)
Location: fs/ioctl.c:635
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff812f3460-ffffffff812f3ac2: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8132bb30)
Location: fs/ioctl.c:667
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:ksys_ioctl
```
**Symbols:**

```
ffffffff8132bb30-ffffffff8132bfe1: do_vfs_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff813370f0)
Location: fs/ioctl.c:667
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff813370f0-ffffffff813375a2: do_vfs_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ioctl.c (0)
Location: fs/ioctl.c:971
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff8133d3d0-ffffffff8133dbd6: do_vfs_ioctl (STB_LOCAL)
ffffffff81bdc6a7-ffffffff81bdc6de: do_vfs_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ioctl.c (0)
Location: fs/ioctl.c:776
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff8138ad50-ffffffff8138b556: do_vfs_ioctl (STB_LOCAL)
ffffffff81cc3aa8-ffffffff81cc3adf: do_vfs_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ioctl.c (0)
Location: fs/ioctl.c:772
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff8140bfd0-ffffffff8140c88a: do_vfs_ioctl (STB_LOCAL)
ffffffff81e762c9-ffffffff81e76300: do_vfs_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81496a00)
Location: fs/ioctl.c:772
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff81496a00-ffffffff814972fd: do_vfs_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cba40)
Location: fs/ioctl.c:772
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff814cba40-ffffffff814cc34b: do_vfs_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fe2f0)
Location: fs/ioctl.c:773
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff814fe2f0-ffffffff814fec0a: do_vfs_ioctl (STB_LOCAL)
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
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffff80001039e238)
Location: fs/ioctl.c:635
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
**Symbols:**

```
ffff80001039e238-ffff80001039f08c: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c0583774)
Location: fs/ioctl.c:635
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
```
**Symbols:**

```
c0583774-c0583f68: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c000000000498ad0)
Location: fs/ioctl.c:635
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
```
**Symbols:**

```
c000000000498ad0-c0000000004996d8: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffe0002699a2)
Location: fs/ioctl.c:635
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
```
**Symbols:**

```
ffffffe0002699a2-ffffffe000269f6a: do_vfs_ioctl (STB_GLOBAL)
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
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812eba40)
Location: fs/ioctl.c:635
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff812eba40-ffffffff812ec0a2: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812dc670)
Location: fs/ioctl.c:635
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff812dc670-ffffffff812dccd2: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e9850)
Location: fs/ioctl.c:635
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff812e9850-ffffffff812e9eb2: do_vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_vfs_ioctl(struct file *filp, unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812fa850)
Location: fs/ioctl.c:635
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff812fa850-ffffffff812faeb0: do_vfs_ioctl (STB_GLOBAL)
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
