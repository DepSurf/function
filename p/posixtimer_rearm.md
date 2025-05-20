# Function: <code>posixtimer_rearm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void posixtimer_rearm(struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81108300)
Location: kernel/time/posix-timers.c:309
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81108300-ffffffff81108391: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void posixtimer_rearm(struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811134b0)
Location: kernel/time/posix-timers.c:310
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff811134b0-ffffffff81113547: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void posixtimer_rearm(struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81120810)
Location: kernel/time/posix-timers.c:320
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81120810-ffffffff811208c1: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112bff0)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff8112bff0-ffffffff8112c0a7: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811367c0)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff811367c0-ffffffff8113687a: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81142870)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81142870-ffffffff8114292a: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811522d0)
Location: kernel/time/posix-timers.c:313
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff811522d0-ffffffff8115238a: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114e550)
Location: kernel/time/posix-timers.c:313
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff8114e550-ffffffff8114e60a: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114f9f0)
Location: kernel/time/posix-timers.c:313
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff8114f9f0-ffffffff8114faa7: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81173bd0)
Location: kernel/time/posix-timers.c:313
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81173bd0-ffffffff81173c87: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a8790)
Location: kernel/time/posix-timers.c:313
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff811a8790-ffffffff811a885e: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e8570)
Location: kernel/time/posix-timers.c:313
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff811e8570-ffffffff811e863e: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811fcb60)
Location: kernel/time/posix-timers.c:257
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff811fcb60-ffffffff811fcc2e: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81212d50)
Location: kernel/time/posix-timers.c:257
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81212d50-ffffffff81212e1e: posixtimer_rearm (STB_GLOBAL)
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
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101ac8d8)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffff8000101ac8d8-ffff8000101ac9b8: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f6a00)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
c03f6a00-c03f6aec: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c0000000002106e0)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
c0000000002106e0-c0000000002107f4: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe0001364bc)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffe0001364bc-ffffffe000136544: posixtimer_rearm (STB_GLOBAL)
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
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8113b020)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff8113b020-ffffffff8113b0da: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112da70)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff8112da70-ffffffff8112db2a: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81138d40)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81138d40-ffffffff81138dfa: posixtimer_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void posixtimer_rearm(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811457f0)
Location: kernel/time/posix-timers.c:287
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff811457f0-ffffffff811458aa: posixtimer_rearm (STB_GLOBAL)
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
