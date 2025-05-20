# Function: <code>call_rcu_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void call_rcu_bh(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7af0)
Location: kernel/rcu/tree.c:3120
Inline: False
Direct callers:
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_api.c:qdisc_put_stab
```
**Symbols:**

```
ffffffff810e7af0-ffffffff810e7b09: call_rcu_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void call_rcu_bh(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810edd00)
Location: kernel/rcu/tree.c:3198
Inline: False
Direct callers:
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_api.c:qdisc_put_stab
```
**Symbols:**

```
ffffffff810edd00-ffffffff810edd19: call_rcu_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void call_rcu_bh(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4c70)
Location: kernel/rcu/tree.c:3196
Inline: False
Direct callers:
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_api.c:qdisc_put_stab
```
**Symbols:**

```
ffffffff810f4c70-ffffffff810f4c89: call_rcu_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void call_rcu_bh(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f59b0)
Location: kernel/rcu/tree.c:3222
Inline: False
Direct callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
**Symbols:**

```
ffffffff810f59b0-ffffffff810f59c9: call_rcu_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void call_rcu_bh(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ff7b0)
Location: kernel/rcu/tree.c:3205
Inline: False
Direct callers:
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
```
**Symbols:**

```
ffffffff810ff7b0-ffffffff810ff7c9: call_rcu_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void call_rcu_bh(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811066e0)
Location: kernel/rcu/tree.c:3011
Inline: False
Direct callers:
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
```
**Symbols:**

```
ffffffff811066e0-ffffffff811066f9: call_rcu_bh (STB_GLOBAL)
```
</details>
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
</ul>
