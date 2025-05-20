# Function: <code>force_qs_rnp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void force_qs_rnp(struct rcu_state *rsp, int (*f)(struct rcu_data *, bool *, long unsigned int *), bool *isidle, long unsigned int *maxj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e65e0)
Location: kernel/rcu/tree.c:2798
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810e65e0-ffffffff810e674b: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void force_qs_rnp(struct rcu_state *rsp, int (*f)(struct rcu_data *, bool *, long unsigned int *), bool *isidle, long unsigned int *maxj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ec620)
Location: kernel/rcu/tree.c:2881
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810ec620-ffffffff810ec7be: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void force_qs_rnp(struct rcu_state *rsp, int (*f)(struct rcu_data *, bool *, long unsigned int *), bool *isidle, long unsigned int *maxj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2e30)
Location: kernel/rcu/tree.c:2884
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f2e30-ffffffff810f2fd2: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void force_qs_rnp(struct rcu_state *rsp, int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f38c0)
Location: kernel/rcu/tree.c:2875
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f38c0-ffffffff810f3a75: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void force_qs_rnp(struct rcu_state *rsp, int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fd310)
Location: kernel/rcu/tree.c:2856
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810fd310-ffffffff810fd4b2: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void force_qs_rnp(struct rcu_state *rsp, int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81104bb0)
Location: kernel/rcu/tree.c:2660
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81104bb0-ffffffff81104d14: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110410)
Location: kernel/rcu/tree.c:2543
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81110410-ffffffff81110560: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111a050)
Location: kernel/rcu/tree.c:2196
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111a050-ffffffff8111a1bb: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81126460)
Location: kernel/rcu/tree.c:2258
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81126460-ffffffff811265cb: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133c40)
Location: kernel/rcu/tree.c:2517
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff81133c40-ffffffff81133de9: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112f3c0)
Location: kernel/rcu/tree.c:2644
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff8112f3c0-ffffffff8112f549: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112ff20)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff8112ff20-ffffffff811300b2: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2614
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff81151c70-ffffffff81151ed6: force_qs_rnp (STB_LOCAL)
ffffffff81caec1f-ffffffff81caec34: force_qs_rnp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2691
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff8117b3a0-ffffffff8117b646: force_qs_rnp (STB_LOCAL)
ffffffff81e5f75b-ffffffff81e5f76f: force_qs_rnp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b1ed0)
Location: kernel/rcu/tree.c:2359
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff811b1ed0-ffffffff811b218d: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c3cd0)
Location: kernel/rcu/tree.c:2252
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff811c3cd0-ffffffff811c3f8d: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811dc730)
Location: kernel/rcu/tree.c:2307
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
**Symbols:**

```
ffffffff811dc730-ffffffff811dcaaa: force_qs_rnp (STB_LOCAL)
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
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018dff8)
Location: kernel/rcu/tree.c:2258
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffff80001018dff8-ffff80001018e1dc: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03db8fc)
Location: kernel/rcu/tree.c:2258
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
c03db8fc-c03dba9c: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e83f0)
Location: kernel/rcu/tree.c:2258
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
c0000000001e83f0-c0000000001e8624: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120e7e)
Location: kernel/rcu/tree.c:2258
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffe000120e7e-ffffffe000120ff2: force_qs_rnp (STB_LOCAL)
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
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111ea40)
Location: kernel/rcu/tree.c:2258
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111ea40-ffffffff8111ebab: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110f9f0)
Location: kernel/rcu/tree.c:2258
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8110f9f0-ffffffff8110fb63: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111c930)
Location: kernel/rcu/tree.c:2258
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111c930-ffffffff8111ca9b: force_qs_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void force_qs_rnp(int (*f)(struct rcu_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811290a0)
Location: kernel/rcu/tree.c:2258
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811290a0-ffffffff81129203: force_qs_rnp (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool *isidle</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *maxj</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*f)(struct rcu_data *, bool *, long unsigned int *)</code> ➡️ <code>int (*f)(struct rcu_data *)</code>
</li>
</ul>
</details>
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
<code>rsp, f</code> ➡️ <code>f</code>
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
