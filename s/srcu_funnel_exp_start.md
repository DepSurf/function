# Function: <code>srcu_funnel_exp_start</code>

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
void srcu_funnel_exp_start(struct srcu_struct *sp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f0be0)
Location: kernel/rcu/srcutree.c:583
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff810f0be0-ffffffff810f0c81: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *sp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fa9a0)
Location: kernel/rcu/srcutree.c:584
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff810fa9a0-ffffffff810faa41: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *sp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81102e30)
Location: kernel/rcu/srcutree.c:615
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81102e30-ffffffff81102ed1: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e820)
Location: kernel/rcu/srcutree.c:623
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8110e820-ffffffff8110e8c1: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81117f00)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81117f00-ffffffff81117f95: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811242c0)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff811242c0-ffffffff81124355: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811319d0)
Location: kernel/rcu/srcutree.c:611
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff811319d0-ffffffff81131a6f: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112d1b0)
Location: kernel/rcu/srcutree.c:600
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff8112d1b0-ffffffff8112d24f: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112d750)
Location: kernel/rcu/srcutree.c:603
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff8112d750-ffffffff8112d7ef: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114e940)
Location: kernel/rcu/srcutree.c:595
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff8114e940-ffffffff8114e9df: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81175cc0)
Location: kernel/rcu/srcutree.c:845
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff81175cc0-ffffffff81175db3: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811acbb0)
Location: kernel/rcu/srcutree.c:909
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff811acbb0-ffffffff811acca3: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811bea30)
Location: kernel/rcu/srcutree.c:958
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff811bea30-ffffffff811beb38: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811cef50)
Location: kernel/rcu/srcutree.c:949
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff811cef50-ffffffff811cf058: srcu_funnel_exp_start (STB_LOCAL)
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
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018b030)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffff80001018b030-ffff80001018b1e4: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d83e4)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
c03d83e4-c03d8494: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e4190)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
c0000000001e4190-c0000000001e4290: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011ecc4)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffe00011ecc4-ffffffe00011ed6a: srcu_funnel_exp_start (STB_LOCAL)
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
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111c8a0)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8111c8a0-ffffffff8111c935: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110d960)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8110d960-ffffffff8110d9f5: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111a790)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8111a790-ffffffff8111a825: srcu_funnel_exp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void srcu_funnel_exp_start(struct srcu_struct *ssp, struct srcu_node *snp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81126070)
Location: kernel/rcu/srcutree.c:598
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81126070-ffffffff81126105: srcu_funnel_exp_start (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct *ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
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
