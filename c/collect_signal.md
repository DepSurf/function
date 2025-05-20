# Function: <code>collect_signal</code>

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
In kernel/signal.c (ffffffff8108d4d7)
Location: kernel/signal.c:506
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
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
In kernel/signal.c (ffffffff810903a6)
Location: kernel/signal.c:506
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
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
In kernel/signal.c (ffffffff81095326)
Location: kernel/signal.c:508
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092593)
Location: kernel/signal.c:514
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109942d)
Location: kernel/signal.c:516
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d539)
Location: kernel/signal.c:518
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5809)
Location: kernel/signal.c:552
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa4ef)
Location: kernel/signal.c:562
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0aef)
Location: kernel/signal.c:567
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8650)
Location: kernel/signal.c:567
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810b8650-ffffffff810b875e: collect_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3900)
Location: kernel/signal.c:568
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810b3900-ffffffff810b3a0e: collect_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4e20)
Location: kernel/signal.c:567
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810b4e20-ffffffff810b4f2e: collect_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:568
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810c7410-ffffffff810c759a: collect_signal (STB_LOCAL)
ffffffff81ca46bd-ffffffff81ca46e1: collect_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:568
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff810dffe0-ffffffff810e0175: collect_signal (STB_LOCAL)
ffffffff81e54017-ffffffff81e5403a: collect_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:568
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81100680-ffffffff811007f2: collect_signal (STB_LOCAL)
ffffffff820560d0-ffffffff820560f3: collect_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:573
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff8110c780-ffffffff8110c8f2: collect_signal (STB_LOCAL)
ffffffff820d4660-ffffffff820d4683: collect_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:564
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffff81116160-ffffffff811162d2: collect_signal (STB_LOCAL)
ffffffff821af559-ffffffff821af57c: collect_signal.cold (STB_LOCAL)
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
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010b638)
Location: kernel/signal.c:567
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffff80001010b638-ffff80001010b788: collect_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036468c)
Location: kernel/signal.c:567
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
c036468c-c03647f8: collect_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153220)
Location: kernel/signal.c:567
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
c000000000153220-c00000000015337c: collect_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void collect_signal(int sig, struct sigpending *list, kernel_siginfo_t *info, bool *resched_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cd82c)
Location: kernel/signal.c:567
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
**Symbols:**

```
ffffffe0000cd82c-ffffffe0000cd926: collect_signal (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aae5f)
Location: kernel/signal.c:567
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810997ff)
Location: kernel/signal.c:567
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa3bf)
Location: kernel/signal.c:567
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b249f)
Location: kernel/signal.c:567
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
