# Function: <code>queue_pages_pmd</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8123728b)
Location: mm/mempolicy.c:431
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff8125a7c5)
Location: mm/mempolicy.c:431
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff8126e645)
Location: mm/mempolicy.c:438
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff81289c85)
Location: mm/mempolicy.c:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff812997f5)
Location: mm/mempolicy.c:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff812ceaa0)
Location: mm/mempolicy.c:469
Inline: True
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff812ceaa0-ffffffff812cec4a: queue_pages_pmd.constprop.0 (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff812da3e0)
Location: mm/mempolicy.c:469
Inline: True
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff812da3e0-ffffffff812da58a: queue_pages_pmd.constprop.0 (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff812e1c40)
Location: mm/mempolicy.c:469
Inline: True
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff812e1c40-ffffffff812e1df3: queue_pages_pmd.constprop.0 (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff81328d20)
Location: mm/mempolicy.c:450
Inline: True
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff81328d20-ffffffff81328ed2: queue_pages_pmd.constprop.0 (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff81397f70)
Location: mm/mempolicy.c:453
Inline: True
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff81397f70-ffffffff81398138: queue_pages_pmd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81417cf0)
Location: mm/mempolicy.c:454
Inline: True
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff81417cf0-ffffffff81417ea2: queue_pages_pmd.constprop.0 (STB_LOCAL)
```
</details>
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
In mm/mempolicy.c (ffff800010338590)
Location: mm/mempolicy.c:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000413118)
Location: mm/mempolicy.c:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/mempolicy.c (ffffffff81291dd5)
Location: mm/mempolicy.c:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff81283a4c)
Location: mm/mempolicy.c:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff8128fbe5)
Location: mm/mempolicy.c:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff8129f076)
Location: mm/mempolicy.c:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
</details>
</li>
</ul>

## Differences
