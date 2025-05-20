# Function: <code>security_task_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e7e0)
Location: security/security.c:987
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
```
**Symbols:**

```
ffffffff8133e7e0-ffffffff8133e847: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373df0)
Location: security/security.c:1011
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
```
**Symbols:**

```
ffffffff81373df0-ffffffff81373e57: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a720)
Location: security/security.c:1032
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
```
**Symbols:**

```
ffffffff8138a720-ffffffff8138a787: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139fc70)
Location: security/security.c:1675
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
```
**Symbols:**

```
ffffffff8139fc70-ffffffff8139fcd7: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c58b0)
Location: security/security.c:1637
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
```
**Symbols:**

```
ffffffff813c58b0-ffffffff813c591d: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5890)
Location: security/security.c:1141
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
```
**Symbols:**

```
ffffffff813f5890-ffffffff813f58e8: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410ec0)
Location: security/security.c:1749
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
```
**Symbols:**

```
ffffffff81410ec0-ffffffff81410f18: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e700)
Location: security/security.c:1768
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff8143e700-ffffffff8143e765: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458100)
Location: security/security.c:1807
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff81458100-ffffffff81458158: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aaf90)
Location: security/security.c:2003
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff814aaf90-ffffffff814aafe8: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8590)
Location: security/security.c:2020
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff814c8590-ffffffff814c85e8: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cebd0)
Location: security/security.c:2083
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff814cebd0-ffffffff814cec28: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527890)
Location: security/security.c:2091
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff81527890-ffffffff815278e8: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc760)
Location: security/security.c:2097
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff815bc760-ffffffff815bc7dd: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816687f0)
Location: security/security.c:2149
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff816687f0-ffffffff8166886d: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0e40)
Location: security/security.c:3554
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff816a0e40-ffffffff816a0ebd: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd810)
Location: security/security.c:3613
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff816dd810-ffffffff816dd88d: security_task_kill (STB_GLOBAL)
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
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543ee8)
Location: security/security.c:1807
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffff800010543ee8-ffff800010543f5c: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9e40)
Location: security/security.c:1807
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
c06f9e40-c06f9eac: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006987b0)
Location: security/security.c:1807
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
c0000000006987b0-c000000000698894: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a01e8)
Location: security/security.c:1807
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffe0003a01e8-ffffffe0003a023c: security_task_kill (STB_GLOBAL)
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
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814506e0)
Location: security/security.c:1807
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff814506e0-ffffffff81450738: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441130)
Location: security/security.c:1807
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff81441130-ffffffff81441188: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c780)
Location: security/security.c:1807
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff8144c780-ffffffff8144c7d8: security_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463b50)
Location: security/security.c:1807
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff81463b50-ffffffff81463ba8: security_task_kill (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *cred</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 secid</code>
</li>
</ul>
</details>
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
