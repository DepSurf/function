# Function: <code>sync_rcu_exp_select_cpus</code>

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
In kernel/rcu/tree.c (ffffffff810e5188)
Location: kernel/rcu/tree.c:3698
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
In kernel/rcu/tree.c (ffffffff810eba22)
Location: kernel/rcu/tree_exp.h:341
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus(struct rcu_state *rsp, smp_call_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f1c50)
Location: kernel/rcu/tree_exp.h:341
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff810f1c50-ffffffff810f205f: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus(struct rcu_state *rsp, smp_call_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2a40)
Location: kernel/rcu/tree_exp.h:359
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff810f2a40-ffffffff810f2e64: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus(struct rcu_state *rsp, smp_call_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc7f0)
Location: kernel/rcu/tree_exp.h:359
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff810fc7f0-ffffffff810fcc0c: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus(struct rcu_state *rsp, smp_call_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81105ac0)
Location: kernel/rcu/tree_exp.h:472
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81105ac0-ffffffff81105d8e: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus(smp_call_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811111e0)
Location: kernel/rcu/tree_exp.h:429
Inline: False
Direct callers:
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811111e0-ffffffff811114d7: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111abb0)
Location: kernel/rcu/tree_exp.h:421
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff8111abb0-ffffffff8111ae97: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81126fa0)
Location: kernel/rcu/tree_exp.h:419
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81126fa0-ffffffff81127287: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134c40)
Location: kernel/rcu/tree_exp.h:423
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81134c40-ffffffff81134e27: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811306e0)
Location: kernel/rcu/tree_exp.h:423
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811306e0-ffffffff811308c7: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81130ce0)
Location: kernel/rcu/tree_exp.h:423
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81130ce0-ffffffff81130fb9: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:424
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811528f0-ffffffff81152d61: sync_rcu_exp_select_cpus (STB_LOCAL)
ffffffff81caed8e-ffffffff81caeda2: sync_rcu_exp_select_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:529
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff8117adb0-ffffffff8117b228: sync_rcu_exp_select_cpus (STB_LOCAL)
ffffffff81e5f747-ffffffff81e5f75b: sync_rcu_exp_select_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:531
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811b5bf0-ffffffff811b6068: sync_rcu_exp_select_cpus (STB_LOCAL)
ffffffff8205a108-ffffffff8205a11c: sync_rcu_exp_select_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:532
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811c6b70-ffffffff811c6fe8: sync_rcu_exp_select_cpus (STB_LOCAL)
ffffffff820d8898-ffffffff820d88ac: sync_rcu_exp_select_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:531
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff811d6dd0-ffffffff811d7248: sync_rcu_exp_select_cpus (STB_LOCAL)
ffffffff821b3bd5-ffffffff821b3be9: sync_rcu_exp_select_cpus.cold (STB_LOCAL)
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
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018f840)
Location: kernel/rcu/tree_exp.h:419
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffff80001018f840-ffff80001018fc4c: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03db184)
Location: kernel/rcu/tree_exp.h:419
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
c03db184-c03db46c: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e7990)
Location: kernel/rcu/tree_exp.h:419
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
c0000000001e7990-c0000000001e7da8: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000121b7a)
Location: kernel/rcu/tree_exp.h:419
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffe000121b7a-ffffffe000121e26: sync_rcu_exp_select_cpus (STB_LOCAL)
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
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f580)
Location: kernel/rcu/tree_exp.h:419
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff8111f580-ffffffff8111f867: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110ff0)
Location: kernel/rcu/tree_exp.h:419
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81110ff0-ffffffff811112f4: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d470)
Location: kernel/rcu/tree_exp.h:419
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff8111d470-ffffffff8111d757: sync_rcu_exp_select_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81128390)
Location: kernel/rcu/tree_exp.h:419
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:wait_rcu_exp_gp
```
**Symbols:**

```
ffffffff81128390-ffffffff81128677: sync_rcu_exp_select_cpus (STB_LOCAL)
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
<code>rsp, func</code> ➡️ <code>func</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>smp_call_func_t func</code>
</li>
</ul>
</details>
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
