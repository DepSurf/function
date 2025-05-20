# Function: <code>start_poll_synchronize_rcu_expedited</code>

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
long unsigned int start_poll_synchronize_rcu_expedited();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b03f0)
Location: kernel/rcu/tree_exp.h:1014
Inline: False
Direct callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811b03f0-ffffffff811b0508: start_poll_synchronize_rcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int start_poll_synchronize_rcu_expedited();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c23c0)
Location: kernel/rcu/tree_exp.h:1058
Inline: False
Direct callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811c23c0-ffffffff811c24df: start_poll_synchronize_rcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int start_poll_synchronize_rcu_expedited();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d2930)
Location: kernel/rcu/tree_exp.h:1061
Inline: False
Direct callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811d2930-ffffffff811d2a4f: start_poll_synchronize_rcu_expedited (STB_GLOBAL)
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
