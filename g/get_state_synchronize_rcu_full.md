# Function: <code>get_state_synchronize_rcu_full</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void get_state_synchronize_rcu_full(struct rcu_gp_oldstate *rgosp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b27c5)
Location: kernel/rcu/tree.c:3620
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_full
```
**Symbols:**

```
ffffffff811af750-ffffffff811af79a: get_state_synchronize_rcu_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void get_state_synchronize_rcu_full(struct rcu_gp_oldstate *rgosp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c5b45)
Location: kernel/rcu/tree.c:3612
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_full
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
**Symbols:**

```
ffffffff811c17c0-ffffffff811c180a: get_state_synchronize_rcu_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void get_state_synchronize_rcu_full(struct rcu_gp_oldstate *rgosp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d5e65)
Location: kernel/rcu/tree.c:3684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_full
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
**Symbols:**

```
ffffffff811d1cc0-ffffffff811d1d0a: get_state_synchronize_rcu_full (STB_GLOBAL)
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
