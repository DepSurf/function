# Function: <code>audit_log_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_exit(struct audit_context *context, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81125d10)
Location: kernel/auditsc.c:1324
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_syscall_exit
```
**Symbols:**

```
ffffffff81125d10-ffffffff811269df: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_exit(struct audit_context *context, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8112e200)
Location: kernel/auditsc.c:1323
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8112e200-ffffffff8112eac4: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_exit(struct audit_context *context, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81137f40)
Location: kernel/auditsc.c:1328
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81137f40-ffffffff81138804: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_exit(struct audit_context *context, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81139490)
Location: kernel/auditsc.c:1335
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81139490-ffffffff81139e2b: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_exit(struct audit_context *context, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81146180)
Location: kernel/auditsc.c:1335
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81146180-ffffffff81146aec: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_exit(struct audit_context *context, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81154b60)
Location: kernel/auditsc.c:1346
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81154b60-ffffffff8115549c: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811619f0)
Location: kernel/auditsc.c:1305
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff811619f0-ffffffff811623b9: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8116f480)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8116f480-ffffffff8116fa76: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117b300)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8117b300-ffffffff8117b8f6: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118f840)
Location: kernel/auditsc.c:1474
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8118f840-ffffffff8118fd98: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118cad0)
Location: kernel/auditsc.c:1492
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8118cad0-ffffffff8118d01e: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d820)
Location: kernel/auditsc.c:1491
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8118d820-ffffffff8118de7a: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1500
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff811b6510-ffffffff811b6c77: audit_log_exit (STB_LOCAL)
ffffffff81cb3649-ffffffff81cb3664: audit_log_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1677
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff811e8c50-ffffffff811e9333: audit_log_exit (STB_LOCAL)
ffffffff81e643f8-ffffffff81e64413: audit_log_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1655
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8122ecf0-ffffffff8122f3d3: audit_log_exit (STB_LOCAL)
ffffffff8205c5f1-ffffffff8205c60c: audit_log_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1652
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81245a90-ffffffff812462f1: audit_log_exit (STB_LOCAL)
ffffffff820daf4e-ffffffff820daf69: audit_log_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1647
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8125fa10-ffffffff81260188: audit_log_exit (STB_LOCAL)
ffffffff821b6ca4-ffffffff821b6cbf: audit_log_exit.cold (STB_LOCAL)
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
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f0fc0)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffff8000101f0fc0-ffff8000101f159c: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c04304f0)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
c04304f0-c0430b18: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0000000002646e0)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
c0000000002646e0-c000000000264eac: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000164a48)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffe000164a48-ffffffe000164fbc: audit_log_exit (STB_LOCAL)
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
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81173920)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81173920-ffffffff81173f16: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81166ac0)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81166ac0-ffffffff811670b6: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811716f0)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff811716f0-ffffffff81171ce6: audit_log_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117ef00)
Location: kernel/auditsc.c:1444
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8117ef00-ffffffff8117f4f6: audit_log_exit (STB_LOCAL)
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
<b>Param removed. </b>
<code>struct audit_context *context</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
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
