# Function: <code>tid_fd_mode</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81322d30)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81322d30-ffffffff81322da0: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81339e80)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81339e80-ffffffff81339ef0: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81362020)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81362020-ffffffff81362090: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8137a280)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8137a280-ffffffff8137a2f0: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813c35d0)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813c35d0-ffffffff813c3633: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813d582b)
Location: fs/proc/fd.c:85
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813dc775)
Location: fs/proc/fd.c:85
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8142dd65)
Location: fs/proc/fd.c:99
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff814a77c6)
Location: fs/proc/fd.c:109
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8153cfe6)
Location: fs/proc/fd.c:110
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff815752b6)
Location: fs/proc/fd.c:111
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff815adb7c)
Location: fs/proc/fd.c:111
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
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
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffff8000104464f8)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffff8000104464f8-ffff8000104465a0: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (c060b694)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
c060b694-c060b708: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (c00000000055c1d0)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
c00000000055c1d0-c00000000055c2b4: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffe0002dc45a)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffe0002dc45a-ffffffe0002dc4e6: tid_fd_mode (STB_LOCAL)
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
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81372860)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81372860-ffffffff813728d0: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81363330)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81363330-ffffffff813633a0: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81370330)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81370330-ffffffff813703a0: tid_fd_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct *task, unsigned int fd, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81383ce0)
Location: fs/proc/fd.c:84
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81383ce0-ffffffff81383d55: tid_fd_mode (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
