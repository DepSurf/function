# Function: <code>dl_change_utilization</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c86e0)
Location: kernel/sched/deadline.c:125
Inline: True
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810c86e0-ffffffff810c88b4: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cfe10)
Location: kernel/sched/deadline.c:126
Inline: True
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810cfe10-ffffffff810cffe0: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d8320)
Location: kernel/sched/deadline.c:155
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810d8320-ffffffff810d8554: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e1e20)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810e1e20-ffffffff810e2054: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e88f0)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810e88f0-ffffffff810e8b43: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f4270)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810f4270-ffffffff810f44c3: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb480)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810fb480-ffffffff810fb6eb: dl_change_utilization (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f9340)
Location: kernel/sched/deadline.c:233
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810f9340-ffffffff810f95a7: dl_change_utilization (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb490)
Location: kernel/sched/deadline.c:233
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810fb490-ffffffff810fb6fa: dl_change_utilization (STB_LOCAL)
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
In kernel/sched/deadline.c (ffffffff8111a988)
Location: kernel/sched/deadline.c:233
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
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
In kernel/sched/build_policy.c (ffffffff8113a929)
Location: kernel/sched/deadline.c:307
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
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
In kernel/sched/build_policy.c (ffffffff81165121)
Location: kernel/sched/deadline.c:309
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
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
In kernel/sched/build_policy.c (ffffffff811758c1)
Location: kernel/sched/deadline.c:311
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
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
In kernel/sched/build_policy.c (ffffffff81183bd8)
Location: kernel/sched/deadline.c:324
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
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
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010156630)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffff800010156630-ffff8000101568ac: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a4298)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
c03a4298-c03a45d0: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001aaf00)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
c0000000001aaf00-c0000000001ab284: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fd746)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffe0000fd746-ffffffe0000fd916: dl_change_utilization (STB_GLOBAL)
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
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ed670)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810ed670-ffffffff810ed8c3: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810dd700)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810dd700-ffffffff810dd953: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ea7a0)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810ea7a0-ffffffff810ea9f3: dl_change_utilization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct *p, u64 new_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f5750)
Location: kernel/sched/deadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
**Symbols:**

```
ffffffff810f5750-ffffffff810f59a3: dl_change_utilization (STB_GLOBAL)
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
