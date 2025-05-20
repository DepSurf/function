# Function: <code>audit_signal_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108cfea)
Location: kernel/audit.h:332
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810901a7)
Location: kernel/audit.h:338
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095127)
Location: kernel/audit.h:338
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113c9c0)
Location: kernel/auditsc.c:2256
Inline: False
```
**Symbols:**

```
ffffffff8113c9c0-ffffffff8113cc26: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81149740)
Location: kernel/auditsc.c:2279
Inline: False
```
**Symbols:**

```
ffffffff81149740-ffffffff811499a6: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81158060)
Location: kernel/auditsc.c:2286
Inline: False
```
**Symbols:**

```
ffffffff81158060-ffffffff811582ae: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81165060)
Location: kernel/auditsc.c:2271
Inline: False
```
**Symbols:**

```
ffffffff81165060-ffffffff811652b0: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b650)
Location: kernel/audit.c:2271
Inline: False
```
**Symbols:**

```
ffffffff8116b650-ffffffff8116b6e7: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81177530)
Location: kernel/audit.c:2273
Inline: False
```
**Symbols:**

```
ffffffff81177530-ffffffff811775c7: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8118a1a0)
Location: kernel/audit.c:2425
Inline: False
```
**Symbols:**

```
ffffffff8118a1a0-ffffffff8118a23b: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811874b0)
Location: kernel/audit.c:2442
Inline: False
```
**Symbols:**

```
ffffffff811874b0-ffffffff81187556: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188520)
Location: kernel/audit.c:2442
Inline: False
```
**Symbols:**

```
ffffffff81188520-ffffffff811885c6: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811b0a40)
Location: kernel/audit.c:2481
Inline: False
```
**Symbols:**

```
ffffffff811b0a40-ffffffff811b0ae6: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e2c40)
Location: kernel/audit.c:2525
Inline: False
```
**Symbols:**

```
ffffffff811e2c40-ffffffff811e2cf6: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81228b30)
Location: kernel/audit.c:2523
Inline: False
```
**Symbols:**

```
ffffffff81228b30-ffffffff81228be6: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123f130)
Location: kernel/audit.c:2523
Inline: False
```
**Symbols:**

```
ffffffff8123f130-ffffffff8123f1e6: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81258fa0)
Location: kernel/audit.c:2545
Inline: False
```
**Symbols:**

```
ffffffff81258fa0-ffffffff81259056: audit_signal_info (STB_GLOBAL)
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
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ec530)
Location: kernel/audit.c:2273
Inline: False
```
**Symbols:**

```
ffff8000101ec530-ffff8000101ec5e8: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042c174)
Location: kernel/audit.c:2273
Inline: False
```
**Symbols:**

```
c042c174-c042c22c: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025df90)
Location: kernel/audit.c:2273
Inline: False
```
**Symbols:**

```
c00000000025df90-c00000000025e084: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe000160bca)
Location: kernel/audit.c:2273
Inline: False
```
**Symbols:**

```
ffffffe000160bca-ffffffe000160c68: audit_signal_info (STB_GLOBAL)
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
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116fb50)
Location: kernel/audit.c:2273
Inline: False
```
**Symbols:**

```
ffffffff8116fb50-ffffffff8116fbe7: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81162cf0)
Location: kernel/audit.c:2273
Inline: False
```
**Symbols:**

```
ffffffff81162cf0-ffffffff81162d87: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d920)
Location: kernel/audit.c:2273
Inline: False
```
**Symbols:**

```
ffffffff8116d920-ffffffff8116d9b7: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_signal_info(int sig, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8117b120)
Location: kernel/audit.c:2273
Inline: False
```
**Symbols:**

```
ffffffff8117b120-ffffffff8117b1a7: audit_signal_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
