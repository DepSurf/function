# Function: <code>rcu_accelerate_cbs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_state *rsp, struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e5e70)
Location: kernel/rcu/tree.c:1629
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810e5e70-ffffffff810e60a0: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_state *rsp, struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb3d0)
Location: kernel/rcu/tree.c:1737
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_advance_cbs
```
**Symbols:**

```
ffffffff810eb3d0-ffffffff810eb5f1: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_state *rsp, struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f3060)
Location: kernel/rcu/tree.c:1739
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_advance_cbs
```
**Symbols:**

```
ffffffff810f3060-ffffffff810f3281: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_state *rsp, struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f3d40)
Location: kernel/rcu/tree.c:1813
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
```
**Symbols:**

```
ffffffff810f3d40-ffffffff810f3ec7: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_state *rsp, struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fd5d0)
Location: kernel/rcu/tree.c:1885
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
```
**Symbols:**

```
ffffffff810fd5d0-ffffffff810fd757: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_state *rsp, struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81106120)
Location: kernel/rcu/tree.c:1745
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
```
**Symbols:**

```
ffffffff81106120-ffffffff81106295: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111da0)
Location: kernel/rcu/tree.c:1595
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81111da0-ffffffff81111eef: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111b660)
Location: kernel/rcu/tree.c:1249
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff8111b660-ffffffff8111b7d4: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127dc0)
Location: kernel/rcu/tree.c:1257
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81127dc0-ffffffff81127f4e: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135af0)
Location: kernel/rcu/tree.c:1457
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81135af0-ffffffff81135b63: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811312a0)
Location: kernel/rcu/tree.c:1537
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811312a0-ffffffff81131316: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131a90)
Location: kernel/rcu/tree.c:1541
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81131a90-ffffffff81131b06: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81153ab0)
Location: kernel/rcu/tree.c:1494
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81153ab0-ffffffff81153b26: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811786d0)
Location: kernel/rcu/tree.c:1510
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811786d0-ffffffff8117875a: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811afdf0)
Location: kernel/rcu/tree.c:1085
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811afdf0-ffffffff811afe7a: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c1e60)
Location: kernel/rcu/tree.c:1045
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811c1e60-ffffffff811c1eea: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d2510)
Location: kernel/rcu/tree.c:1087
Inline: False
Direct callers:
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811d2510-ffffffff811d25a1: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018cd70)
Location: kernel/rcu/tree.c:1257
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffff80001018cd70-ffff80001018cf84: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03da2d4)
Location: kernel/rcu/tree.c:1257
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
c03da2d4-c03da4a4: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e8630)
Location: kernel/rcu/tree.c:1257
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
c0000000001e8630-c0000000001e88e0: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe0001226e6)
Location: kernel/rcu/tree.c:1257
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffe0001226e6-ffffffe0001228a2: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811203a0)
Location: kernel/rcu/tree.c:1257
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811203a0-ffffffff8112052e: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111cd0)
Location: kernel/rcu/tree.c:1257
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81111cd0-ffffffff81111e6f: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e290)
Location: kernel/rcu/tree.c:1257
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff8111e290-ffffffff8111e41e: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rcu_accelerate_cbs(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811287c0)
Location: kernel/rcu/tree.c:1257
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811287c0-ffffffff8112895a: rcu_accelerate_cbs (STB_LOCAL)
```
</details>
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
<li>
<b>Param reordered. </b>
<code>rsp, rnp, rdp</code> ➡️ <code>rnp, rdp</code>
</li>
</ul>
</details>
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
