# Function: <code>rcu_cleanup_dead_rnp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e46b0)
Location: kernel/rcu/tree.c:2572
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810e46b0-ffffffff810e4710: rcu_cleanup_dead_rnp.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ecb74)
Location: kernel/rcu/tree.c:2678
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810eada0-ffffffff810eae00: rcu_cleanup_dead_rnp.part.17 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff810f3af4)
Location: kernel/rcu/tree.c:2682
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f2170-ffffffff810f21d0: rcu_cleanup_dead_rnp.part.19 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff810f49a0)
Location: kernel/rcu/tree.c:2679
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f34a0-ffffffff810f3500: rcu_cleanup_dead_rnp.part.21 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff810fe86d)
Location: kernel/rcu/tree.c:2674
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810fcec0-ffffffff810fcf20: rcu_cleanup_dead_rnp.part.22 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff811074f3)
Location: kernel/rcu/tree.c:2474
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81106020-ffffffff81106080: rcu_cleanup_dead_rnp.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111900)
Location: kernel/rcu/tree.c:2371
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81111900-ffffffff81111978: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111b150)
Location: kernel/rcu/tree.c:2024
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111b150-ffffffff8111b1c9: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127540)
Location: kernel/rcu/tree.c:2059
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81127540-ffffffff811275b9: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135910)
Location: kernel/rcu/tree.c:2305
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff81135910-ffffffff8113598f: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811310c0)
Location: kernel/rcu/tree.c:2424
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811310c0-ffffffff8113113f: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131810)
Location: kernel/rcu/tree.c:2437
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff81131810-ffffffff8113188f: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81153830)
Location: kernel/rcu/tree.c:2391
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff81153830-ffffffff811538af: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811790e0)
Location: kernel/rcu/tree.c:2462
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811790e0-ffffffff8117918e: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b0620)
Location: kernel/rcu/tree.c:2130
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811b0620-ffffffff811b06ce: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c25f0)
Location: kernel/rcu/tree.c:4186
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811c25f0-ffffffff811c269e: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d2b60)
Location: kernel/rcu/tree.c:4322
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811d2b60-ffffffff811d2c0e: rcu_cleanup_dead_rnp (STB_LOCAL)
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
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018c0f0)
Location: kernel/rcu/tree.c:2059
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffff80001018c0f0-ffff80001018c1e0: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dbf30)
Location: kernel/rcu/tree.c:2059
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
c03dbf30-c03dc040: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e91e0)
Location: kernel/rcu/tree.c:2059
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
c0000000001e91e0-c0000000001e9358: rcu_cleanup_dead_rnp (STB_LOCAL)
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2059
Inline: True
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
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111fb20)
Location: kernel/rcu/tree.c:2059
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111fb20-ffffffff8111fb99: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811115b0)
Location: kernel/rcu/tree.c:2059
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811115b0-ffffffff81111629: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111da10)
Location: kernel/rcu/tree.c:2059
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111da10-ffffffff8111da89: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rcu_cleanup_dead_rnp(struct rcu_node *rnp_leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81128e40)
Location: kernel/rcu/tree.c:2059
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81128e40-ffffffff81128ecb: rcu_cleanup_dead_rnp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
