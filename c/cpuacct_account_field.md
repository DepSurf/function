# Function: <code>cpuacct_account_field</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *p, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810c99f0)
Location: kernel/sched/cpuacct.c:263
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_user_time
  - kernel/sched/cputime.c:account_system_time
```
**Symbols:**

```
ffffffff810c99f0-ffffffff810c9a36: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810ce2c0)
Location: kernel/sched/cpuacct.c:370
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810ce2c0-ffffffff810ce306: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810d42e0)
Location: kernel/sched/cpuacct.c:370
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810d42e0-ffffffff810d4326: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810d3470)
Location: kernel/sched/cpuacct.c:370
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810d3470-ffffffff810d34b9: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810db040)
Location: kernel/sched/cpuacct.c:371
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810db040-ffffffff810db08b: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810e31b0)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810e31b0-ffffffff810e31fa: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810ed8e0)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810ed8e0-ffffffff810ed92a: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f4660)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810f4660-ffffffff810f46a9: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff811002f0)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff811002f0-ffffffff81100339: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff8110a990)
Location: kernel/sched/cpuacct.c:361
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff8110a990-ffffffff8110a9d9: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff811078a0)
Location: kernel/sched/cpuacct.c:361
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff811078a0-ffffffff811078ee: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81109970)
Location: kernel/sched/cpuacct.c:361
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff81109970-ffffffff811099b7: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81127e10)
Location: kernel/sched/cpuacct.c:346
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff81127e10-ffffffff81127e57: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81145520)
Location: kernel/sched/cpuacct.c:350
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
**Symbols:**

```
ffffffff81145520-ffffffff81145570: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81172680)
Location: kernel/sched/cpuacct.c:350
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
**Symbols:**

```
ffffffff81172680-ffffffff811726d0: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811836f0)
Location: kernel/sched/cpuacct.c:350
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
**Symbols:**

```
ffffffff811836f0-ffffffff81183778: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81191e30)
Location: kernel/sched/cpuacct.c:350
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
**Symbols:**

```
ffffffff81191e30-ffffffff81191eb8: cpuacct_account_field (STB_GLOBAL)
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
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffff800010164958)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffff800010164958-ffff8000101649cc: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (c03b0fa0)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
c03b0fa0-c03b1010: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (c0000000001bb8b0)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
c0000000001bb8b0-c0000000001bb908: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffe0001081be)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffe0001081be-ffffffe00010822a: cpuacct_account_field (STB_GLOBAL)
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
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f9600)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810f9600-ffffffff810f9649: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810e97e0)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810e97e0-ffffffff810e9829: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f6820)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff810f6820-ffffffff810f6869: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct *tsk, int index, u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81101860)
Location: kernel/sched/cpuacct.c:360
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff81101860-ffffffff811018c5: cpuacct_account_field (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *p</code>
</li>
</ul>
</details>
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
