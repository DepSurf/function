# Function: <code>account_system_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, cputime_t cputime, cputime_t cputime_scaled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b1760)
Location: kernel/sched/cputime.c:211
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810b1760-ffffffff810b1870: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, cputime_t cputime, cputime_t cputime_scaled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b41f0)
Location: kernel/sched/cputime.c:220
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810b41f0-ffffffff810b4312: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, cputime_t cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810ba820)
Location: kernel/sched/cputime.c:199
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810ba820-ffffffff810ba930: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b51a0)
Location: kernel/sched/cputime.c:187
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810b51a0-ffffffff810b51fc: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bc350)
Location: kernel/sched/cputime.c:187
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810bc350-ffffffff810bc3ac: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c3a20)
Location: kernel/sched/cputime.c:183
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810c3a20-ffffffff810c3a7c: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810ccce0)
Location: kernel/sched/cputime.c:183
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810ccce0-ffffffff810ccd3d: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d50c0)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810d50c0-ffffffff810d5119: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810df680)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810df680-ffffffff810df6d9: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e79d0)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e79d0-ffffffff810e7a29: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e56c0)
Location: kernel/sched/cputime.c:185
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e56c0-ffffffff810e5719: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7690)
Location: kernel/sched/cputime.c:185
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e7690-ffffffff810e76e9: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810fed30)
Location: kernel/sched/cputime.c:185
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810fed30-ffffffff810fed89: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811395c0)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff811395c0-ffffffff8113963b: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81163cd0)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff81163cd0-ffffffff81163d4b: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811744b0)
Location: kernel/sched/cputime.c:188
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff811744b0-ffffffff8117452b: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81181e50)
Location: kernel/sched/cputime.c:188
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:vtime_guest_enter
  - kernel/sched/build_policy.c:vtime_user_enter
  - kernel/sched/build_policy.c:vtime_account_kernel
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff81181e50-ffffffff81181ecb: account_system_time (STB_GLOBAL)
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
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffff80001013efc0)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffff80001013efc0-ffff80001013f054: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c038ef84)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
c038ef84-c038f020: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c00000000018e180)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
c00000000018e180-c00000000018e1f4: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffe0000ed73a)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffe0000ed73a-ffffffe0000ed7b8: account_system_time (STB_GLOBAL)
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
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d9870)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810d9870-ffffffff810d98c9: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c8250)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:__vtime_account_system
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810c8250-ffffffff810c82a9: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d5bb0)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810d5bb0-ffffffff810d5c09: account_system_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void account_system_time(struct task_struct *p, int hardirq_offset, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e14c0)
Location: kernel/sched/cputime.c:184
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e14c0-ffffffff810e1519: account_system_time (STB_GLOBAL)
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
