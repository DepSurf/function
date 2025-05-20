# Function: <code>force_sigsegv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int force_sigsegv(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108fc30)
Location: kernel/signal.c:1447
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff8108fc30-ffffffff8108fc96: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int force_sigsegv(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092cb0)
Location: kernel/signal.c:1447
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff81092cb0-ffffffff81092d16: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int force_sigsegv(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097c40)
Location: kernel/signal.c:1453
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff81097c40-ffffffff81097ca6: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int force_sigsegv(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094f50)
Location: kernel/signal.c:1475
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff81094f50-ffffffff81094fb6: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int force_sigsegv(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109bdf0)
Location: kernel/signal.c:1476
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff8109bdf0-ffffffff8109be56: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int force_sigsegv(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fe60)
Location: kernel/signal.c:1474
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff8109fe60-ffffffff8109fec6: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void force_sigsegv(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a81d0)
Location: kernel/signal.c:1561
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810a81d0-ffffffff810a8234: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae430)
Location: kernel/signal.c:1638
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810ae430-ffffffff810ae48f: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4a40)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810b4a40-ffffffff810b4a9f: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bdac0)
Location: kernel/signal.c:1639
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
ffffffff810bdac0-ffffffff810bdb64: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8dd0)
Location: kernel/signal.c:1640
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810b8dd0-ffffffff810b8e74: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba3c0)
Location: kernel/signal.c:1642
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810ba3c0-ffffffff810ba464: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ccc41)
Location: kernel/signal.c:1694
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810ccd60-ffffffff810ccdf5: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e46b3)
Location: kernel/signal.c:1695
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810e3f80-ffffffff810e402f: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81104d23)
Location: kernel/signal.c:1696
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff811045f0-ffffffff8110469f: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81110fa3)
Location: kernel/signal.c:1702
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff81110870-ffffffff8111091f: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111a913)
Location: kernel/signal.c:1708
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff8111a1c0-ffffffff8111a26f: force_sigsegv (STB_GLOBAL)
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
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110ae0)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffff800010110ae0-ffff800010110bb0: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03682bc)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
c03682bc-c0368318: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001583b0)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
c0000000001583b0-c000000000158438: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d06dc)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffe0000d06dc-ffffffe0000d0736: force_sigsegv (STB_GLOBAL)
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
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aedb0)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810aedb0-ffffffff810aee0f: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d700)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff8109d700-ffffffff8109d75f: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae310)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810ae310-ffffffff810ae36f: force_sigsegv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void force_sigsegv(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6580)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff810b6580-ffffffff810b65df: force_sigsegv (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *p</code>
</li>
</ul>
</details>
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
