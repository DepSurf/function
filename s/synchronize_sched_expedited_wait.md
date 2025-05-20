# Function: <code>synchronize_sched_expedited_wait</code>

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
In kernel/rcu/tree.c (ffffffff810e53c2)
Location: kernel/rcu/tree.c:3770
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited
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
In kernel/rcu/tree.c (ffffffff810ebc97)
Location: kernel/rcu/tree_exp.h:409
Inline: True
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
In kernel/rcu/tree.c (ffffffff810f22c5)
Location: kernel/rcu/tree_exp.h:419
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
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
In kernel/rcu/tree.c (ffffffff810f2e81)
Location: kernel/rcu/tree_exp.h:435
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
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
In kernel/rcu/tree.c (ffffffff810fd9c1)
Location: kernel/rcu/tree_exp.h:435
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
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
In kernel/rcu/tree.c (ffffffff8110674f)
Location: kernel/rcu/tree_exp.h:512
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
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
In kernel/rcu/tree.c (ffffffff81111648)
Location: kernel/rcu/tree_exp.h:470
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:459
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff81119b00-ffffffff81119c78: synchronize_sched_expedited_wait (STB_LOCAL)
ffffffff8111e20e-ffffffff8111e4c3: synchronize_sched_expedited_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff81125e90-ffffffff81126008: synchronize_sched_expedited_wait (STB_LOCAL)
ffffffff8112a7dc-ffffffff8112aa84: synchronize_sched_expedited_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018d178)
Location: kernel/rcu/tree_exp.h:457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffff80001018d178-ffff80001018d5e4: synchronize_sched_expedited_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03da64c)
Location: kernel/rcu/tree_exp.h:457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
c03da64c-c03dab10: synchronize_sched_expedited_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e6b70)
Location: kernel/rcu/tree_exp.h:457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
c0000000001e6b70-c0000000001e7148: synchronize_sched_expedited_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120630)
Location: kernel/rcu/tree_exp.h:457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffe000120630-ffffffe000120a36: synchronize_sched_expedited_wait (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff8111e470-ffffffff8111e5e8: synchronize_sched_expedited_wait (STB_LOCAL)
ffffffff81122dbc-ffffffff81123064: synchronize_sched_expedited_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff8110f6a0-ffffffff8110f818: synchronize_sched_expedited_wait (STB_LOCAL)
ffffffff81115878-ffffffff81115b29: synchronize_sched_expedited_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff8111c360-ffffffff8111c4d8: synchronize_sched_expedited_wait (STB_LOCAL)
ffffffff81120cac-ffffffff81120f54: synchronize_sched_expedited_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void synchronize_sched_expedited_wait();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff81127c10-ffffffff81127d88: synchronize_sched_expedited_wait (STB_LOCAL)
ffffffff8112cf81-ffffffff8112d2a7: synchronize_sched_expedited_wait.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
