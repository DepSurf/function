# Function: <code>__audit_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81128340)
Location: kernel/auditsc.c:1457
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81128340-ffffffff81128570: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811304e0)
Location: kernel/auditsc.c:1456
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff811304e0-ffffffff8113071c: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113a250)
Location: kernel/auditsc.c:1461
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8113a250-ffffffff8113a48c: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113b890)
Location: kernel/auditsc.c:1470
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8113b890-ffffffff8113bab5: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811485f0)
Location: kernel/auditsc.c:1470
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff811485f0-ffffffff81148815: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81156fc0)
Location: kernel/auditsc.c:1481
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81156fc0-ffffffff811571c6: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81164010)
Location: kernel/auditsc.c:1440
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81164010-ffffffff8116421a: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81170c10)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81170c10-ffffffff81170e69: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117ca90)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8117ca90-ffffffff8117cce9: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118fda0)
Location: kernel/auditsc.c:1613
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8118fda0-ffffffff81190001: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d020)
Location: kernel/auditsc.c:1631
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8118d020-ffffffff8118d281: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118de80)
Location: kernel/auditsc.c:1630
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8118de80-ffffffff8118e0d5: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1640
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81cb3664-ffffffff81cb367f: __audit_free.cold (STB_LOCAL)
ffffffff811b6c80-ffffffff811b6ee1: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e9a70)
Location: kernel/auditsc.c:1825
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff811e9a70-ffffffff811e9ba8: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122fab0)
Location: kernel/auditsc.c:1803
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8122fab0-ffffffff8122fc52: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812465a0)
Location: kernel/auditsc.c:1800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff812465a0-ffffffff81246742: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81260450)
Location: kernel/auditsc.c:1795
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81260450-ffffffff812605f2: __audit_free (STB_GLOBAL)
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
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f1980)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffff8000101f1980-ffff8000101f1b6c: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0431e20)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
c0431e20-c0432028: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000265c50)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
c000000000265c50-c000000000265f14: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165288)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffe000165288-ffffffe000165450: __audit_free (STB_GLOBAL)
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
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811750b0)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff811750b0-ffffffff81175309: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81168250)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81168250-ffffffff811684a9: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81172e80)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81172e80-ffffffff811730d9: __audit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __audit_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811806f0)
Location: kernel/auditsc.c:1582
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff811806f0-ffffffff81180949: __audit_free (STB_GLOBAL)
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
