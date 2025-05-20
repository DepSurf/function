# Function: <code>sugov_tunables_free</code>

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
In kernel/sched/cpufreq_schedutil.c (ffffffff810d4b25)
Location: kernel/sched/cpufreq_schedutil.c:464
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810d3ef5)
Location: kernel/sched/cpufreq_schedutil.c:481
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810dbb95)
Location: kernel/sched/cpufreq_schedutil.c:536
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810e3c55)
Location: kernel/sched/cpufreq_schedutil.c:646
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810ee2d5)
Location: kernel/sched/cpufreq_schedutil.c:719
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f5028)
Location: kernel/sched/cpufreq_schedutil.c:726
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81100ca8)
Location: kernel/sched/cpufreq_schedutil.c:729
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sugov_tunables_free(struct sugov_tunables *tunables);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b438)
Location: kernel/sched/cpufreq_schedutil.c:729
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff8110ae20-ffffffff8110ae50: sugov_tunables_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sugov_tunables_free(struct sugov_tunables *tunables);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811082f8)
Location: kernel/sched/cpufreq_schedutil.c:754
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81107d50-ffffffff81107d80: sugov_tunables_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sugov_tunables_free(struct sugov_tunables *tunables);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a438)
Location: kernel/sched/cpufreq_schedutil.c:641
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81109e90-ffffffff81109ec0: sugov_tunables_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sugov_tunables_free(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811280f0)
Location: kernel/sched/cpufreq_schedutil.c:540
Inline: False
```
**Symbols:**

```
ffffffff811280f0-ffffffff81128100: sugov_tunables_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sugov_tunables_free(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113cac0)
Location: kernel/sched/cpufreq_schedutil.c:540
Inline: False
```
**Symbols:**

```
ffffffff8113cac0-ffffffff8113cad6: sugov_tunables_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sugov_tunables_free(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81167430)
Location: kernel/sched/cpufreq_schedutil.c:539
Inline: False
```
**Symbols:**

```
ffffffff81167430-ffffffff81167446: sugov_tunables_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sugov_tunables_free(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81177870)
Location: kernel/sched/cpufreq_schedutil.c:543
Inline: False
```
**Symbols:**

```
ffffffff81177870-ffffffff81177886: sugov_tunables_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sugov_tunables_free(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81185580)
Location: kernel/sched/cpufreq_schedutil.c:584
Inline: False
```
**Symbols:**

```
ffffffff81185580-ffffffff81185596: sugov_tunables_free (STB_LOCAL)
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
In kernel/sched/cpufreq_schedutil.c (ffff800010165534)
Location: kernel/sched/cpufreq_schedutil.c:729
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (c03b1a9c)
Location: kernel/sched/cpufreq_schedutil.c:729
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (c0000000001bc7a0)
Location: kernel/sched/cpufreq_schedutil.c:729
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9fb8)
Location: kernel/sched/cpufreq_schedutil.c:729
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810ea198)
Location: kernel/sched/cpufreq_schedutil.c:729
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f71d8)
Location: kernel/sched/cpufreq_schedutil.c:729
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81102258)
Location: kernel/sched/cpufreq_schedutil.c:729
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sugov_tunables *tunables</code>
</li>
</ul>
</details>
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
