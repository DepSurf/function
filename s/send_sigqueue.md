# Function: <code>send_sigqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct task_struct *t, int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108fd40)
Location: kernel/signal.c:1521
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_event
```
**Symbols:**

```
ffffffff8108fd40-ffffffff8108ff35: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct task_struct *t, int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092dc0)
Location: kernel/signal.c:1521
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_event
```
**Symbols:**

```
ffffffff81092dc0-ffffffff81092fa8: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct task_struct *t, int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097d50)
Location: kernel/signal.c:1527
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_event
```
**Symbols:**

```
ffffffff81097d50-ffffffff81097f38: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct task_struct *t, int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095060)
Location: kernel/signal.c:1549
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_event
```
**Symbols:**

```
ffffffff81095060-ffffffff8109523e: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct task_struct *t, int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109bf00)
Location: kernel/signal.c:1550
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_event
```
**Symbols:**

```
ffffffff8109bf00-ffffffff8109c0dd: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct task_struct *t, int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a02d0)
Location: kernel/signal.c:1667
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_event
```
**Symbols:**

```
ffffffff810a02d0-ffffffff810a04ad: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a8600)
Location: kernel/signal.c:1753
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff810a8600-ffffffff810a87f8: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abbe0)
Location: kernel/signal.c:1841
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff810abbe0-ffffffff810abdd4: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b21f0)
Location: kernel/signal.c:1846
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff810b21f0-ffffffff810b23e4: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810baa80)
Location: kernel/signal.c:1842
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff810baa80-ffffffff810baca8: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5d40)
Location: kernel/signal.c:1843
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff810b5d40-ffffffff810b5f3c: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7940)
Location: kernel/signal.c:1855
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff810b7940-ffffffff810b7b3c: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1947
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff81ca4834-ffffffff81ca485d: send_sigqueue.cold (STB_LOCAL)
ffffffff810c9dc0-ffffffff810c9fc6: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1960
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff81e54105-ffffffff81e5412e: send_sigqueue.cold (STB_LOCAL)
ffffffff810e18a0-ffffffff810e1ad0: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1961
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff820561be-ffffffff820561e7: send_sigqueue.cold (STB_LOCAL)
ffffffff81101bc0-ffffffff81101df0: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1967
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff820d4745-ffffffff820d476e: send_sigqueue.cold (STB_LOCAL)
ffffffff8110ddd0-ffffffff8110e023: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1958
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff821af63e-ffffffff821af667: send_sigqueue.cold (STB_LOCAL)
ffffffff81117730-ffffffff81117983: send_sigqueue (STB_GLOBAL)
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
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010df08)
Location: kernel/signal.c:1846
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffff80001010df08-ffff80001010e12c: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0366230)
Location: kernel/signal.c:1846
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
c0366230-c0366468: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000155330)
Location: kernel/signal.c:1846
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
c000000000155330-c0000000001555b8: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cef0e)
Location: kernel/signal.c:1846
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffe0000cef0e-ffffffe0000cf08a: send_sigqueue (STB_GLOBAL)
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
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac560)
Location: kernel/signal.c:1846
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff810ac560-ffffffff810ac754: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109aef0)
Location: kernel/signal.c:1846
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff8109aef0-ffffffff8109b0e4: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abac0)
Location: kernel/signal.c:1846
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff810abac0-ffffffff810abcb4: send_sigqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int send_sigqueue(struct sigqueue *q, struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3c20)
Location: kernel/signal.c:1846
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff810b3c20-ffffffff810b3e3b: send_sigqueue (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct pid *pid</code>
</li>
<li>
<b>Param added. </b>
<code>enum pid_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *t</code>
</li>
<li>
<b>Param removed. </b>
<code>int group</code>
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
