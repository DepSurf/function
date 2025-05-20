# Function: <code>ioctl_file_clone</code>

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
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81247630)
Location: fs/ioctl.c:218
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81247630-ffffffff812476ad: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8125a610)
Location: fs/ioctl.c:218
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8125a610-ffffffff8125a6f0: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81266fe0)
Location: fs/ioctl.c:220
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81266fe0-ffffffff812670ec: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81289870)
Location: fs/ioctl.c:221
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81289870-ffffffff8128997c: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812afc20)
Location: fs/ioctl.c:221
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812afc20-ffffffff812afd0f: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812c4dd0)
Location: fs/ioctl.c:222
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812c4dd0-ffffffff812c4e8b: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e1820)
Location: fs/ioctl.c:222
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812e1820-ffffffff812e18e0: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812f32f0)
Location: fs/ioctl.c:223
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812f32f0-ffffffff812f33b0: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8132b5e0)
Location: fs/ioctl.c:227
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8132b5e0-ffffffff8132b6a0: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81336ba0)
Location: fs/ioctl.c:227
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81336ba0-ffffffff81336c60: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133cd00)
Location: fs/ioctl.c:230
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8133cd00-ffffffff8133cdbf: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138ab40)
Location: fs/ioctl.c:230
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8138ab40-ffffffff8138abff: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140bdb0)
Location: fs/ioctl.c:230
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8140bdb0-ffffffff8140be62: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814967c0)
Location: fs/ioctl.c:230
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff814967c0-ffffffff81496872: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cb800)
Location: fs/ioctl.c:230
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff814cb800-ffffffff814cb8b2: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fe0b0)
Location: fs/ioctl.c:231
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff814fe0b0-ffffffff814fe162: ioctl_file_clone (STB_LOCAL)
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
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffff80001039d7c0)
Location: fs/ioctl.c:223
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffff80001039d7c0-ffff80001039d8a0: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c0582ccc)
Location: fs/ioctl.c:223
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
c0582ccc-c0582dcc: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c000000000498870)
Location: fs/ioctl.c:223
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
c000000000498870-c0000000004989c0: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffe000269862)
Location: fs/ioctl.c:223
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffe000269862-ffffffe00026990a: ioctl_file_clone (STB_LOCAL)
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
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812eb8d0)
Location: fs/ioctl.c:223
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812eb8d0-ffffffff812eb990: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812dc500)
Location: fs/ioctl.c:223
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812dc500-ffffffff812dc5c0: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e96e0)
Location: fs/ioctl.c:223
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812e96e0-ffffffff812e97a0: ioctl_file_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int ioctl_file_clone(struct file *dst_file, long unsigned int srcfd, u64 off, u64 olen, u64 destoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812fa6e0)
Location: fs/ioctl.c:223
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812fa6e0-ffffffff812fa7a0: ioctl_file_clone (STB_LOCAL)
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
