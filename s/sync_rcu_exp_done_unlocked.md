# Function: <code>sync_rcu_exp_done_unlocked</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool sync_rcu_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134548)
Location: kernel/rcu/tree_exp.h:161
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
```
**Symbols:**

```
ffffffff811336e0-ffffffff81133727: sync_rcu_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool sync_rcu_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112ffe8)
Location: kernel/rcu/tree_exp.h:161
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
```
**Symbols:**

```
ffffffff8112ed80-ffffffff8112edc7: sync_rcu_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool sync_rcu_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132245)
Location: kernel/rcu/tree_exp.h:161
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
```
**Symbols:**

```
ffffffff8112f3e0-ffffffff8112f427: sync_rcu_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool sync_rcu_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81154625)
Location: kernel/rcu/tree_exp.h:161
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
```
**Symbols:**

```
ffffffff81150990-ffffffff811509d7: sync_rcu_exp_done_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool sync_rcu_exp_done_unlocked(struct rcu_node *rnp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117e954)
Location: kernel/rcu/tree_exp.h:161
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
```
**Symbols:**

```
ffffffff811780a0-ffffffff81178101: sync_rcu_exp_done_unlocked (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff811b3e93)
Location: kernel/rcu/tree_exp.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
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
In kernel/rcu/tree.c (ffffffff811c7ef3)
Location: kernel/rcu/tree_exp.h:164
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
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
In kernel/rcu/tree.c (ffffffff811da565)
Location: kernel/rcu/tree_exp.h:164
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
