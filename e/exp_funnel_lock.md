# Function: <code>exp_funnel_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e506a)
Location: kernel/rcu/tree.c:3610
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb949)
Location: kernel/rcu/tree_exp.h:246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f34e6)
Location: kernel/rcu/tree_exp.h:246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f406a)
Location: kernel/rcu/tree_exp.h:262
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fe040)
Location: kernel/rcu/tree_exp.h:262
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81106eec)
Location: kernel/rcu/tree_exp.h:287
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111aac)
Location: kernel/rcu/tree_exp.h:286
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111b3ac)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127789)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool exp_funnel_lock(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81137600)
Location: kernel/rcu/tree_exp.h:280
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81137600-ffffffff811377fb: exp_funnel_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool exp_funnel_lock(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132c30)
Location: kernel/rcu/tree_exp.h:280
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81132c30-ffffffff81132e2b: exp_funnel_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool exp_funnel_lock(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132e90)
Location: kernel/rcu/tree_exp.h:280
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81132e90-ffffffff8113308b: exp_funnel_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool exp_funnel_lock(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81155110)
Location: kernel/rcu/tree_exp.h:280
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81155110-ffffffff8115532e: exp_funnel_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool exp_funnel_lock(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81178a30)
Location: kernel/rcu/tree_exp.h:280
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81178a30-ffffffff81178c78: exp_funnel_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool exp_funnel_lock(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b3070)
Location: kernel/rcu/tree_exp.h:282
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811b3070-ffffffff811b32c4: exp_funnel_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool exp_funnel_lock(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c51e0)
Location: kernel/rcu/tree_exp.h:283
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811c51e0-ffffffff811c5434: exp_funnel_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool exp_funnel_lock(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d5370)
Location: kernel/rcu/tree_exp.h:282
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811d5370-ffffffff811d55c4: exp_funnel_lock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018fcc0)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dbc30)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e8dd4)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000122338)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111fd69)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111769)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111dc59)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81128b8d)
Location: kernel/rcu/tree_exp.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
