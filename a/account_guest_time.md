# Function: <code>account_guest_time</code>

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
In kernel/sched/cputime.c (ffffffff810b1808)
Location: kernel/sched/cputime.c:160
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
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
In kernel/sched/cputime.c (ffffffff810b42ac)
Location: kernel/sched/cputime.c:169
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
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
In kernel/sched/cputime.c (ffffffff810ba8d1)
Location: kernel/sched/cputime.c:154
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b50b0)
Location: kernel/sched/cputime.c:142
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810b50b0-ffffffff810b5126: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bc230)
Location: kernel/sched/cputime.c:142
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810bc230-ffffffff810bc2a6: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c3900)
Location: kernel/sched/cputime.c:138
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810c3900-ffffffff810c3973: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810ccbc0)
Location: kernel/sched/cputime.c:138
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810ccbc0-ffffffff810ccc33: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d4fa0)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810d4fa0-ffffffff810d5013: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810df560)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810df560-ffffffff810df5d2: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e78b0)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810e78b0-ffffffff810e7922: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e55a0)
Location: kernel/sched/cputime.c:140
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810e55a0-ffffffff810e5612: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7560)
Location: kernel/sched/cputime.c:140
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810e7560-ffffffff810e75d2: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810feb70)
Location: kernel/sched/cputime.c:140
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810feb70-ffffffff810fec6a: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811393e0)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_system_time
```
**Symbols:**

```
ffffffff811393e0-ffffffff811394f0: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81163ad0)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_system_time
```
**Symbols:**

```
ffffffff81163ad0-ffffffff81163be0: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811742b0)
Location: kernel/sched/cputime.c:143
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_system_time
```
**Symbols:**

```
ffffffff811742b0-ffffffff811743c0: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81181bc0)
Location: kernel/sched/cputime.c:143
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:vtime_guest_exit
  - kernel/sched/build_policy.c:vtime_account_kernel
  - kernel/sched/build_policy.c:account_system_time
```
**Symbols:**

```
ffffffff81181bc0-ffffffff81181cd0: account_guest_time (STB_GLOBAL)
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
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffff80001013ee00)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffff80001013ee00-ffff80001013eef0: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c038ed74)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
c038ed74-c038ee90: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c00000000018dfc0)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
c00000000018dfc0-c00000000018e07c: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffe0000ed5e0)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffe0000ed5e0-ffffffe0000ed688: account_guest_time (STB_GLOBAL)
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
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d9750)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810d9750-ffffffff810d97c2: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c8130)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:vtime_account_guest
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810c8130-ffffffff810c81a2: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d5a90)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810d5a90-ffffffff810d5b02: account_guest_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void account_guest_time(struct task_struct *p, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e1390)
Location: kernel/sched/cputime.c:139
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810e1390-ffffffff810e1402: account_guest_time (STB_GLOBAL)
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
