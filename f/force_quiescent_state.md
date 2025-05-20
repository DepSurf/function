# Function: <code>force_quiescent_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void force_quiescent_state(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e47b0)
Location: kernel/rcu/tree.c:2861
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_bh_force_quiescent_state
  - kernel/rcu/tree.c:rcu_sched_force_quiescent_state
  - kernel/rcu/tree.c:rcu_check_callbacks
```
**Symbols:**

```
ffffffff810e47b0-ffffffff810e48a6: force_quiescent_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void force_quiescent_state(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ea750)
Location: kernel/rcu/tree.c:2941
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_sched_force_quiescent_state
  - kernel/rcu/tree.c:rcu_bh_force_quiescent_state
```
**Symbols:**

```
ffffffff810ea750-ffffffff810ea857: force_quiescent_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void force_quiescent_state(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f1650)
Location: kernel/rcu/tree.c:2944
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_sched_force_quiescent_state
  - kernel/rcu/tree.c:rcu_bh_force_quiescent_state
```
**Symbols:**

```
ffffffff810f1650-ffffffff810f1753: force_quiescent_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void force_quiescent_state(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f24f0)
Location: kernel/rcu/tree.c:2932
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_bh_force_quiescent_state
  - kernel/rcu/tree.c:rcu_force_quiescent_state
```
**Symbols:**

```
ffffffff810f24f0-ffffffff810f25e6: force_quiescent_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void force_quiescent_state(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc280)
Location: kernel/rcu/tree.c:2913
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_bh_force_quiescent_state
  - kernel/rcu/tree.c:rcu_force_quiescent_state
```
**Symbols:**

```
ffffffff810fc280-ffffffff810fc376: force_quiescent_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void force_quiescent_state(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81105ef0)
Location: kernel/rcu/tree.c:2717
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_bh_force_quiescent_state
  - kernel/rcu/tree.c:rcu_force_quiescent_state
```
**Symbols:**

```
ffffffff81105ef0-ffffffff81105fc7: force_quiescent_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void force_quiescent_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111980)
Location: kernel/rcu/tree.c:2590
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_force_quiescent_state
```
**Symbols:**

```
ffffffff81111980-ffffffff81111a43: force_quiescent_state (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct rcu_state *rsp</code>
</li>
</ul>
</details>
</li>
</ul>
