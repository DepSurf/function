# Function: <code>rcu_exp_wait_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ebc97)
Location: kernel/rcu/tree_exp.h:490
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_exp_wait_wake(struct rcu_state *rsp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f22a0)
Location: kernel/rcu/tree_exp.h:498
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff810f22a0-ffffffff810f2843: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_exp_wait_wake(struct rcu_state *rsp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2e70)
Location: kernel/rcu/tree_exp.h:514
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff810f2e70-ffffffff810f344b: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_exp_wait_wake(struct rcu_state *rsp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fd9b0)
Location: kernel/rcu/tree_exp.h:514
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff810fd9b0-ffffffff810fdf77: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void rcu_exp_wait_wake(struct rcu_state *rsp, long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:592
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81106720-ffffffff81106964: rcu_exp_wait_wake (STB_LOCAL)
ffffffff81108d94-ffffffff8110901d: rcu_exp_wait_wake.cold.77 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:550
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81111620-ffffffff8111187b: rcu_exp_wait_wake (STB_LOCAL)
ffffffff811145d5-ffffffff81114864: rcu_exp_wait_wake.cold.74 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111aea0)
Location: kernel/rcu/tree_exp.h:539
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff8111aea0-ffffffff8111afb5: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127290)
Location: kernel/rcu/tree_exp.h:538
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81127290-ffffffff811273a3: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811378c0)
Location: kernel/rcu/tree_exp.h:579
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811378c0-ffffffff811379d3: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132f00)
Location: kernel/rcu/tree_exp.h:579
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81132f00-ffffffff81133013: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132470)
Location: kernel/rcu/tree_exp.h:580
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81132470-ffffffff81132583: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81154850)
Location: kernel/rcu/tree_exp.h:581
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81154850-ffffffff811549a4: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117ec00)
Location: kernel/rcu/tree_exp.h:681
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff8117ec00-ffffffff8117ed65: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b4690)
Location: kernel/rcu/tree_exp.h:686
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811b4690-ffffffff811b4801: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c87a0)
Location: kernel/rcu/tree_exp.h:689
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811c87a0-ffffffff811c8911: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811da810)
Location: kernel/rcu/tree_exp.h:692
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811da810-ffffffff811da981: rcu_exp_wait_wake (STB_LOCAL)
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
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018d5e8)
Location: kernel/rcu/tree_exp.h:538
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffff80001018d5e8-ffff80001018d74c: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03db46c)
Location: kernel/rcu/tree_exp.h:538
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
c03db46c-c03db5b0: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e7db0)
Location: kernel/rcu/tree_exp.h:538
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
c0000000001e7db0-c0000000001e7f78: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000121f90)
Location: kernel/rcu/tree_exp.h:538
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffe000121f90-ffffffe0001220d8: rcu_exp_wait_wake (STB_LOCAL)
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
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f870)
Location: kernel/rcu/tree_exp.h:538
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff8111f870-ffffffff8111f983: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111300)
Location: kernel/rcu/tree_exp.h:538
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81111300-ffffffff8111141b: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d760)
Location: kernel/rcu/tree_exp.h:538
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff8111d760-ffffffff8111d873: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81128680)
Location: kernel/rcu/tree_exp.h:538
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81128680-ffffffff81128791: rcu_exp_wait_wake (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>rsp, s</code> ➡️ <code>s</code>
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
