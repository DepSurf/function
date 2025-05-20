# Function: <code>selinux_task_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813426e0)
Location: security/selinux/hooks.c:3744
Inline: False
```
**Symbols:**

```
ffffffff813426e0-ffffffff81342738: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81377ac0)
Location: security/selinux/hooks.c:3875
Inline: False
```
**Symbols:**

```
ffffffff81377ac0-ffffffff81377b18: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138e5b0)
Location: security/selinux/hooks.c:3947
Inline: False
```
**Symbols:**

```
ffffffff8138e5b0-ffffffff8138e608: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a4220)
Location: security/selinux/hooks.c:3930
Inline: False
```
**Symbols:**

```
ffffffff813a4220-ffffffff813a428c: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ca300)
Location: security/selinux/hooks.c:3945
Inline: False
```
**Symbols:**

```
ffffffff813ca300-ffffffff813ca36c: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813f96b0)
Location: security/selinux/hooks.c:4177
Inline: False
```
**Symbols:**

```
ffffffff813f96b0-ffffffff813f9727: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81415540)
Location: security/selinux/hooks.c:3897
Inline: False
```
**Symbols:**

```
ffffffff81415540-ffffffff814155c7: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81442e80)
Location: security/selinux/hooks.c:4085
Inline: False
```
**Symbols:**

```
ffffffff81442e80-ffffffff81442f07: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145c9c0)
Location: security/selinux/hooks.c:4143
Inline: False
```
**Symbols:**

```
ffffffff8145c9c0-ffffffff8145ca4f: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814afd90)
Location: security/selinux/hooks.c:4136
Inline: False
```
**Symbols:**

```
ffffffff814afd90-ffffffff814afe1f: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d1220)
Location: security/selinux/hooks.c:4152
Inline: False
```
**Symbols:**

```
ffffffff814d1220-ffffffff814d12c7: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d7670)
Location: security/selinux/hooks.c:4316
Inline: False
```
**Symbols:**

```
ffffffff814d7670-ffffffff814d771a: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815303c0)
Location: security/selinux/hooks.c:4301
Inline: False
```
**Symbols:**

```
ffffffff815303c0-ffffffff8153046a: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c7400)
Location: security/selinux/hooks.c:4197
Inline: False
```
**Symbols:**

```
ffffffff815c7400-ffffffff815c74c5: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81674290)
Location: security/selinux/hooks.c:4215
Inline: False
```
**Symbols:**

```
ffffffff81674290-ffffffff81674355: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ac4e0)
Location: security/selinux/hooks.c:4177
Inline: False
```
**Symbols:**

```
ffffffff816ac4e0-ffffffff816ac598: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e9840)
Location: security/selinux/hooks.c:4265
Inline: False
```
**Symbols:**

```
ffffffff816e9840-ffffffff816e9901: selinux_task_kill (STB_LOCAL)
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
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff8000105496d8)
Location: security/selinux/hooks.c:4143
Inline: False
```
**Symbols:**

```
ffff8000105496d8-ffff800010549798: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06ff418)
Location: security/selinux/hooks.c:4143
Inline: False
```
**Symbols:**

```
c06ff418-c06ff4bc: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a0c70)
Location: security/selinux/hooks.c:4143
Inline: False
```
**Symbols:**

```
c0000000006a0c70-c0000000006a0d84: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a4564)
Location: security/selinux/hooks.c:4143
Inline: False
```
**Symbols:**

```
ffffffe0003a4564-ffffffe0003a4606: selinux_task_kill (STB_LOCAL)
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
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81454fa0)
Location: security/selinux/hooks.c:4143
Inline: False
```
**Symbols:**

```
ffffffff81454fa0-ffffffff8145502f: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814459e0)
Location: security/selinux/hooks.c:4143
Inline: False
```
**Symbols:**

```
ffffffff814459e0-ffffffff81445a6f: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81451040)
Location: security/selinux/hooks.c:4143
Inline: False
```
**Symbols:**

```
ffffffff81451040-ffffffff814510cf: selinux_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81469b60)
Location: security/selinux/hooks.c:4143
Inline: False
```
**Symbols:**

```
ffffffff81469b60-ffffffff81469c16: selinux_task_kill (STB_LOCAL)
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
