# Function: <code>schedule_delayed_monitor_work</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void schedule_delayed_monitor_work(struct kfree_rcu_cpu *krcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811afed0)
Location: kernel/rcu/tree.c:3135
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
**Symbols:**

```
ffffffff811afed0-ffffffff811aff6b: schedule_delayed_monitor_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void schedule_delayed_monitor_work(struct kfree_rcu_cpu *krcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c2060)
Location: kernel/rcu/tree.c:3087
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
**Symbols:**

```
ffffffff811c2060-ffffffff811c2102: schedule_delayed_monitor_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void schedule_delayed_monitor_work(struct kfree_rcu_cpu *krcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d2720)
Location: kernel/rcu/tree.c:3158
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
**Symbols:**

```
ffffffff811d2720-ffffffff811d27c2: schedule_delayed_monitor_work (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
