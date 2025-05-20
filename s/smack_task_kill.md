# Function: <code>smack_task_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8135ee20)
Location: security/smack/smack_lsm.c:2234
Inline: False
```
**Symbols:**

```
ffffffff8135ee20-ffffffff8135eed4: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81395320)
Location: security/smack/smack_lsm.c:2250
Inline: False
```
**Symbols:**

```
ffffffff81395320-ffffffff813953e3: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813abab0)
Location: security/smack/smack_lsm.c:2241
Inline: False
```
**Symbols:**

```
ffffffff813abab0-ffffffff813abb73: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c5020)
Location: security/smack/smack_lsm.c:2167
Inline: False
```
**Symbols:**

```
ffffffff813c5020-ffffffff813c50ee: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct siginfo *info, int sig, u32 secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813eb2f0)
Location: security/smack/smack_lsm.c:2136
Inline: False
```
**Symbols:**

```
ffffffff813eb2f0-ffffffff813eb3be: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8141b850)
Location: security/smack/smack_lsm.c:2253
Inline: False
```
**Symbols:**

```
ffffffff8141b850-ffffffff8141b907: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814381a0)
Location: security/smack/smack_lsm.c:2098
Inline: False
```
**Symbols:**

```
ffffffff814381a0-ffffffff81438264: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81465f30)
Location: security/smack/smack_lsm.c:2185
Inline: False
```
**Symbols:**

```
ffffffff81465f30-ffffffff81465ff3: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147fd10)
Location: security/smack/smack_lsm.c:2182
Inline: False
```
**Symbols:**

```
ffffffff8147fd10-ffffffff8147fdd3: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d54a0)
Location: security/smack/smack_lsm.c:2170
Inline: False
```
**Symbols:**

```
ffffffff814d54a0-ffffffff814d5563: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f2e70)
Location: security/smack/smack_lsm.c:2170
Inline: False
```
**Symbols:**

```
ffffffff814f2e70-ffffffff814f2f62: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f9dd0)
Location: security/smack/smack_lsm.c:2169
Inline: False
```
**Symbols:**

```
ffffffff814f9dd0-ffffffff814f9ec2: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815549b0)
Location: security/smack/smack_lsm.c:2169
Inline: False
```
**Symbols:**

```
ffffffff815549b0-ffffffff81554aa2: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815ee910)
Location: security/smack/smack_lsm.c:2175
Inline: False
```
**Symbols:**

```
ffffffff815ee910-ffffffff815eea20: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169ebb0)
Location: security/smack/smack_lsm.c:2235
Inline: False
```
**Symbols:**

```
ffffffff8169ebb0-ffffffff8169ecc0: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d7720)
Location: security/smack/smack_lsm.c:2298
Inline: False
```
**Symbols:**

```
ffffffff816d7720-ffffffff816d7830: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff817140c0)
Location: security/smack/smack_lsm.c:2351
Inline: False
```
**Symbols:**

```
ffffffff817140c0-ffffffff817141d6: smack_task_kill (STB_LOCAL)
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
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff8000105714e8)
Location: security/smack/smack_lsm.c:2182
Inline: False
```
**Symbols:**

```
ffff8000105714e8-ffff8000105715c4: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c072474c)
Location: security/smack/smack_lsm.c:2182
Inline: False
```
**Symbols:**

```
c072474c-c0724830: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d7a70)
Location: security/smack/smack_lsm.c:2182
Inline: False
```
**Symbols:**

```
c0000000006d7a70-c0000000006d7b80: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c308e)
Location: security/smack/smack_lsm.c:2182
Inline: False
```
**Symbols:**

```
ffffffe0003c308e-ffffffe0003c3146: smack_task_kill (STB_LOCAL)
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
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814782f0)
Location: security/smack/smack_lsm.c:2182
Inline: False
```
**Symbols:**

```
ffffffff814782f0-ffffffff814783b3: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81468d10)
Location: security/smack/smack_lsm.c:2182
Inline: False
```
**Symbols:**

```
ffffffff81468d10-ffffffff81468dd3: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81474390)
Location: security/smack/smack_lsm.c:2182
Inline: False
```
**Symbols:**

```
ffffffff81474390-ffffffff81474453: smack_task_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smack_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8148bcb0)
Location: security/smack/smack_lsm.c:2182
Inline: False
```
**Symbols:**

```
ffffffff8148bcb0-ffffffff8148bda7: smack_task_kill (STB_LOCAL)
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
