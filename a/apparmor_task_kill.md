# Function: <code>apparmor_task_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813869a0)
Location: security/apparmor/lsm.c:1147
Inline: True
```
**Symbols:**

```
ffffffff813869a0-ffffffff81386b3b: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813c12b0)
Location: security/apparmor/lsm.c:1123
Inline: True
```
**Symbols:**

```
ffffffff813c12b0-ffffffff813c14b8: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813d8750)
Location: security/apparmor/lsm.c:1126
Inline: True
```
**Symbols:**

```
ffffffff813d8750-ffffffff813d8958: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813e8e70)
Location: security/apparmor/lsm.c:726
Inline: True
```
**Symbols:**

```
ffffffff813e8e70-ffffffff813e8f69: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81410c00)
Location: security/apparmor/lsm.c:698
Inline: True
```
**Symbols:**

```
ffffffff81410c00-ffffffff81410d3e: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81443830)
Location: security/apparmor/lsm.c:736
Inline: True
```
**Symbols:**

```
ffffffff81443830-ffffffff81443a72: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81460110)
Location: security/apparmor/lsm.c:722
Inline: True
```
**Symbols:**

```
ffffffff81460110-ffffffff81460377: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148d040)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
ffffffff8148d040-ffffffff8148d264: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a6f00)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
ffffffff814a6f00-ffffffff814a7124: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff815048e0)
Location: security/apparmor/lsm.c:779
Inline: False
```
**Symbols:**

```
ffffffff815048e0-ffffffff81504bde: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81520b50)
Location: security/apparmor/lsm.c:779
Inline: False
```
**Symbols:**

```
ffffffff81520b50-ffffffff81520e55: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81526e00)
Location: security/apparmor/lsm.c:788
Inline: False
```
**Symbols:**

```
ffffffff81526e00-ffffffff81527122: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81585090)
Location: security/apparmor/lsm.c:788
Inline: False
```
**Symbols:**

```
ffffffff81585090-ffffffff815853b2: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816260c0)
Location: security/apparmor/lsm.c:991
Inline: True
```
**Symbols:**

```
ffffffff816260c0-ffffffff816263fb: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816da720)
Location: security/apparmor/lsm.c:1042
Inline: False
```
**Symbols:**

```
ffffffff816da720-ffffffff816dab4f: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81713ec0)
Location: security/apparmor/lsm.c:1190
Inline: False
```
**Symbols:**

```
ffffffff81713ec0-ffffffff81714275: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81752970)
Location: security/apparmor/lsm.c:1218
Inline: False
```
**Symbols:**

```
ffffffff81752970-ffffffff81752d17: apparmor_task_kill (STB_LOCAL)
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
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059d650)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
ffff80001059d650-ffff80001059d890: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074ea78)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
c074ea78-c074ecdc: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c000000000714fe0)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
c000000000714fe0-c0000000007152fc: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e93dc)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
ffffffe0003e93dc-ffffffe0003e9588: apparmor_task_kill (STB_LOCAL)
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
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149f4e0)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
ffffffff8149f4e0-ffffffff8149f704: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148ff00)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
ffffffff8148ff00-ffffffff81490124: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149b580)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
ffffffff8149b580-ffffffff8149b7a4: apparmor_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int apparmor_task_kill(struct task_struct *target, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b3860)
Location: security/apparmor/lsm.c:718
Inline: True
```
**Symbols:**

```
ffffffff814b3860-ffffffff814b3b13: apparmor_task_kill (STB_LOCAL)
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
