# Function: <code>get_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090240)
Location: kernel/signal.c:2130
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81090240-ffffffff8109083b: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810932b0)
Location: kernel/signal.c:2130
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810932b0-ffffffff810938d1: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098240)
Location: kernel/signal.c:2136
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81098240-ffffffff81098861: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095530)
Location: kernel/signal.c:2157
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81095530-ffffffff81095b0c: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c3d0)
Location: kernel/signal.c:2158
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff8109c3d0-ffffffff8109c95b: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2291
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810a2e8e-ffffffff810a2eb9: get_signal.cold.54 (STB_LOCAL)
ffffffff810a07c0-ffffffff810a0d60: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2381
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810aba8e-ffffffff810abab6: get_signal.cold.59 (STB_LOCAL)
ffffffff810a8ad0-ffffffff810a9194: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2521
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810b0ff3-ffffffff810b101e: get_signal.cold (STB_LOCAL)
ffffffff810ae830-ffffffff810af0b0: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810b76bf-ffffffff810b76ea: get_signal.cold (STB_LOCAL)
ffffffff810b4e40-ffffffff810b56c7: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810bf60f-ffffffff810bf63a: get_signal.cold (STB_LOCAL)
ffffffff810bdd10-ffffffff810be338: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2547
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
**Symbols:**

```
ffffffff81bdba66-ffffffff81bdba8e: get_signal.cold (STB_LOCAL)
ffffffff810b9040-ffffffff810b9633: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2561
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff81bcdb16-ffffffff81bcdb46: get_signal.cold (STB_LOCAL)
ffffffff810ba560-ffffffff810bae0d: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2643
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - fs/io_uring.c:io_sqd_handle_event
  - fs/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff81ca48d8-ffffffff81ca4998: get_signal.cold (STB_LOCAL)
ffffffff810cce00-ffffffff810cd6f2: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2626
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - io_uring/io_uring.c:io_sqd_handle_event
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff81e541c5-ffffffff81e5426c: get_signal.cold (STB_LOCAL)
ffffffff810e4dd0-ffffffff810e5689: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2627
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff8205627e-ffffffff820562c3: get_signal.cold (STB_LOCAL)
ffffffff81105440-ffffffff81105d28: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2649
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - kernel/vhost_task.c:vhost_task_fn
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/io-wq.c:io_wq_worker
```
**Symbols:**

```
ffffffff820d4802-ffffffff820d4821: get_signal.cold (STB_LOCAL)
ffffffff811116d0-ffffffff81112007: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2661
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - kernel/vhost_task.c:vhost_task_fn
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/io-wq.c:io_wq_worker
```
**Symbols:**

```
ffffffff821af6eb-ffffffff821af70a: get_signal.cold (STB_LOCAL)
ffffffff8111b070-ffffffff8111b9ff: get_signal (STB_GLOBAL)
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
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110fd0)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
```
**Symbols:**

```
ffff800010110fd0-ffff800010111848: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03687dc)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
```
**Symbols:**

```
c03687dc-c0369190: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001588c0)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
```
**Symbols:**

```
c0000000001588c0-c000000000159460: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d09dc)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/riscv/kernel/signal.c:do_notify_resume
```
**Symbols:**

```
ffffffe0000d09dc-ffffffe0000d1282: get_signal (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810b1a2f-ffffffff810b1a5a: get_signal.cold (STB_LOCAL)
ffffffff810af1b0-ffffffff810afa37: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810a034f-ffffffff810a037a: get_signal.cold (STB_LOCAL)
ffffffff8109db00-ffffffff8109e357: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810b0f8f-ffffffff810b0fba: get_signal.cold (STB_LOCAL)
ffffffff810ae710-ffffffff810aef97: get_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool get_signal(struct ksignal *ksig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2526
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff810b9267-ffffffff810b92ab: get_signal.cold (STB_LOCAL)
ffffffff810b6980-ffffffff810b7269: get_signal (STB_GLOBAL)
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
<code>int</code> ➡️ <code>bool</code>
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
