# Function: <code>rcu_report_qs_rnp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4900)
Location: kernel/rcu/tree.c:2247
Inline: False
Direct callers:
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810e4900-ffffffff810e4a7a: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ea8f0)
Location: kernel/rcu/tree.c:2361
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_qs_rnp
```
**Symbols:**

```
ffffffff810ea8f0-ffffffff810eaa6c: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f18b0)
Location: kernel/rcu/tree.c:2365
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_qs_rnp
```
**Symbols:**

```
ffffffff810f18b0-ffffffff810f1a28: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2740)
Location: kernel/rcu/tree.c:2391
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_qs_rnp
```
**Symbols:**

```
ffffffff810f2740-ffffffff810f284c: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc4d0)
Location: kernel/rcu/tree.c:2463
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_qs_rnp
```
**Symbols:**

```
ffffffff810fc4d0-ffffffff810fc5dc: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811048e0)
Location: kernel/rcu/tree.c:2263
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_qs_rnp
```
**Symbols:**

```
ffffffff811048e0-ffffffff811049e9: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811102e0)
Location: kernel/rcu/tree.c:2157
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811102e0-ffffffff811103da: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81119f40)
Location: kernel/rcu/tree.c:1811
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81119f40-ffffffff8111a048: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81126350)
Location: kernel/rcu/tree.c:1843
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81126350-ffffffff81126458: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133b30)
Location: kernel/rcu/tree.c:2087
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff81133b30-ffffffff81133c3e: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112f2b0)
Location: kernel/rcu/tree.c:2207
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff8112f2b0-ffffffff8112f3be: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112f810)
Location: kernel/rcu/tree.c:2220
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff8112f810-ffffffff8112f91e: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81151140)
Location: kernel/rcu/tree.c:2174
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff81151140-ffffffff8115124e: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117b230)
Location: kernel/rcu/tree.c:2230
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff8117b230-ffffffff8117b396: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b1d50)
Location: kernel/rcu/tree.c:1898
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811b1d50-ffffffff811b1eb6: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c3b80)
Location: kernel/rcu/tree.c:1851
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811c3b80-ffffffff811c3cb4: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d4cb0)
Location: kernel/rcu/tree.c:1905
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcutree_report_cpu_dead
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811d4cb0-ffffffff811d4de4: rcu_report_qs_rnp (STB_LOCAL)
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
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018dde8)
Location: kernel/rcu/tree.c:1843
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffff80001018dde8-ffff80001018dff8: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03db76c)
Location: kernel/rcu/tree.c:1843
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
c03db76c-c03db8fc: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e8250)
Location: kernel/rcu/tree.c:1843
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
c0000000001e8250-c0000000001e83ec: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120d8a)
Location: kernel/rcu/tree.c:1843
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffe000120d8a-ffffffe000120e7e: rcu_report_qs_rnp (STB_LOCAL)
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
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e930)
Location: kernel/rcu/tree.c:1843
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111e930-ffffffff8111ea38: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110f8e0)
Location: kernel/rcu/tree.c:1843
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8110f8e0-ffffffff8110f9e8: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111c820)
Location: kernel/rcu/tree.c:1843
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111c820-ffffffff8111c928: rcu_report_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_report_qs_rnp(long unsigned int mask, struct rcu_node *rnp, long unsigned int gps, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81128f80)
Location: kernel/rcu/tree.c:1843
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81128f80-ffffffff81129091: rcu_report_qs_rnp (STB_LOCAL)
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
<code>mask, rsp, rnp, gps, flags</code> ➡️ <code>mask, rnp, gps, flags</code>
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
