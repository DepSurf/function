# Function: <code>_nohz_idle_balance</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0930)
Location: kernel/sched/fair.c:9572
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810d0930-ffffffff810d0b86: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810da170)
Location: kernel/sched/fair.c:9675
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810da170-ffffffff810da3c6: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e14d0)
Location: kernel/sched/fair.c:9616
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810e14d0-ffffffff810e16d5: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebb70)
Location: kernel/sched/fair.c:9600
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810ebb70-ffffffff810ebd75: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f59b0)
Location: kernel/sched/fair.c:10286
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_newidle_balance
```
**Symbols:**

```
ffffffff810f59b0-ffffffff810f5bc4: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3ac0)
Location: kernel/sched/fair.c:10400
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_newidle_balance
```
**Symbols:**

```
ffffffff810f3ac0-ffffffff810f3d1a: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f62b0)
Location: kernel/sched/fair.c:10455
Inline: True
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_run_idle_balance
```
**Symbols:**

```
ffffffff810f62b0-ffffffff810f6508: _nohz_idle_balance.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:10697
Inline: True
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_run_idle_balance
```
**Symbols:**

```
ffffffff81110070-ffffffff81110322: _nohz_idle_balance.constprop.0.isra.0 (STB_LOCAL)
ffffffff81ca675c-ffffffff81ca678c: _nohz_idle_balance.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:10803
Inline: True
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_run_idle_balance
```
**Symbols:**

```
ffffffff8112c0a0-ffffffff8112c437: _nohz_idle_balance.constprop.0.isra.0 (STB_LOCAL)
ffffffff81e55f85-ffffffff81e55fc0: _nohz_idle_balance.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11331
Inline: True
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_run_idle_balance
```
**Symbols:**

```
ffffffff81155ce0-ffffffff811560dc: _nohz_idle_balance.isra.0 (STB_LOCAL)
ffffffff820571b3-ffffffff820571e4: _nohz_idle_balance.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11635
Inline: True
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_run_idle_balance
```
**Symbols:**

```
ffffffff81165e60-ffffffff81166242: _nohz_idle_balance.isra.0 (STB_LOCAL)
ffffffff820d59df-ffffffff820d5a0e: _nohz_idle_balance.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:12099
Inline: True
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_run_idle_balance
```
**Symbols:**

```
ffffffff81172bc0-ffffffff81172fa2: _nohz_idle_balance.isra.0 (STB_LOCAL)
ffffffff821b0a57-ffffffff821b0a86: _nohz_idle_balance.isra.0.cold (STB_LOCAL)
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
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014bdf0)
Location: kernel/sched/fair.c:9600
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffff80001014bdf0-ffff80001014c0a4: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0399ab8)
Location: kernel/sched/fair.c:9600
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
c0399ab8-c0399d18: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019e600)
Location: kernel/sched/fair.c:9600
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
c00000000019e600-c00000000019e944: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f54aa)
Location: kernel/sched/fair.c:9600
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffe0000f54aa-ffffffe0000f56ec: _nohz_idle_balance (STB_LOCAL)
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
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e5cd0)
Location: kernel/sched/fair.c:9600
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810e5cd0-ffffffff810e5ed5: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d4e70)
Location: kernel/sched/fair.c:9600
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810d4e70-ffffffff810d5075: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e20a0)
Location: kernel/sched/fair.c:9600
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810e20a0-ffffffff810e22a5: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq *this_rq, unsigned int flags, enum cpu_idle_type idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810edc40)
Location: kernel/sched/fair.c:9600
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810edc40-ffffffff810ede45: _nohz_idle_balance (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
