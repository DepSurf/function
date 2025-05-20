# Function: <code>cpudl_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810c4550)
Location: kernel/sched/cpudeadline.c:99
Inline: False
Direct callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:find_later_rq
```
**Symbols:**

```
ffffffff810c4550-ffffffff810c4618: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810c8230)
Location: kernel/sched/cpudeadline.c:99
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810c8230-ffffffff810c82ed: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ce250)
Location: kernel/sched/cpudeadline.c:124
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810ce250-ffffffff810ce310: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810cab90)
Location: kernel/sched/cpudeadline.c:124
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810cab90-ffffffff810cac2b: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810d2340)
Location: kernel/sched/cpudeadline.c:124
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810d2340-ffffffff810d23ca: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810da420)
Location: kernel/sched/cpudeadline.c:121
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810da420-ffffffff810da4aa: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810e3f70)
Location: kernel/sched/cpudeadline.c:121
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810e3f70-ffffffff810e3ffa: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (0)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810eae72-ffffffff810eae85: cpudl_find.cold (STB_LOCAL)
ffffffff810eab60-ffffffff810eabfb: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810f6530)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810f6530-ffffffff810f65c1: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ffec0)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810ffec0-ffffffff810fff54: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810fe970)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810fe970-ffffffff810feab8: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff81100d30)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff81100d30-ffffffff81100e99: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff8111cea0)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff8111cea0-ffffffff8111d031: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81133c40)
Location: kernel/sched/cpudeadline.c:116
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff81133c40-ffffffff81133dd1: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115e140)
Location: kernel/sched/cpudeadline.c:116
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff8115e140-ffffffff8115e2b4: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116e820)
Location: kernel/sched/cpudeadline.c:116
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff8116e820-ffffffff8116e997: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117bdf0)
Location: kernel/sched/cpudeadline.c:116
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:wakeup_preempt_dl
  - kernel/sched/build_policy.c:wakeup_preempt_dl
```
**Symbols:**

```
ffffffff8117bdf0-ffffffff8117bf16: cpudl_find (STB_GLOBAL)
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
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffff80001015a3a8)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffff80001015a3a8-ffff80001015a4a8: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (c03a7170)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
c03a7170-c03a7290: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (c0000000001ae640)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
c0000000001ae640-c0000000001ae794: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffe0000ffd78)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffe0000ffd78-ffffffe0000ffe44: cpudl_find (STB_GLOBAL)
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
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ef930)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810ef930-ffffffff810ef9c1: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810df9a0)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810df9a0-ffffffff810dfa31: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810eca60)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810eca60-ffffffff810ecaf1: cpudl_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpudl_find(struct cpudl *cp, struct task_struct *p, struct cpumask *later_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810f7aa0)
Location: kernel/sched/cpudeadline.c:117
Inline: False
Direct callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
**Symbols:**

```
ffffffff810f7aa0-ffffffff810f7b31: cpudl_find (STB_GLOBAL)
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
