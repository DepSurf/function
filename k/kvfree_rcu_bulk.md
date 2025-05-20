# Function: <code>kvfree_rcu_bulk</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kvfree_rcu_bulk(struct kfree_rcu_cpu *krcp, struct kvfree_rcu_bulk_data *bnode, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811ca9f0)
Location: kernel/rcu/tree.c:2944
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
```
**Symbols:**

```
ffffffff811ca9f0-ffffffff811caba4: kvfree_rcu_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kvfree_rcu_bulk(struct kfree_rcu_cpu *krcp, struct kvfree_rcu_bulk_data *bnode, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d9450)
Location: kernel/rcu/tree.c:3015
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
```
**Symbols:**

```
ffffffff811d9450-ffffffff811d9604: kvfree_rcu_bulk (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
