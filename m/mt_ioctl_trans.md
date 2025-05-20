# Function: <code>mt_ioctl_trans</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mt_ioctl_trans(unsigned int fd, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812659e0)
Location: fs/compat_ioctl.c:515
Inline: False
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
**Symbols:**

```
ffffffff812659e0-ffffffff81265b3b: mt_ioctl_trans (STB_LOCAL)
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
In fs/compat_ioctl.c (ffffffff8129287b)
Location: fs/compat_ioctl.c:537
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff812a75fb)
Location: fs/compat_ioctl.c:537
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff812b3d3b)
Location: fs/compat_ioctl.c:537
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff812d763b)
Location: fs/compat_ioctl.c:520
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81302767)
Location: fs/compat_ioctl.c:518
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81317cc6)
Location: fs/compat_ioctl.c:382
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8133f172)
Location: fs/compat_ioctl.c:382
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8135747a)
Location: fs/compat_ioctl.c:382
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int mt_ioctl_trans(struct file *file, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffff80001041b8c0)
Location: fs/compat_ioctl.c:382
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
**Symbols:**

```
ffff80001041b8c0-ffff80001041c490: mt_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mt_ioctl_trans(struct file *file, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (c000000000529d20)
Location: fs/compat_ioctl.c:382
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
```
**Symbols:**

```
c000000000529d20-c00000000052a684: mt_ioctl_trans (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8134fa5a)
Location: fs/compat_ioctl.c:382
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8134073a)
Location: fs/compat_ioctl.c:382
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8134d52a)
Location: fs/compat_ioctl.c:382
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81360aaa)
Location: fs/compat_ioctl.c:382
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
