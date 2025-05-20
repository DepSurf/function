# Function: <code>do_ioctl_trans</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_ioctl_trans(int fd, unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81265b40)
Location: fs/compat_ioctl.c:1439
Inline: False
Direct callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff81265b40-ffffffff81266845: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81291d40)
Location: fs/compat_ioctl.c:1447
Inline: False
Direct callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff81291d40-ffffffff81292b95: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812a6ac0)
Location: fs/compat_ioctl.c:1449
Inline: False
Direct callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff812a6ac0-ffffffff812a7915: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812b30a0)
Location: fs/compat_ioctl.c:1442
Inline: False
Direct callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff812b30a0-ffffffff812b40b5: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812d6ba0)
Location: fs/compat_ioctl.c:1326
Inline: False
Direct callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff812d6ba0-ffffffff812d7943: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff813019f0)
Location: fs/compat_ioctl.c:1312
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff813019f0-ffffffff81302783: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff813174e0)
Location: fs/compat_ioctl.c:930
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff813174e0-ffffffff81317e1a: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8133f070)
Location: fs/compat_ioctl.c:927
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8133f070-ffffffff8133f6ee: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81357380)
Location: fs/compat_ioctl.c:927
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81357380-ffffffff81357cd6: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffff80001041d1e0)
Location: fs/compat_ioctl.c:927
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (c00000000052b260)
Location: fs/compat_ioctl.c:927
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
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
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8134f960)
Location: fs/compat_ioctl.c:927
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8134f960-ffffffff813502b6: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81340640)
Location: fs/compat_ioctl.c:927
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81340640-ffffffff81340f96: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8134d430)
Location: fs/compat_ioctl.c:927
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8134d430-ffffffff8134dd86: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_ioctl_trans(unsigned int cmd, long unsigned int arg, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff813609b0)
Location: fs/compat_ioctl.c:927
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff813609b0-ffffffff81361306: do_ioctl_trans (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int fd</code>
</li>
<li>
<b>Param reordered. </b>
<code>fd, cmd, arg, file</code> ➡️ <code>cmd, arg, file</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
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
