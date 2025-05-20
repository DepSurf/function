# Function: <code>rcu_report_qs_rdp</code>

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
In kernel/rcu/tree.c (ffffffff810e72be)
Location: kernel/rcu/tree.c:2350
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff810ed527)
Location: kernel/rcu/tree.c:2457
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff810f449a)
Location: kernel/rcu/tree.c:2461
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff810f5659)
Location: kernel/rcu/tree.c:2490
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff810ff43e)
Location: kernel/rcu/tree.c:2564
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff81106a60)
Location: kernel/rcu/tree.c:2364
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff81112d19)
Location: kernel/rcu/tree.c:2261
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff8111c672)
Location: kernel/rcu/tree.c:1915
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (ffffffff81128dda)
Location: kernel/rcu/tree.c:1947
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135bf0)
Location: kernel/rcu/tree.c:2191
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81135bf0-ffffffff81135cb8: rcu_report_qs_rdp.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_report_qs_rdp(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131320)
Location: kernel/rcu/tree.c:2311
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81131320-ffffffff811313f1: rcu_report_qs_rdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811335ef)
Location: kernel/rcu/tree.c:2324
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811559e7)
Location: kernel/rcu/tree.c:2278
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117e3ea)
Location: kernel/rcu/tree.c:2334
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b9271)
Location: kernel/rcu/tree.c:2002
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811cb589)
Location: kernel/rcu/tree.c:1955
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_report_qs_rdp(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2009
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff811de8f0-ffffffff811dea6c: rcu_report_qs_rdp (STB_LOCAL)
ffffffff821b409d-ffffffff821b40b2: rcu_report_qs_rdp.cold (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff8000101901a4)
Location: kernel/rcu/tree.c:1947
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (c03ddd6c)
Location: kernel/rcu/tree.c:1947
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (c0000000001eb140)
Location: kernel/rcu/tree.c:1947
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (ffffffe000122dae)
Location: kernel/rcu/tree.c:1947
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (ffffffff811213ba)
Location: kernel/rcu/tree.c:1947
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (ffffffff81112b53)
Location: kernel/rcu/tree.c:1947
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (ffffffff8111f2aa)
Location: kernel/rcu/tree.c:1947
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (ffffffff8112b38f)
Location: kernel/rcu/tree.c:1947
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
