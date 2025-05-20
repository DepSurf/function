# Function: <code>receive_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8472)
Location: include/linux/file.h:104
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9f1e)
Location: include/linux/file.h:104
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/seccomp.c (ffffffff811a4126)
Location: include/linux/file.h:104
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int receive_fd(struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398cb0)
Location: fs/file.c:1198
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
```
**Symbols:**

```
ffffffff81398cb0-ffffffff81398d26: receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int receive_fd(struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141b510)
Location: fs/file.c:1200
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
```
**Symbols:**

```
ffffffff8141b510-ffffffff8141b59b: receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int receive_fd(struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a75f0)
Location: fs/file.c:1210
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
```
**Symbols:**

```
ffffffff814a75f0-ffffffff814a767b: receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int receive_fd(struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dc5d0)
Location: fs/file.c:1225
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
```
**Symbols:**

```
ffffffff814dc5d0-ffffffff814dc65b: receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int receive_fd(struct file *file, int *ufd, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150e7d0)
Location: fs/file.c:1314
Inline: True
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - io_uring/openclose.c:io_install_fixed_fd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff8150e7d0-ffffffff8150e885: receive_fd (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *ufd</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, o_flags</code> ➡️ <code>file, ufd, o_flags</code>
</li>
</ul>
</details>
</li>
</ul>
