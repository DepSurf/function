# Function: <code>__sync_rcu_exp_select_node_cpus</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sync_rcu_exp_select_node_cpus(struct rcu_exp_work *rewp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117a9e0)
Location: kernel/rcu/tree_exp.h:337
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff8117a9e0-ffffffff8117ad8a: __sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sync_rcu_exp_select_node_cpus(struct rcu_exp_work *rewp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b5700)
Location: kernel/rcu/tree_exp.h:339
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811b5700-ffffffff811b5ba6: __sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sync_rcu_exp_select_node_cpus(struct rcu_exp_work *rewp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c6690)
Location: kernel/rcu/tree_exp.h:340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811c6690-ffffffff811c6b28: __sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sync_rcu_exp_select_node_cpus(struct rcu_exp_work *rewp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d68f0)
Location: kernel/rcu/tree_exp.h:339
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811d68f0-ffffffff811d6d8a: __sync_rcu_exp_select_node_cpus (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
