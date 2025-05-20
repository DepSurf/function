# Function: <code>copy_siginfo_from_user</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa7c0)
Location: kernel/signal.c:3096
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810aa7c0-ffffffff810aa80b: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af850)
Location: kernel/signal.c:3225
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810af850-ffffffff810af89b: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5e70)
Location: kernel/signal.c:3230
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810b5e70-ffffffff810b5ebb: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810be380)
Location: kernel/signal.c:3248
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810be380-ffffffff810be42f: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9680)
Location: kernel/signal.c:3268
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810b9680-ffffffff810b972f: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bae50)
Location: kernel/signal.c:3296
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810bae50-ffffffff810baeff: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cd740)
Location: kernel/signal.c:3384
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810cd740-ffffffff810cd80a: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e5ce2)
Location: kernel/signal.c:3364
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810e56e0-ffffffff810e5724: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110693a)
Location: kernel/signal.c:3366
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81106240-ffffffff81106284: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81112c2a)
Location: kernel/signal.c:3390
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81112520-ffffffff81112564: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111c61a)
Location: kernel/signal.c:3401
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8111bf10-ffffffff8111bf54: copy_siginfo_from_user (STB_GLOBAL)
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
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010112140)
Location: kernel/signal.c:3230
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
**Symbols:**

```
ffff800010112140-ffff800010112238: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0369258)
Location: kernel/signal.c:3230
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
c0369258-c0369314: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000159c40)
Location: kernel/signal.c:3230
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
c000000000159c40-c000000000159ce8: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d12e6)
Location: kernel/signal.c:3230
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffe0000d12e6-ffffffe0000d1340: copy_siginfo_from_user (STB_GLOBAL)
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
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b01e0)
Location: kernel/signal.c:3230
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810b01e0-ffffffff810b022b: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109eb00)
Location: kernel/signal.c:3230
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff8109eb00-ffffffff8109eb4b: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af740)
Location: kernel/signal.c:3230
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810af740-ffffffff810af78b: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7a10)
Location: kernel/signal.c:3230
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810b7a10-ffffffff810b7a5b: copy_siginfo_from_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
