# Function: <code>__receive_fd</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int __receive_fd(int fd, struct file *file, int *ufd, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813458c0)
Location: fs/file.c:1088
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff813458c0-ffffffff813459a0: __receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __receive_fd(struct file *file, int *ufd, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134bc60)
Location: fs/file.c:1098
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff8134bc60-ffffffff8134bd02: __receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __receive_fd(struct file *file, int *ufd, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398cc3)
Location: fs/file.c:1158
Inline: True
Inline callers:
  - fs/file.c:receive_fd
  - fs/file.c:receive_fd
Direct callers:
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff81399aa0-ffffffff81399b42: __receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __receive_fd(struct file *file, int *ufd, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141b523)
Location: fs/file.c:1160
Inline: True
Inline callers:
  - fs/file.c:receive_fd
  - fs/file.c:receive_fd
Direct callers:
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff8141c4e0-ffffffff8141c5e0: __receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __receive_fd(struct file *file, int *ufd, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a7603)
Location: fs/file.c:1170
Inline: True
Inline callers:
  - fs/file.c:receive_fd
  - fs/file.c:receive_fd
Direct callers:
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff814a8610-ffffffff814a86c5: __receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __receive_fd(struct file *file, int *ufd, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dc5e3)
Location: fs/file.c:1185
Inline: True
Inline callers:
  - fs/file.c:receive_fd
  - fs/file.c:receive_fd
Direct callers:
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff814dd600-ffffffff814dd6b5: __receive_fd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int fd</code>
</li>
<li>
<b>Param reordered. </b>
<code>fd, file, ufd, o_flags</code> ➡️ <code>file, ufd, o_flags</code>
</li>
</ul>
</details>
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
</ul>
