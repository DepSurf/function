# Function: <code>__dequeue_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108d4a0)
Location: kernel/signal.c:543
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff8108d4a0-ffffffff8108d620: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090370)
Location: kernel/signal.c:543
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81090370-ffffffff810904eb: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810952f0)
Location: kernel/signal.c:545
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810952f0-ffffffff8109546b: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092560)
Location: kernel/signal.c:558
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81092560-ffffffff810926ef: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810993f0)
Location: kernel/signal.c:560
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810993f0-ffffffff8109957f: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d500)
Location: kernel/signal.c:563
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff8109d500-ffffffff8109d689: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a57d0)
Location: kernel/signal.c:597
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810a57d0-ffffffff810a5900: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa4b0)
Location: kernel/signal.c:607
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810aa4b0-ffffffff810aa5da: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0ab0)
Location: kernel/signal.c:612
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810b0ab0-ffffffff810b0bda: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8ef2)
Location: kernel/signal.c:612
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b41a2)
Location: kernel/signal.c:613
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5db2)
Location: kernel/signal.c:612
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c8c32)
Location: kernel/signal.c:613
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e01bb)
Location: kernel/signal.c:613
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110084b)
Location: kernel/signal.c:613
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110c94b)
Location: kernel/signal.c:618
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111632b)
Location: kernel/signal.c:609
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010b7c4)
Location: kernel/signal.c:612
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03649ec)
Location: kernel/signal.c:612
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001533cc)
Location: kernel/signal.c:612
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cddb8)
Location: kernel/signal.c:612
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
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
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aae20)
Location: kernel/signal.c:612
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810aae20-ffffffff810aaf4a: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810997c0)
Location: kernel/signal.c:612
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810997c0-ffffffff810998ea: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa380)
Location: kernel/signal.c:612
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810aa380-ffffffff810aa4aa: __dequeue_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending *pending, sigset_t *mask, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2460)
Location: kernel/signal.c:612
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810b2460-ffffffff810b258a: __dequeue_signal (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *resched_timer</code>
</li>
</ul>
</details>
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
<b>Param type changed. </b>
<code>siginfo_t *info</code> ➡️ <code>kernel_siginfo_t *info</code>
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
</ul>
<b>Arch</b>
<ul>
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
