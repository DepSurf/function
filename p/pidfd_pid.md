# Function: <code>pidfd_pid</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0270)
Location: kernel/fork.c:1682
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810a0270-ffffffff810a0295: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a7150)
Location: kernel/fork.c:1707
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810a7150-ffffffff810a7175: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2e20)
Location: kernel/fork.c:1703
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810a2e20-ffffffff810a2e45: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3a20)
Location: kernel/fork.c:1702
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810a3a20-ffffffff810a3a45: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5240)
Location: kernel/fork.c:1781
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810b5240-ffffffff810b5265: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cb530)
Location: kernel/fork.c:1826
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810cb530-ffffffff810cb561: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e8b00)
Location: kernel/fork.c:1848
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810e8b00-ffffffff810e8b31: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f30a0)
Location: kernel/fork.c:1996
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810f30a0-ffffffff810f30d4: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fc450)
Location: kernel/fork.c:1993
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810fc450-ffffffff810fc484: pidfd_pid (STB_GLOBAL)
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
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f4ab0)
Location: kernel/fork.c:1682
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
**Symbols:**

```
ffff8000100f4ab0-ffff8000100f4b00: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0353278)
Location: kernel/fork.c:1682
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
c0353278-c03532a8: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013aac0)
Location: kernel/fork.c:1682
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
c00000000013aac0-c00000000013aaf8: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c1278)
Location: kernel/fork.c:1682
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffe0000c1278-ffffffe0000c12b4: pidfd_pid (STB_GLOBAL)
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
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099b90)
Location: kernel/fork.c:1682
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff81099b90-ffffffff81099bb5: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810885d0)
Location: kernel/fork.c:1682
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810885d0-ffffffff810885f5: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099b40)
Location: kernel/fork.c:1682
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff81099b40-ffffffff81099b65: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pid *pidfd_pid(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1790)
Location: kernel/fork.c:1682
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810a1790-ffffffff810a17b5: pidfd_pid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
