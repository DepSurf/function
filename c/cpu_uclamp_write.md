# Function: <code>cpu_uclamp_write</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d5510)
Location: kernel/sched/core.c:7278
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff810d5510-ffffffff810d5695: cpu_uclamp_write.isra.0 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810dfad0)
Location: kernel/sched/core.c:7512
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff810dfad0-ffffffff810dfc61: cpu_uclamp_write.constprop.0 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810dcdc0)
Location: kernel/sched/core.c:8477
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff810dcdc0-ffffffff810dcf56: cpu_uclamp_write.constprop.0 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810de990)
Location: kernel/sched/core.c:8853
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff810de990-ffffffff810deb2a: cpu_uclamp_write.constprop.0 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810f3830)
Location: kernel/sched/core.c:10091
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff810f3830-ffffffff810f3a5b: cpu_uclamp_write.constprop.0 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff8110f890)
Location: kernel/sched/core.c:10414
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff8110f890-ffffffff8110fac8: cpu_uclamp_write.constprop.0 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff81136710)
Location: kernel/sched/core.c:10560
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff81136710-ffffffff81136948: cpu_uclamp_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81145750)
Location: kernel/sched/core.c:10720
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff81145750-ffffffff81145988: cpu_uclamp_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81150c70)
Location: kernel/sched/core.c:10680
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff81150c70-ffffffff81150eab: cpu_uclamp_write.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffff800010136008)
Location: kernel/sched/core.c:7278
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffff800010136008-ffff80001013618c: cpu_uclamp_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c0384f50)
Location: kernel/sched/core.c:7278
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
c0384f50-c038512c: cpu_uclamp_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c000000000180fe0)
Location: kernel/sched/core.c:7278
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
c000000000180fe0-c0000000001812f0: cpu_uclamp_write.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf810)
Location: kernel/sched/core.c:7278
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff810cf810-ffffffff810cf995: cpu_uclamp_write.isra.0 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810be0d0)
Location: kernel/sched/core.c:7278
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff810be0d0-ffffffff810be255: cpu_uclamp_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7370)
Location: kernel/sched/core.c:7278
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_uclamp_max_write
  - kernel/sched/core.c:cpu_uclamp_min_write
```
**Symbols:**

```
ffffffff810d7370-ffffffff810d74ff: cpu_uclamp_write.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
