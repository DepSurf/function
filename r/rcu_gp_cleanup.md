# Function: <code>rcu_gp_cleanup</code>

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
In kernel/rcu/tree.c (ffffffff810e6d72)
Location: kernel/rcu/tree.c:1987
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff810ecfae)
Location: kernel/rcu/tree.c:2089
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff810f3f29)
Location: kernel/rcu/tree.c:2093
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff810f4d89)
Location: kernel/rcu/tree.c:2117
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff810fec32)
Location: kernel/rcu/tree.c:2190
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff81107804)
Location: kernel/rcu/tree.c:2052
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff8111299e)
Location: kernel/rcu/tree.c:2001
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff8111c2d9)
Location: kernel/rcu/tree.c:1655
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff81128a49)
Location: kernel/rcu/tree.c:1684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_gp_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135f70)
Location: kernel/rcu/tree.c:1921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81135f70-ffffffff81136302: rcu_gp_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_gp_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131740)
Location: kernel/rcu/tree.c:2038
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81131740-ffffffff81131ac9: rcu_gp_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_gp_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131d60)
Location: kernel/rcu/tree.c:2051
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81131d60-ffffffff811320ea: rcu_gp_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_gp_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2005
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81153e10-ffffffff81154278: rcu_gp_cleanup (STB_LOCAL)
ffffffff81caf048-ffffffff81caf05d: rcu_gp_cleanup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_gp_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2046
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8117cbd0-ffffffff8117d038: rcu_gp_cleanup (STB_LOCAL)
ffffffff81e5fc13-ffffffff81e5fc37: rcu_gp_cleanup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_gp_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b6ee0)
Location: kernel/rcu/tree.c:1711
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811b6ee0-ffffffff811b73a8: rcu_gp_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_gp_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c7910)
Location: kernel/rcu/tree.c:1664
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811c7910-ffffffff811c7def: rcu_gp_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_gp_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811db980)
Location: kernel/rcu/tree.c:1718
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811db980-ffffffff811dbead: rcu_gp_cleanup (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff80001018e9a8)
Location: kernel/rcu/tree.c:1684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (c03dd134)
Location: kernel/rcu/tree.c:1684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (c0000000001ea500)
Location: kernel/rcu/tree.c:1684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffe0001238e4)
Location: kernel/rcu/tree.c:1684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff81121029)
Location: kernel/rcu/tree.c:1684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff81113601)
Location: kernel/rcu/tree.c:1684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff8111ef19)
Location: kernel/rcu/tree.c:1684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff8112a0ae)
Location: kernel/rcu/tree.c:1684
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
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
