# Function: <code>vfs_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812200ea)
Location: fs/ioctl.c:35
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81247829)
Location: fs/ioctl.c:36
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812476b0-ffffffff812476e4: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8125a869)
Location: fs/ioctl.c:36
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff8125a6f0-ffffffff8125a724: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8126726c)
Location: fs/ioctl.c:38
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812670f0-ffffffff81267124: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81289afc)
Location: fs/ioctl.c:39
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff81289980-ffffffff812899b7: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812afe8c)
Location: fs/ioctl.c:39
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812afd10-ffffffff812afd47: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812c4fcc)
Location: fs/ioctl.c:39
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812c4900-ffffffff812c4937: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e1d7a)
Location: fs/ioctl.c:39
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812e1340-ffffffff812e1377: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812f384a)
Location: fs/ioctl.c:40
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812f2de0-ffffffff812f2e17: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8132c202)
Location: fs/ioctl.c:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8132b070-ffffffff8132b0a7: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81337626)
Location: fs/ioctl.c:41
Inline: True
Inline callers:
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81336630-ffffffff81336667: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133dc56)
Location: fs/ioctl.c:44
Inline: True
Inline callers:
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8133c7d0-ffffffff8133c807: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138b5d6)
Location: fs/ioctl.c:44
Inline: True
Inline callers:
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8138a4d0-ffffffff8138a507: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140c914)
Location: fs/ioctl.c:44
Inline: True
Inline callers:
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8140b5d0-ffffffff8140b625: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81497394)
Location: fs/ioctl.c:44
Inline: True
Inline callers:
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81495f30-ffffffff81495f85: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cc3e4)
Location: fs/ioctl.c:44
Inline: True
Inline callers:
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff814caf70-ffffffff814cafc8: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814feca4)
Location: fs/ioctl.c:44
Inline: True
Inline callers:
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff814fd820-ffffffff814fd878: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffff80001039ec70)
Location: fs/ioctl.c:40
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffff80001039d6b0-ffff80001039d720: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c0583b74)
Location: fs/ioctl.c:40
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:file_ioctl
```
**Symbols:**

```
c0582c5c-c0582c9c: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c000000000499440)
Location: fs/ioctl.c:40
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
c000000000498210-c000000000498278: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffe000269a7c)
Location: fs/ioctl.c:40
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffe0002694c4-ffffffe000269518: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812ebe2a)
Location: fs/ioctl.c:40
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812eb3c0-ffffffff812eb3f7: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812dca5a)
Location: fs/ioctl.c:40
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812dbff0-ffffffff812dc027: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e9c3a)
Location: fs/ioctl.c:40
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812e91d0-ffffffff812e9207: vfs_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int vfs_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812fac38)
Location: fs/ioctl.c:40
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff812fa1d0-ffffffff812fa207: vfs_ioctl (STB_GLOBAL)
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
