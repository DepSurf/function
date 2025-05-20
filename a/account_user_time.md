# Function: <code>account_user_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, cputime_t cputime, cputime_t cputime_scaled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b16e0)
Location: kernel/sched/cputime.c:135
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810b16e0-ffffffff810b1756: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, cputime_t cputime, cputime_t cputime_scaled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b4170)
Location: kernel/sched/cputime.c:144
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810b4170-ffffffff810b41e4: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, cputime_t cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810ba7b0)
Location: kernel/sched/cputime.c:132
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810ba7b0-ffffffff810ba81a: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b5030)
Location: kernel/sched/cputime.c:120
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810b5030-ffffffff810b50a7: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bc180)
Location: kernel/sched/cputime.c:120
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810bc180-ffffffff810bc228: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c3850)
Location: kernel/sched/cputime.c:116
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810c3850-ffffffff810c38f5: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810ccb10)
Location: kernel/sched/cputime.c:116
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810ccb10-ffffffff810ccbb5: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d4ef0)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810d4ef0-ffffffff810d4f9c: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810df4b0)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810df4b0-ffffffff810df55b: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7800)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e7800-ffffffff810e78ab: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e54f0)
Location: kernel/sched/cputime.c:118
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e54f0-ffffffff810e55a0: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e74a0)
Location: kernel/sched/cputime.c:118
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e74a0-ffffffff810e7553: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810feab0)
Location: kernel/sched/cputime.c:118
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810feab0-ffffffff810feb62: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81139320)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff81139320-ffffffff811393d6: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81163a00)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff81163a00-ffffffff81163ab6: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811741e0)
Location: kernel/sched/cputime.c:121
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff811741e0-ffffffff81174297: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81181af0)
Location: kernel/sched/cputime.c:121
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:vtime_user_exit
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff81181af0-ffffffff81181ba7: account_user_time (STB_GLOBAL)
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
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffff80001013ed20)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffff80001013ed20-ffff80001013ee00: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c038ec6c)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
c038ec6c-c038ed74: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c00000000018deb0)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
c00000000018deb0-c00000000018dfb8: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffe0000ed524)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffe0000ed524-ffffffe0000ed5e0: account_user_time (STB_GLOBAL)
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
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d96a0)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810d96a0-ffffffff810d974b: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c8080)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:vtime_user_exit
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810c8080-ffffffff810c812b: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d59e0)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810d59e0-ffffffff810d5a8b: account_user_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void account_user_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e12d0)
Location: kernel/sched/cputime.c:117
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e12d0-ffffffff810e1385: account_user_time (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>cputime_t cputime_scaled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cputime_t cputime</code> ➡️ <code>u64 cputime</code>
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
