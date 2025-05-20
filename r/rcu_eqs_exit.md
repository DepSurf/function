# Function: <code>rcu_eqs_exit</code>

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
In kernel/rcu/tree.c (ffffffff810e649a)
Location: kernel/rcu/tree.c:812
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff810ed37a)
Location: kernel/rcu/tree.c:857
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff810f42fa)
Location: kernel/rcu/tree.c:858
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff810f51fb)
Location: kernel/rcu/tree.c:946
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff810ffb5b)
Location: kernel/rcu/tree.c:957
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff81107f0d)
Location: kernel/rcu/tree.c:877
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff8111342d)
Location: kernel/rcu/tree.c:762
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff8111d06d)
Location: kernel/rcu/tree.c:723
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff8112956d)
Location: kernel/rcu/tree.c:731
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff81bbf8a0)
Location: kernel/rcu/tree.c:828
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff81bbf8a0-ffffffff81bbf90c: rcu_eqs_exit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c38680)
Location: kernel/rcu/tree.c:894
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff81c38680-ffffffff81c386ec: rcu_eqs_exit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c2aa90)
Location: kernel/rcu/tree.c:899
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff81c2aa90-ffffffff81c2aafc: rcu_eqs_exit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81d49030)
Location: kernel/rcu/tree.c:852
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff81d49030-ffffffff81d4909c: rcu_eqs_exit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81f18410)
Location: kernel/rcu/tree.c:859
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff81f18410-ffffffff81f18488: rcu_eqs_exit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/rcu/tree.c (ffff800010190b10)
Location: kernel/rcu/tree.c:731
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (c03de6e0)
Location: kernel/rcu/tree.c:731
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (c0000000001ebf70)
Location: kernel/rcu/tree.c:731
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffe00012409e)
Location: kernel/rcu/tree.c:731
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff81121b4d)
Location: kernel/rcu/tree.c:731
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811107b0)
Location: kernel/rcu/tree.c:731
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_user_exit
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff811107b0-ffffffff8111082e: rcu_eqs_exit.constprop.0 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff8111fa3d)
Location: kernel/rcu/tree.c:731
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
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
In kernel/rcu/tree.c (ffffffff8112bbad)
Location: kernel/rcu/tree.c:731
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_exit
```
</details>
</li>
</ul>

## Differences
