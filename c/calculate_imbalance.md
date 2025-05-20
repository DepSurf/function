# Function: <code>calculate_imbalance</code>

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
In kernel/sched/fair.c (ffffffff810bcdd1)
Location: kernel/sched/fair.c:6641
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810c05df)
Location: kernel/sched/fair.c:7113
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810c65e8)
Location: kernel/sched/fair.c:7692
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810c0248)
Location: kernel/sched/fair.c:7689
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810c78f4)
Location: kernel/sched/fair.c:8138
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810cfc24)
Location: kernel/sched/fair.c:8491
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810d9053)
Location: kernel/sched/fair.c:8538
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810e0308)
Location: kernel/sched/fair.c:8437
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810ea998)
Location: kernel/sched/fair.c:8420
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810f4bda)
Location: kernel/sched/fair.c:8967
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void calculate_imbalance(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e65f0)
Location: kernel/sched/fair.c:9066
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810e65f0-ffffffff810e6785: calculate_imbalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void calculate_imbalance(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e85c0)
Location: kernel/sched/fair.c:9120
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810e85c0-ffffffff810e8749: calculate_imbalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void calculate_imbalance(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ffc90)
Location: kernel/sched/fair.c:9355
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810ffc90-ffffffff810ffe19: calculate_imbalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void calculate_imbalance(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111ae50)
Location: kernel/sched/fair.c:9429
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff8111ae50-ffffffff8111b052: calculate_imbalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void calculate_imbalance(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811428e0)
Location: kernel/sched/fair.c:9944
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff811428e0-ffffffff81142ae8: calculate_imbalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void calculate_imbalance(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811528b0)
Location: kernel/sched/fair.c:10217
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff811528b0-ffffffff81152acb: calculate_imbalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void calculate_imbalance(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115f0f0)
Location: kernel/sched/fair.c:10636
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff8115f0f0-ffffffff8115f3fb: calculate_imbalance (STB_LOCAL)
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
In kernel/sched/fair.c (ffff80001014ab24)
Location: kernel/sched/fair.c:8420
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (c03987a0)
Location: kernel/sched/fair.c:8420
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (c00000000019ce84)
Location: kernel/sched/fair.c:8420
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f44d2)
Location: kernel/sched/fair.c:8420
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810e4af8)
Location: kernel/sched/fair.c:8420
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810d3ca8)
Location: kernel/sched/fair.c:8420
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810e0ec8)
Location: kernel/sched/fair.c:8420
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810eca68)
Location: kernel/sched/fair.c:8420
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
