# Function: <code>rcu_gp_init</code>

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
In kernel/rcu/tree.c (ffffffff810e6805)
Location: kernel/rcu/tree.c:1810
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
In kernel/rcu/tree.c (ffffffff810eca4e)
Location: kernel/rcu/tree.c:1917
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
In kernel/rcu/tree.c (ffffffff810f39ce)
Location: kernel/rcu/tree.c:1921
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
In kernel/rcu/tree.c (ffffffff810f4859)
Location: kernel/rcu/tree.c:1954
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
In kernel/rcu/tree.c (ffffffff810fe724)
Location: kernel/rcu/tree.c:2027
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
In kernel/rcu/tree.c (ffffffff811073bb)
Location: kernel/rcu/tree.c:1889
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
In kernel/rcu/tree.c (ffffffff81112416)
Location: kernel/rcu/tree.c:1761
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
In kernel/rcu/tree.c (ffffffff8111bced)
Location: kernel/rcu/tree.c:1415
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
In kernel/rcu/tree.c (ffffffff8112845d)
Location: kernel/rcu/tree.c:1444
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
bool rcu_gp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811370a0)
Location: kernel/rcu/tree.c:1672
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811370a0-ffffffff81137508: rcu_gp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rcu_gp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132680)
Location: kernel/rcu/tree.c:1775
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81132680-ffffffff81132b42: rcu_gp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rcu_gp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133a10)
Location: kernel/rcu/tree.c:1783
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81133a10-ffffffff81133ed2: rcu_gp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool rcu_gp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1737
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81155da0-ffffffff81156384: rcu_gp_init (STB_LOCAL)
ffffffff81caf4f9-ffffffff81caf59c: rcu_gp_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool rcu_gp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1781
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8117d2a0-ffffffff8117d8d8: rcu_gp_init (STB_LOCAL)
ffffffff81e5fc67-ffffffff81e5fd3b: rcu_gp_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool rcu_gp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1433
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811b7e20-ffffffff811b84dc: rcu_gp_init (STB_LOCAL)
ffffffff8205a1fe-ffffffff8205a2ae: rcu_gp_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool rcu_gp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1386
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811c9d50-ffffffff811ca40c: rcu_gp_init (STB_LOCAL)
ffffffff820d8a17-ffffffff820d8ac7: rcu_gp_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool rcu_gp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1428
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811dbf70-ffffffff811dc636: rcu_gp_init (STB_LOCAL)
ffffffff821b3e89-ffffffff821b3f39: rcu_gp_init.cold (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff80001018e2ac)
Location: kernel/rcu/tree.c:1444
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rcu_gp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc908)
Location: kernel/rcu/tree.c:1444
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
c03dc908-c03dce14: rcu_gp_init (STB_LOCAL)
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
In kernel/rcu/tree.c (c0000000001e9f28)
Location: kernel/rcu/tree.c:1444
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
In kernel/rcu/tree.c (ffffffe0001233b8)
Location: kernel/rcu/tree.c:1444
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
In kernel/rcu/tree.c (ffffffff81120a3d)
Location: kernel/rcu/tree.c:1444
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
In kernel/rcu/tree.c (ffffffff81113022)
Location: kernel/rcu/tree.c:1444
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
In kernel/rcu/tree.c (ffffffff8111e92d)
Location: kernel/rcu/tree.c:1444
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
In kernel/rcu/tree.c (ffffffff81129a7d)
Location: kernel/rcu/tree.c:1444
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
<b>Arch</b>
<ul>
</ul>
