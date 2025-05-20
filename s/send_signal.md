# Function: <code>send_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int send_signal(int sig, struct siginfo *info, struct task_struct *t, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108e830)
Location: kernel/signal.c:1076
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:do_send_sig_info
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff8108e830-ffffffff8108e8a5: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int send_signal(int sig, struct siginfo *info, struct task_struct *t, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810918b0)
Location: kernel/signal.c:1076
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810918b0-ffffffff81091925: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int send_signal(int sig, struct siginfo *info, struct task_struct *t, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096840)
Location: kernel/signal.c:1082
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff81096840-ffffffff810968b5: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int send_signal(int sig, struct siginfo *info, struct task_struct *t, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093b60)
Location: kernel/signal.c:1096
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff81093b60-ffffffff81093bd5: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int send_signal(int sig, struct siginfo *info, struct task_struct *t, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109aa50)
Location: kernel/signal.c:1097
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff8109aa50-ffffffff8109aac5: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int send_signal(int sig, struct siginfo *info, struct task_struct *t, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e960)
Location: kernel/signal.c:1105
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff8109e960-ffffffff8109e9d5: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a6c70)
Location: kernel/signal.c:1194
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810a6c70-ffffffff810a6ce5: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0ebe)
Location: kernel/signal.c:1203
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810ac9e0-ffffffff810acafd: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b760e)
Location: kernel/signal.c:1208
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810b2ff0-ffffffff810b310d: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bf55e)
Location: kernel/signal.c:1208
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810bbcc0-ffffffff810bbddd: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba75e)
Location: kernel/signal.c:1209
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810b6f80-ffffffff810b70ab: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bc08e)
Location: kernel/signal.c:1211
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810b8580-ffffffff810b86ab: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cea7c)
Location: kernel/signal.c:1212
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810caa70-ffffffff810cab9b: send_signal (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010113ac4)
Location: kernel/signal.c:1208
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffff80001010ee48-ffff80001010ef5c: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036aa68)
Location: kernel/signal.c:1208
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
c0366b74-c0366cac: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015b780)
Location: kernel/signal.c:1208
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
c0000000001561f0-c0000000001563fc: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf4c8)
Location: kernel/signal.c:1208
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffe0000cf4c8-ffffffe0000cf5b0: send_signal (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b197e)
Location: kernel/signal.c:1208
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810ad360-ffffffff810ad47d: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a029e)
Location: kernel/signal.c:1208
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff8109bce0-ffffffff8109bdfd: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0ede)
Location: kernel/signal.c:1208
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810ac8c0-ffffffff810ac9dd: send_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int send_signal(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b91b0)
Location: kernel/signal.c:1208
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:do_send_sig_info
```
**Symbols:**

```
ffffffff810b4a30-ffffffff810b4b65: send_signal (STB_LOCAL)
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
