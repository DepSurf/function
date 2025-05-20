# Function: <code>sched_rt_rq_enqueue</code>

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
In kernel/sched/rt.c (ffffffff810bfdec)
Location: kernel/sched/rt.c:587
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:rq_offline_rt
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
In kernel/sched/rt.c (ffffffff810c4a05)
Location: kernel/sched/rt.c:595
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810caa6c)
Location: kernel/sched/rt.c:595
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810c456c)
Location: kernel/sched/rt.c:596
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810cb944)
Location: kernel/sched/rt.c:586
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810d3284)
Location: kernel/sched/rt.c:585
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810dcf24)
Location: kernel/sched/rt.c:587
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810e3ee4)
Location: kernel/sched/rt.c:587
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_rt_rq_enqueue(struct rt_rq *rt_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ee900)
Location: kernel/sched/rt.c:486
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff810ee900-ffffffff810ee986: sched_rt_rq_enqueue (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810f8823)
Location: kernel/sched/rt.c:629
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
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
In kernel/sched/rt.c (ffffffff810f6a2d)
Location: kernel/sched/rt.c:630
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
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
In kernel/sched/rt.c (ffffffff810f8dbd)
Location: kernel/sched/rt.c:630
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
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
In kernel/sched/rt.c (ffffffff8111429a)
Location: kernel/sched/rt.c:641
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
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
In kernel/sched/build_policy.c (ffffffff81131741)
Location: kernel/sched/rt.c:677
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
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
In kernel/sched/build_policy.c (ffffffff8115b73d)
Location: kernel/sched/rt.c:677
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
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
In kernel/sched/build_policy.c (ffffffff8116b8c0)
Location: kernel/sched/rt.c:677
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
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
In kernel/sched/build_policy.c (ffffffff811791c0)
Location: kernel/sched/rt.c:633
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
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
void sched_rt_rq_enqueue(struct rt_rq *rt_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014fa98)
Location: kernel/sched/rt.c:486
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
ffff80001014fa98-ffff80001014fb2c: sched_rt_rq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_rt_rq_enqueue(struct rt_rq *rt_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039d820)
Location: kernel/sched/rt.c:486
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
c039d820-c039d8a0: sched_rt_rq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_rt_rq_enqueue(struct rt_rq *rt_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a38f0)
Location: kernel/sched/rt.c:486
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
c0000000001a38f0-c0000000001a39f0: sched_rt_rq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_rt_rq_enqueue(struct rt_rq *rt_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f82f4)
Location: kernel/sched/rt.c:486
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffe0000f82f4-ffffffe0000f8386: sched_rt_rq_enqueue (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810e8374)
Location: kernel/sched/rt.c:588
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_rt_rq_enqueue(struct rt_rq *rt_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d7cc0)
Location: kernel/sched/rt.c:486
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff810d7cc0-ffffffff810d7d46: sched_rt_rq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_rt_rq_enqueue(struct rt_rq *rt_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4e30)
Location: kernel/sched/rt.c:486
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff810e4e30-ffffffff810e4eb6: sched_rt_rq_enqueue (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810f102e)
Location: kernel/sched/rt.c:588
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
</ul>
