# Function: <code>rcu_segcblist_pend_cbs</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f7355)
Location: kernel/rcu/rcu_segcblist.c:130
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_extract_pend_cbs
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff810f70c0-ffffffff810f70df: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811010a0)
Location: kernel/rcu/rcu_segcblist.c:102
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811010a0-ffffffff811010bf: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81109520)
Location: kernel/rcu/rcu_segcblist.c:102
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81109520-ffffffff8110953f: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81114cf0)
Location: kernel/rcu/rcu_segcblist.c:102
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81114cf0-ffffffff81114d0f: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111eb20)
Location: kernel/rcu/rcu_segcblist.c:89
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff8111eb20-ffffffff8111eb3f: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b1f5)
Location: kernel/rcu/rcu_segcblist.c:203
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff8112b190-ffffffff8112b1b0: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139795)
Location: kernel/rcu/rcu_segcblist.c:192
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/srcutree.c:srcu_might_be_idle
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81139730-ffffffff81139750: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134265)
Location: kernel/rcu/rcu_segcblist.c:192
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/srcutree.c:srcu_might_be_idle
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81134200-ffffffff81134220: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81135075)
Location: kernel/rcu/rcu_segcblist.c:290
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81135000-ffffffff81135021: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81157875)
Location: kernel/rcu/rcu_segcblist.c:290
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81157800-ffffffff81157821: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180b25)
Location: kernel/rcu/rcu_segcblist.c:288
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81180a90-ffffffff81180ab7: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb3f5)
Location: kernel/rcu/rcu_segcblist.c:288
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811bb330-ffffffff811bb357: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cdd95)
Location: kernel/rcu/rcu_segcblist.c:288
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811cdcd0-ffffffff811cdcf7: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e29b5)
Location: kernel/rcu/rcu_segcblist.c:288
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811e28f0-ffffffff811e2917: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193304)
Location: kernel/rcu/rcu_segcblist.c:203
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffff800010193210-ffff80001019325c: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0664)
Location: kernel/rcu/rcu_segcblist.c:203
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
c03e05c0-c03e05fc: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee388)
Location: kernel/rcu/rcu_segcblist.c:203
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
c0000000001ee2e0-c0000000001ee318: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125902)
Location: kernel/rcu/rcu_segcblist.c:203
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffe000125862-ffffffe000125892: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811237d5)
Location: kernel/rcu/rcu_segcblist.c:203
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81123770-ffffffff81123790: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81116295)
Location: kernel/rcu/rcu_segcblist.c:203
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81116230-ffffffff81116250: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811216c5)
Location: kernel/rcu/rcu_segcblist.c:203
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81121660-ffffffff81121680: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_pend_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dcd5)
Location: kernel/rcu/rcu_segcblist.c:203
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff8112dc70-ffffffff8112dc90: rcu_segcblist_pend_cbs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
