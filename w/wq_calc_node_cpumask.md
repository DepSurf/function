# Function: <code>wq_calc_node_cpumask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810975e0)
Location: kernel/workqueue.c:3437
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810975e0-ffffffff810976b5: wq_calc_node_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109acd0)
Location: kernel/workqueue.c:3538
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff8109acd0-ffffffff8109ad9b: wq_calc_node_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1250)
Location: kernel/workqueue.c:3566
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810a1250-ffffffff810a1328: wq_calc_node_cpumask.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff8109f1d0)
Location: kernel/workqueue.c:3564
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff8109f1d0-ffffffff8109f2e3: wq_calc_node_cpumask.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a58c0)
Location: kernel/workqueue.c:3575
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810a58c0-ffffffff810a59d3: wq_calc_node_cpumask.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3648
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810ab770-ffffffff810ab86d: wq_calc_node_cpumask.isra.26 (STB_LOCAL)
ffffffff810b0226-ffffffff810b0240: wq_calc_node_cpumask.isra.26.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3671
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810b4a30-ffffffff810b4b34: wq_calc_node_cpumask.isra.28 (STB_LOCAL)
ffffffff810b9396-ffffffff810b93b0: wq_calc_node_cpumask.isra.28.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3812
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810ba820-ffffffff810ba926: wq_calc_node_cpumask.isra.0 (STB_LOCAL)
ffffffff810bef95-ffffffff810befb0: wq_calc_node_cpumask.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3821
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810c0c70-ffffffff810c0d76: wq_calc_node_cpumask.isra.0 (STB_LOCAL)
ffffffff810c54a2-ffffffff810c54bd: wq_calc_node_cpumask.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3830
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810c83b0-ffffffff810c84c5: wq_calc_node_cpumask (STB_LOCAL)
ffffffff810cd083-ffffffff810cd09e: wq_calc_node_cpumask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3843
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810c3510-ffffffff810c3617: wq_calc_node_cpumask (STB_LOCAL)
ffffffff81bdbed8-ffffffff81bdbef3: wq_calc_node_cpumask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3850
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810c4280-ffffffff810c4393: wq_calc_node_cpumask (STB_LOCAL)
ffffffff81bcdfba-ffffffff81bcdfd5: wq_calc_node_cpumask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3889
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810d6e30-ffffffff810d6fae: wq_calc_node_cpumask (STB_LOCAL)
ffffffff81ca509e-ffffffff81ca5105: wq_calc_node_cpumask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3872
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810f36c0-ffffffff810f3839: wq_calc_node_cpumask (STB_LOCAL)
ffffffff81e54b33-ffffffff81e54b89: wq_calc_node_cpumask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3879
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff81115800-ffffffff8111598c: wq_calc_node_cpumask (STB_LOCAL)
ffffffff8205664f-ffffffff8205668d: wq_calc_node_cpumask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4207
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff811223d0-ffffffff811225a0: wq_calc_node_cpumask (STB_LOCAL)
ffffffff820d4bca-ffffffff820d4c23: wq_calc_node_cpumask.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011d7d8)
Location: kernel/workqueue.c:3821
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffff80001011d7d8-ffff80001011d980: wq_calc_node_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (c0374bb8)
Location: kernel/workqueue.c:3821
Inline: True
Direct callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
c0374bb8-c0374bdc: wq_calc_node_cpumask.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs *attrs, int node, int cpu_going_down, cpumask_t *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000167ae0)
Location: kernel/workqueue.c:3821
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
c000000000167ae0-c000000000167cd8: wq_calc_node_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d6b5a)
Location: kernel/workqueue.c:3821
Inline: True
Direct callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffe0000d6b5a-ffffffe0000d6bc2: wq_calc_node_cpumask.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3821
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810bafe0-ffffffff810bb0e6: wq_calc_node_cpumask.isra.0 (STB_LOCAL)
ffffffff810bf812-ffffffff810bf82d: wq_calc_node_cpumask.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3821
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810a9ad0-ffffffff810a9bd6: wq_calc_node_cpumask.isra.0 (STB_LOCAL)
ffffffff810ae032-ffffffff810ae04d: wq_calc_node_cpumask.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3821
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810ba540-ffffffff810ba646: wq_calc_node_cpumask.isra.0 (STB_LOCAL)
ffffffff810bed72-ffffffff810bed8d: wq_calc_node_cpumask.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3821
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810c4930-ffffffff810c4a36: wq_calc_node_cpumask.isra.0 (STB_LOCAL)
ffffffff810c7125-ffffffff810c7140: wq_calc_node_cpumask.isra.0.cold (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
