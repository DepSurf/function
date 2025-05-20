# Function: <code>rcu_gp_fqs_loop</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111275f)
Location: kernel/rcu/tree.c:1936
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
In kernel/rcu/tree.c (ffffffff8111c056)
Location: kernel/rcu/tree.c:1590
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
In kernel/rcu/tree.c (ffffffff811287c6)
Location: kernel/rcu/tree.c:1619
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
void rcu_gp_fqs_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135260)
Location: kernel/rcu/tree.c:1852
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81135260-ffffffff81135513: rcu_gp_fqs_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_gp_fqs_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81130a60)
Location: kernel/rcu/tree.c:1969
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81130a60-ffffffff81130cdf: rcu_gp_fqs_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_gp_fqs_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131120)
Location: kernel/rcu/tree.c:1977
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81131120-ffffffff811313a0: rcu_gp_fqs_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_gp_fqs_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1931
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81152f60-ffffffff8115327d: rcu_gp_fqs_loop (STB_LOCAL)
ffffffff81caeddf-ffffffff81caee08: rcu_gp_fqs_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_gp_fqs_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1972
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8117b650-ffffffff8117ba2d: rcu_gp_fqs_loop (STB_LOCAL)
ffffffff81e5f76f-ffffffff81e5f797: rcu_gp_fqs_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_gp_fqs_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b21a0)
Location: kernel/rcu/tree.c:1625
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811b21a0-ffffffff811b265f: rcu_gp_fqs_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_gp_fqs_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c3fa0)
Location: kernel/rcu/tree.c:1578
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811c3fa0-ffffffff811c447e: rcu_gp_fqs_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_gp_fqs_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811dcac0)
Location: kernel/rcu/tree.c:1632
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811dcac0-ffffffff811dd033: rcu_gp_fqs_loop (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff80001018e58c)
Location: kernel/rcu/tree.c:1619
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
In kernel/rcu/tree.c (c03dcf24)
Location: kernel/rcu/tree.c:1619
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
In kernel/rcu/tree.c (c0000000001ea3d0)
Location: kernel/rcu/tree.c:1619
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
In kernel/rcu/tree.c (ffffffe0001237e8)
Location: kernel/rcu/tree.c:1619
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
In kernel/rcu/tree.c (ffffffff81120da6)
Location: kernel/rcu/tree.c:1619
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
In kernel/rcu/tree.c (ffffffff81113384)
Location: kernel/rcu/tree.c:1619
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
In kernel/rcu/tree.c (ffffffff8111ec96)
Location: kernel/rcu/tree.c:1619
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
In kernel/rcu/tree.c (ffffffff81129e11)
Location: kernel/rcu/tree.c:1619
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
