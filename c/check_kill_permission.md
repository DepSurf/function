# Function: <code>check_kill_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108cfb0)
Location: kernel/signal.c:713
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
```
**Symbols:**

```
ffffffff8108cfb0-ffffffff8108d10b: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090180)
Location: kernel/signal.c:713
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
```
**Symbols:**

```
ffffffff81090180-ffffffff810902c4: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095100)
Location: kernel/signal.c:719
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
```
**Symbols:**

```
ffffffff81095100-ffffffff81095244: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092180)
Location: kernel/signal.c:733
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
```
**Symbols:**

```
ffffffff81092180-ffffffff81092273: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099010)
Location: kernel/signal.c:735
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
```
**Symbols:**

```
ffffffff81099010-ffffffff81099103: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c830)
Location: kernel/signal.c:741
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
```
**Symbols:**

```
ffffffff8109c830-ffffffff8109c922: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a4b00)
Location: kernel/signal.c:812
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:group_send_sig_info
```
**Symbols:**

```
ffffffff810a4b00-ffffffff810a4bee: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a97e0)
Location: kernel/signal.c:822
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:group_send_sig_info
```
**Symbols:**

```
ffffffff810a97e0-ffffffff810a98dc: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afd70)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:group_send_sig_info
```
**Symbols:**

```
ffffffff810afd70-ffffffff810afe6c: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b77d0)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff810b77d0-ffffffff810b78cc: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2a60)
Location: kernel/signal.c:828
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff810b2a60-ffffffff810b2b5c: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b40a0)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff810b40a0-ffffffff810b419c: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c6360)
Location: kernel/signal.c:828
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff810c6360-ffffffff810c645c: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ddc90)
Location: kernel/signal.c:834
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff810ddc90-ffffffff810dddb3: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fe0f0)
Location: kernel/signal.c:834
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff810fe0f0-ffffffff810fe213: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110a1b0)
Location: kernel/signal.c:839
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff8110a1b0-ffffffff8110a2d3: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81113b50)
Location: kernel/signal.c:830
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff81113b50-ffffffff81113c73: check_kill_permission (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010aab8)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:group_send_sig_info
```
**Symbols:**

```
ffff80001010aab8-ffff80001010abd8: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036424c)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:group_send_sig_info
```
**Symbols:**

```
c036424c-c0364374: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000152530)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
```
**Symbols:**

```
c000000000152530-c0000000001526d8: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cd926)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
```
**Symbols:**

```
ffffffe0000cd926-ffffffe0000cd9f4: check_kill_permission (STB_LOCAL)
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
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa0e0)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:group_send_sig_info
```
**Symbols:**

```
ffffffff810aa0e0-ffffffff810aa1dc: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098af0)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:group_send_sig_info
```
**Symbols:**

```
ffffffff81098af0-ffffffff81098bec: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9640)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:group_send_sig_info
```
**Symbols:**

```
ffffffff810a9640-ffffffff810a973c: check_kill_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int check_kill_permission(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1960)
Location: kernel/signal.c:827
Inline: True
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:group_send_sig_info
```
**Symbols:**

```
ffffffff810b1960-ffffffff810b1a5c: check_kill_permission (STB_LOCAL)
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
