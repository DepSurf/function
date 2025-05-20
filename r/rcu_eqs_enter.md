# Function: <code>rcu_eqs_enter</code>

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
In kernel/rcu/tree.c (ffffffff810e638a)
Location: kernel/rcu/tree.c:683
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff810ed2ca)
Location: kernel/rcu/tree.c:718
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff810f424a)
Location: kernel/rcu/tree.c:719
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff810f518e)
Location: kernel/rcu/tree.c:819
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff810ffa86)
Location: kernel/rcu/tree.c:816
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff81107d95)
Location: kernel/rcu/tree.c:719
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff811132c5)
Location: kernel/rcu/tree.c:596
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff8111ce95)
Location: kernel/rcu/tree.c:558
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff81129375)
Location: kernel/rcu/tree.c:565
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff81bbf910)
Location: kernel/rcu/tree.c:614
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_enter
```
**Symbols:**

```
ffffffff81bbf910-ffffffff81bbf981: rcu_eqs_enter.constprop.0 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff81c386f0)
Location: kernel/rcu/tree.c:628
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_enter
```
**Symbols:**

```
ffffffff81c386f0-ffffffff81c38761: rcu_eqs_enter.constprop.0 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff81c2ab00)
Location: kernel/rcu/tree.c:634
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_enter
```
**Symbols:**

```
ffffffff81c2ab00-ffffffff81c2ab66: rcu_eqs_enter.constprop.0 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff81d490a0)
Location: kernel/rcu/tree.c:609
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_enter
```
**Symbols:**

```
ffffffff81d490a0-ffffffff81d49106: rcu_eqs_enter.constprop.0 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff81f18490)
Location: kernel/rcu/tree.c:620
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_idle_enter
```
**Symbols:**

```
ffffffff81f18490-ffffffff81f1854f: rcu_eqs_enter.constprop.0 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff8000101909a0)
Location: kernel/rcu/tree.c:565
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (c03de4f8)
Location: kernel/rcu/tree.c:565
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (c0000000001ebcd0)
Location: kernel/rcu/tree.c:565
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffe000123f36)
Location: kernel/rcu/tree.c:565
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff81121955)
Location: kernel/rcu/tree.c:565
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff81110830)
Location: kernel/rcu/tree.c:565
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_user_enter
  - kernel/rcu/tree.c:rcu_idle_enter
```
**Symbols:**

```
ffffffff81110830-ffffffff811108f7: rcu_eqs_enter.constprop.0 (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff8111f845)
Location: kernel/rcu/tree.c:565
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff8112b995)
Location: kernel/rcu/tree.c:565
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_idle_enter
```
</details>
</li>
</ul>

## Differences
