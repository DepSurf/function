# Function: <code>complete_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108ddd0)
Location: kernel/signal.c:870
Inline: False
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:send_sigqueue
```
**Symbols:**

```
ffffffff8108ddd0-ffffffff8108dfb6: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090e50)
Location: kernel/signal.c:870
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81090e50-ffffffff81091038: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095dd0)
Location: kernel/signal.c:876
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81095dd0-ffffffff81095fb0: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092d80)
Location: kernel/signal.c:890
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81092d80-ffffffff81092f8d: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099c60)
Location: kernel/signal.c:892
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81099c60-ffffffff81099e6f: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109dc30)
Location: kernel/signal.c:898
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff8109dc30-ffffffff8109de61: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5f40)
Location: kernel/signal.c:973
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810a5f40-ffffffff810a6175: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aac10)
Location: kernel/signal.c:984
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810aac10-ffffffff810aae52: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1210)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b1210-ffffffff810b1452: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9b80)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b9b80-ffffffff810b9df7: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4e30)
Location: kernel/signal.c:990
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b4e30-ffffffff810b50a7: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6a40)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b6a40-ffffffff810b6c92: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:990
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810c8380-ffffffff810c8644: complete_signal (STB_LOCAL)
ffffffff81ca4702-ffffffff81ca4781: complete_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:997
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff810df990-ffffffff810dfd24: complete_signal (STB_LOCAL)
ffffffff81e53f82-ffffffff81e54017: complete_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:998
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff81100000-ffffffff81100394: complete_signal (STB_LOCAL)
ffffffff8205603b-ffffffff820560d0: complete_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1003
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff8110c090-ffffffff8110c4b0: complete_signal (STB_LOCAL)
ffffffff820d45e5-ffffffff820d4660: complete_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:994
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff81115a40-ffffffff81115e8d: complete_signal (STB_LOCAL)
ffffffff821af4de-ffffffff821af559: complete_signal.cold (STB_LOCAL)
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
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010ce68)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffff80001010ce68-ffff80001010d088: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03650a0)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
c03650a0-c03652ec: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153df0)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
c000000000153df0-c000000000154128: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce40c)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffe0000ce40c-ffffffe0000ce5cc: complete_signal (STB_LOCAL)
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
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab580)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810ab580-ffffffff810ab7c2: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099f20)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81099f20-ffffffff8109a162: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aaae0)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810aaae0-ffffffff810aad22: complete_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void complete_signal(int sig, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2bc0)
Location: kernel/signal.c:989
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b2bc0-ffffffff810b2e02: complete_signal (STB_LOCAL)
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
<code>enum pid_type type</code>
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
