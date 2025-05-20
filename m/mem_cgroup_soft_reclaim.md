# Function: <code>mem_cgroup_soft_reclaim</code>

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
In mm/memcontrol.c (ffffffff811ffcd5)
Location: mm/memcontrol.c:1512
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff81223a33)
Location: mm/memcontrol.c:1377
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff81235f28)
Location: mm/memcontrol.c:1348
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff812419a2)
Location: mm/memcontrol.c:1340
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff812616f2)
Location: mm/memcontrol.c:1354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff81285715)
Location: mm/memcontrol.c:1311
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff8129a615)
Location: mm/memcontrol.c:1492
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff812b58b6)
Location: mm/memcontrol.c:1693
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff812c7566)
Location: mm/memcontrol.c:1709
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff812fad50)
Location: mm/memcontrol.c:1576
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812fad50-ffffffff812faeb4: mem_cgroup_soft_reclaim.constprop.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff81307df0)
Location: mm/memcontrol.c:1765
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81307df0-ffffffff81307f61: mem_cgroup_soft_reclaim.constprop.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff8130fa02)
Location: mm/memcontrol.c:1588
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff8135ac8f)
Location: mm/memcontrol.c:1640
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff813d4394)
Location: mm/memcontrol.c:1657
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff81459d84)
Location: mm/memcontrol.c:1717
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff8148fa38)
Location: mm/memcontrol.c:1751
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bf268)
Location: mm/memcontrol.c:1823
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffff80001036a38c)
Location: mm/memcontrol.c:1709
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (c055b840)
Location: mm/memcontrol.c:1709
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (c0000000004593bc)
Location: mm/memcontrol.c:1709
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffe000247c14)
Location: mm/memcontrol.c:1709
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff812bfb46)
Location: mm/memcontrol.c:1709
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff812b0c26)
Location: mm/memcontrol.c:1709
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff812bd956)
Location: mm/memcontrol.c:1709
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
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
In mm/memcontrol.c (ffffffff812ce296)
Location: mm/memcontrol.c:1709
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
</details>
</li>
</ul>

## Differences
