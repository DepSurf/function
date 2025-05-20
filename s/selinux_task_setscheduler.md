# Function: <code>selinux_task_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3860
Inline: False
```
**Symbols:**

```
ffffffff81377640-ffffffff81377650: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3932
Inline: False
```
**Symbols:**

```
ffffffff8138e050-ffffffff8138e060: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a4290)
Location: security/selinux/hooks.c:3912
Inline: False
```
**Symbols:**

```
ffffffff813a4290-ffffffff813a42da: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ca370)
Location: security/selinux/hooks.c:3927
Inline: False
```
**Symbols:**

```
ffffffff813ca370-ffffffff813ca3ba: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813f9730)
Location: security/selinux/hooks.c:4156
Inline: False
```
**Symbols:**

```
ffffffff813f9730-ffffffff813f977a: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814155d0)
Location: security/selinux/hooks.c:3876
Inline: False
```
**Symbols:**

```
ffffffff814155d0-ffffffff81415622: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81442fd0)
Location: security/selinux/hooks.c:4064
Inline: False
```
**Symbols:**

```
ffffffff81442fd0-ffffffff81443022: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145cb10)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
ffffffff8145cb10-ffffffff8145cb6a: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814afe20)
Location: security/selinux/hooks.c:4115
Inline: True
```
**Symbols:**

```
ffffffff814afe20-ffffffff814afe7a: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d0df0)
Location: security/selinux/hooks.c:4131
Inline: True
```
**Symbols:**

```
ffffffff814d0df0-ffffffff814d0e59: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d7070)
Location: security/selinux/hooks.c:4295
Inline: True
```
**Symbols:**

```
ffffffff814d7070-ffffffff814d70d9: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815300d0)
Location: security/selinux/hooks.c:4280
Inline: False
```
**Symbols:**

```
ffffffff815300d0-ffffffff81530139: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c6f00)
Location: security/selinux/hooks.c:4176
Inline: False
```
**Symbols:**

```
ffffffff815c6f00-ffffffff815c6f80: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81673c80)
Location: security/selinux/hooks.c:4194
Inline: False
```
**Symbols:**

```
ffffffff81673c80-ffffffff81673d00: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816abea0)
Location: security/selinux/hooks.c:4159
Inline: False
```
**Symbols:**

```
ffffffff816abea0-ffffffff816abf15: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e93b0)
Location: security/selinux/hooks.c:4247
Inline: False
```
**Symbols:**

```
ffffffff816e93b0-ffffffff816e942b: selinux_task_setscheduler (STB_LOCAL)
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
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010549798)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
ffff800010549798-ffff800010549808: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06ff4bc)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
c06ff4bc-c06ff53c: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a0e90)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
c0000000006a0e90-c0000000006a0f08: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a4606)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
ffffffe0003a4606-ffffffe0003a465e: selinux_task_setscheduler (STB_LOCAL)
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
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814550f0)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
ffffffff814550f0-ffffffff8145514a: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81445b30)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
ffffffff81445b30-ffffffff81445b8a: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81451190)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
ffffffff81451190-ffffffff814511ea: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81469d20)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
ffffffff81469d20-ffffffff81469d91: selinux_task_setscheduler (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
