# Function: <code>have_governor_per_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816ae710)
Location: drivers/cpufreq/cpufreq.c:151
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
```
**Symbols:**

```
ffffffff816ae710-ffffffff816ae72c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81710070)
Location: drivers/cpufreq/cpufreq.c:114
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff81710070-ffffffff8171008c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81742050)
Location: drivers/cpufreq/cpufreq.c:114
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff81742050-ffffffff8174206c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817606c0)
Location: drivers/cpufreq/cpufreq.c:114
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff817606c0-ffffffff817606dc: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d6680)
Location: drivers/cpufreq/cpufreq.c:114
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff817d6680-ffffffff817d669c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8181f395)
Location: drivers/cpufreq/cpufreq.c:105
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff8181f370-ffffffff8181f38c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184b235)
Location: drivers/cpufreq/cpufreq.c:105
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff8184b210-ffffffff8184b22c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188e2f5)
Location: drivers/cpufreq/cpufreq.c:99
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff8188e2d0-ffffffff8188e2ec: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c0485)
Location: drivers/cpufreq/cpufreq.c:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff818c0460-ffffffff818c047c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81992415)
Location: drivers/cpufreq/cpufreq.c:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff819923f0-ffffffff8199240c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995665)
Location: drivers/cpufreq/cpufreq.c:108
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff81995640-ffffffff8199565d: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197a4d5)
Location: drivers/cpufreq/cpufreq.c:105
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff8197a4b0-ffffffff8197a4cd: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a234e5)
Location: drivers/cpufreq/cpufreq.c:105
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff81a234c0-ffffffff81a234dd: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8c765)
Location: drivers/cpufreq/cpufreq.c:106
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff81b8c730-ffffffff81b8c751: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c175)
Location: drivers/cpufreq/cpufreq.c:106
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff81d2c130-ffffffff81d2c151: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d95405)
Location: drivers/cpufreq/cpufreq.c:111
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff81d953c0-ffffffff81d953e1: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4cf15)
Location: drivers/cpufreq/cpufreq.c:112
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff81e4ced0-ffffffff81e4cef1: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1ce08)
Location: drivers/cpufreq/cpufreq.c:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffff800010b1cdc8-ffff800010b1cdf0: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf7ce8)
Location: drivers/cpufreq/cpufreq.c:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
c0bf7ca8-c0bf7cd4: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c0f870)
Location: drivers/cpufreq/cpufreq.c:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
c000000000c0f830-c000000000c0f854: have_governor_per_policy (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81864ba5)
Location: drivers/cpufreq/cpufreq.c:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff81864b80-ffffffff81864b9c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182d855)
Location: drivers/cpufreq/cpufreq.c:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff8182d830-ffffffff8182d84c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b5935)
Location: drivers/cpufreq/cpufreq.c:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff818b5910-ffffffff818b592c: have_governor_per_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool have_governor_per_policy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d1be5)
Location: drivers/cpufreq/cpufreq.c:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_governor_parent_kobj
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_exit
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
**Symbols:**

```
ffffffff818d1bc0-ffffffff818d1bdc: have_governor_per_policy (STB_GLOBAL)
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
