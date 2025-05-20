# Function: <code>__send_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo *info, struct task_struct *t, int group, int from_ancestor_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108e3e0)
Location: kernel/signal.c:972
Inline: False
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/signal.c:kill_pid_info_as_cred
```
**Symbols:**

```
ffffffff8108e3e0-ffffffff8108e825: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo *info, struct task_struct *t, int group, int from_ancestor_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091460)
Location: kernel/signal.c:972
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:send_signal
```
**Symbols:**

```
ffffffff81091460-ffffffff810918ae: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo *info, struct task_struct *t, int group, int from_ancestor_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810963f0)
Location: kernel/signal.c:978
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:send_signal
```
**Symbols:**

```
ffffffff810963f0-ffffffff8109683e: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo *info, struct task_struct *t, int group, int from_ancestor_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810936c0)
Location: kernel/signal.c:992
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:send_signal
```
**Symbols:**

```
ffffffff810936c0-ffffffff81093b5c: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo *info, struct task_struct *t, int group, int from_ancestor_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a5b0)
Location: kernel/signal.c:994
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:send_signal
```
**Symbols:**

```
ffffffff8109a5b0-ffffffff8109aa4e: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo *info, struct task_struct *t, int group, int from_ancestor_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e4c0)
Location: kernel/signal.c:1000
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:send_signal
```
**Symbols:**

```
ffffffff8109e4c0-ffffffff8109e960: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, int from_ancestor_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a67e0)
Location: kernel/signal.c:1075
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:send_signal
```
**Symbols:**

```
ffffffff810a67e0-ffffffff810a6c69: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab510)
Location: kernel/signal.c:1065
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810ab510-ffffffff810ab8f6: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1b20)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810b1b20-ffffffff810b1f06: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba130)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810ba130-ffffffff810ba507: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b53e0)
Location: kernel/signal.c:1071
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810b53e0-ffffffff810b57b0: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6fd0)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810b6fd0-ffffffff810b73a8: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1071
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810c8650-ffffffff810c8a61: __send_signal (STB_LOCAL)
ffffffff81ca4781-ffffffff81ca481f: __send_signal.cold (STB_LOCAL)
```
</details>
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
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010d778)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffff80001010d778-ffff80001010db0c: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0365b04)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
c0365b04-c0365f20: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000154a20)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
c000000000154a20-c000000000154ec8: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce99c)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:send_signal
```
**Symbols:**

```
ffffffe0000ce99c-ffffffe0000cec84: __send_signal (STB_LOCAL)
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
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abe90)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810abe90-ffffffff810ac276: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a820)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff8109a820-ffffffff8109ac06: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab3f0)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810ab3f0-ffffffff810ab7d6: __send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b34d0)
Location: kernel/signal.c:1070
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810b34d0-ffffffff810b38f3: __send_signal (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pid_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>int group</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct siginfo *info</code> ➡️ <code>struct kernel_siginfo *info</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force</code>
</li>
<li>
<b>Param removed. </b>
<code>int from_ancestor_ns</code>
</li>
</ul>
</details>
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
