# Function: <code>sugov_kthread_create</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d478e)
Location: kernel/sched/cpufreq_schedutil.c:402
Inline: True
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810d3b5e)
Location: kernel/sched/cpufreq_schedutil.c:419
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810db82e)
Location: kernel/sched/cpufreq_schedutil.c:470
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810e3901)
Location: kernel/sched/cpufreq_schedutil.c:571
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810edf11)
Location: kernel/sched/cpufreq_schedutil.c:644
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f4cbb)
Location: kernel/sched/cpufreq_schedutil.c:651
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110092b)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sugov_kthread_create(struct sugov_policy *sg_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff8110af40-ffffffff8110b0cd: sugov_kthread_create (STB_LOCAL)
ffffffff8110bae7-ffffffff8110bafe: sugov_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sugov_kthread_create(struct sugov_policy *sg_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:679
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81107e70-ffffffff81108006: sugov_kthread_create (STB_LOCAL)
ffffffff81bde7e2-ffffffff81bde7f9: sugov_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sugov_kthread_create(struct sugov_policy *sg_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:566
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81109fb0-ffffffff8110a146: sugov_kthread_create (STB_LOCAL)
ffffffff81bd098a-ffffffff81bd09a1: sugov_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sugov_kthread_create(struct sugov_policy *sg_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:575
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81128540-ffffffff811286e4: sugov_kthread_create (STB_LOCAL)
ffffffff81ca926c-ffffffff81ca9298: sugov_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sugov_kthread_create(struct sugov_policy *sg_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:575
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff81142360-ffffffff81142522: sugov_kthread_create (STB_LOCAL)
ffffffff81e57ce7-ffffffff81e57d13: sugov_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sugov_kthread_create(struct sugov_policy *sg_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:574
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff8116e7b0-ffffffff8116e986: sugov_kthread_create (STB_LOCAL)
ffffffff82057e2b-ffffffff82057e40: sugov_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sugov_kthread_create(struct sugov_policy *sg_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:578
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff8117ee50-ffffffff8117f026: sugov_kthread_create (STB_LOCAL)
ffffffff820d65d7-ffffffff820d65ec: sugov_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sugov_kthread_create(struct sugov_policy *sg_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:644
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff8118cc40-ffffffff8118ce16: sugov_kthread_create (STB_LOCAL)
ffffffff821b1770-ffffffff821b1785: sugov_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffff800010165124)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c03b1720)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c0000000001bc2d8)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9c3b)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810e9e1b)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f6e5b)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81101edb)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
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
