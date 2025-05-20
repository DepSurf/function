# Function: <code>compat_ioctl_preallocate</code>

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
In fs/compat_ioctl.c (ffffffff81266a1f)
Location: fs/compat_ioctl.c:790
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81292d42)
Location: fs/compat_ioctl.c:812
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812a7ac2)
Location: fs/compat_ioctl.c:812
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812b42d4)
Location: fs/compat_ioctl.c:811
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812d79ff)
Location: fs/compat_ioctl.c:704
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, struct space_resv_32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81302790)
Location: fs/compat_ioctl.c:702
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81302790-ffffffff81302956: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, struct space_resv_32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81317e20)
Location: fs/compat_ioctl.c:487
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81317e20-ffffffff81317fe6: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, struct space_resv_32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8133f6f0)
Location: fs/compat_ioctl.c:487
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8133f6f0-ffffffff8133f8c1: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, struct space_resv_32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81357ce0)
Location: fs/compat_ioctl.c:487
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81357ce0-ffffffff81357eb1: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, int mode, struct space_resv_32 *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8132b520)
Location: fs/ioctl.c:501
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8132b520-ffffffff8132b5d4: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, int mode, struct space_resv_32 *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81336ae0)
Location: fs/ioctl.c:501
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81336ae0-ffffffff81336b94: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, int mode, struct space_resv_32 *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133cc40)
Location: fs/ioctl.c:504
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8133cc40-ffffffff8133ccf4: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, int mode, struct space_resv_32 *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138aa80)
Location: fs/ioctl.c:301
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8138aa80-ffffffff8138ab34: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, int mode, struct space_resv_32 *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140bcc0)
Location: fs/ioctl.c:297
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8140bcc0-ffffffff8140bda9: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, int mode, struct space_resv_32 *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814966c0)
Location: fs/ioctl.c:297
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
**Symbols:**

```
ffffffff814966c0-ffffffff814967a9: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, int mode, struct space_resv_32 *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cb700)
Location: fs/ioctl.c:297
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
**Symbols:**

```
ffffffff814cb700-ffffffff814cb7ea: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, int mode, struct space_resv_32 *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fdfb0)
Location: fs/ioctl.c:298
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
**Symbols:**

```
ffffffff814fdfb0-ffffffff814fe09a: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
int compat_ioctl_preallocate(struct file *file, struct space_resv_32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff813502c0)
Location: fs/compat_ioctl.c:487
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff813502c0-ffffffff81350491: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, struct space_resv_32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81340fa0)
Location: fs/compat_ioctl.c:487
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81340fa0-ffffffff81341171: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, struct space_resv_32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8134dd90)
Location: fs/compat_ioctl.c:487
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8134dd90-ffffffff8134df61: compat_ioctl_preallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_ioctl_preallocate(struct file *file, struct space_resv_32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81361310)
Location: fs/compat_ioctl.c:487
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81361310-ffffffff813614e1: compat_ioctl_preallocate (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int mode</code>
</li>
<li>
<b>Param added. </b>
<code>struct space_resv_32 *argp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct space_resv_32 *p32</code>
</li>
</ul>
</details>
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
