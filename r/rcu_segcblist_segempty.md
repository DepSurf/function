# Function: <code>rcu_segcblist_segempty</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool rcu_segcblist_segempty(struct rcu_segcblist *rsclp, int seg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f7070)
Location: kernel/rcu/rcu_segcblist.c:109
Inline: False
```
**Symbols:**

```
ffffffff810f7070-ffffffff810f7097: rcu_segcblist_segempty (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0fac)
Location: kernel/rcu/rcu_segcblist.h:121
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811d3e30)
Location: kernel/rcu/rcu_segcblist.h:121
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_state
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e3018)
Location: kernel/rcu/rcu_segcblist.h:121
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
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
</ul>
