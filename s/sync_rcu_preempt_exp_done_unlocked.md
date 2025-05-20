# Function: <code>sync_rcu_preempt_exp_done_unlocked</code>

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
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81104850)
Location: kernel/rcu/tree_exp.h:174
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff81104850-ffffffff81104891: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110230)
Location: kernel/rcu/tree_exp.h:174
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff81110230-ffffffff81110271: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81119a60)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff81119a60-ffffffff81119aa5: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81125df0)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff81125df0-ffffffff81125e35: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
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
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018d0c0)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffff80001018d0c0-ffff80001018d174: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03d9f7c)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
c03d9f7c-c03d9fc4: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e6600)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
c0000000001e6600-c0000000001e66a4: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120544)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffe000120544-ffffffe000120590: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
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
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e3d0)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff8111e3d0-ffffffff8111e415: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110f430)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff8110f430-ffffffff8110f475: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111c2c0)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff8111c2c0-ffffffff8111c305: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool sync_rcu_preempt_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811279d0)
Location: kernel/rcu/tree_exp.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff811279d0-ffffffff81127a15: sync_rcu_preempt_exp_done_unlocked (STB_LOCAL)
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
