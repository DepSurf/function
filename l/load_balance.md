# Function: <code>load_balance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd1c0)
Location: kernel/sched/fair.c:6965
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff810bd1c0-ffffffff810bdb33: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c0950)
Location: kernel/sched/fair.c:7431
Inline: False
Direct callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810c0950-ffffffff810c1349: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c6950)
Location: kernel/sched/fair.c:8008
Inline: False
Direct callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810c6950-ffffffff810c7342: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c0580)
Location: kernel/sched/fair.c:8002
Inline: False
Direct callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810c0580-ffffffff810c0f11: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c7c90)
Location: kernel/sched/fair.c:8462
Inline: False
Direct callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810c7c90-ffffffff810c8641: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cfc90)
Location: kernel/sched/fair.c:8815
Inline: False
Direct callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810cfc90-ffffffff810d0656: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d9460)
Location: kernel/sched/fair.c:8909
Inline: False
Direct callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810d9460-ffffffff810d9e91: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e06d0)
Location: kernel/sched/fair.c:8822
Inline: False
Direct callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810e06d0-ffffffff810e11bf: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ead60)
Location: kernel/sched/fair.c:8805
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff810ead60-ffffffff810eb855: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4e00)
Location: kernel/sched/fair.c:9485
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff810f4e00-ffffffff810f561c: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f2e70)
Location: kernel/sched/fair.c:9586
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff810f2e70-ffffffff810f3703: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f5050)
Location: kernel/sched/fair.c:9652
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff810f5050-ffffffff810f56e6: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:9893
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff8110eb40-ffffffff8110f38f: load_balance (STB_LOCAL)
ffffffff81ca6709-ffffffff81ca6732: load_balance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:9976
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff8112aa70-ffffffff8112b34c: load_balance (STB_LOCAL)
ffffffff81e55f2a-ffffffff81e55f5c: load_balance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:10503
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff81154440-ffffffff81154d04: load_balance (STB_LOCAL)
ffffffff8205711c-ffffffff8205714e: load_balance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:10803
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff811645b0-ffffffff81164ebd: load_balance (STB_LOCAL)
ffffffff820d5944-ffffffff820d597a: load_balance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11264
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff81171360-ffffffff81171c0d: load_balance (STB_LOCAL)
ffffffff821b09a7-ffffffff821b09dd: load_balance.cold (STB_LOCAL)
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
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014ae90)
Location: kernel/sched/fair.c:8805
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffff80001014ae90-ffff80001014bad0: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0398ba8)
Location: kernel/sched/fair.c:8805
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
c0398ba8-c0399754: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019d3b0)
Location: kernel/sched/fair.c:8805
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
c00000000019d3b0-c00000000019e1cc: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f47b4)
Location: kernel/sched/fair.c:8805
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffe0000f47b4-ffffffe0000f5230: load_balance (STB_LOCAL)
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
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e4ec0)
Location: kernel/sched/fair.c:8805
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff810e4ec0-ffffffff810e59b5: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d4070)
Location: kernel/sched/fair.c:8805
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff810d4070-ffffffff810d4b5f: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1290)
Location: kernel/sched/fair.c:8805
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff810e1290-ffffffff810e1d85: load_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq *this_rq, struct sched_domain *sd, enum cpu_idle_type idle, int *continue_balancing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ece30)
Location: kernel/sched/fair.c:8805
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
```
**Symbols:**

```
ffffffff810ece30-ffffffff810ed944: load_balance (STB_LOCAL)
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
