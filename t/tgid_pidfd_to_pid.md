# Function: <code>tgid_pidfd_to_pid</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135ec50)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff8135ec50-ffffffff8135ec76: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81376eb0)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff81376eb0-ffffffff81376ed6: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813bfd20)
Location: fs/proc/base.c:3268
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff813bfd20-ffffffff813bfd46: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d1bb0)
Location: fs/proc/base.c:3285
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff813d1bb0-ffffffff813d1bd6: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d8aa0)
Location: fs/proc/base.c:3297
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff813d8aa0-ffffffff813d8ac6: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8142a1d0)
Location: fs/proc/base.c:3303
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff8142a1d0-ffffffff8142a1f6: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a36d0)
Location: fs/proc/base.c:3351
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff814a36d0-ffffffff814a3702: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815389c0)
Location: fs/proc/base.c:3367
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff815389c0-ffffffff815389f2: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81570c00)
Location: fs/proc/base.c:3369
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff81570c00-ffffffff81570c38: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a95a0)
Location: fs/proc/base.c:3376
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff815a95a0-ffffffff815a95d8: tgid_pidfd_to_pid (STB_GLOBAL)
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
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff800010442688)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
**Symbols:**

```
ffff800010442688-ffff8000104426dc: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0607df8)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
c0607df8-c0607e2c: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000557d50)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
c000000000557d50-c000000000557d8c: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d9264)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffe0002d9264-ffffffe0002d929a: tgid_pidfd_to_pid (STB_GLOBAL)
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
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136f490)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff8136f490-ffffffff8136f4b6: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135ff20)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff8135ff20-ffffffff8135ff46: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136cf60)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff8136cf60-ffffffff8136cf86: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pid *tgid_pidfd_to_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81380880)
Location: fs/proc/base.c:3128
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff81380880-ffffffff813808a6: tgid_pidfd_to_pid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
