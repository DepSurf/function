# Function: <code>test_idle_cores</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5ca1)
Location: kernel/sched/fair.c:5630
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810bf871)
Location: kernel/sched/fair.c:5575
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810c7051)
Location: kernel/sched/fair.c:6021
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810cef63)
Location: kernel/sched/fair.c:6253
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810d84d3)
Location: kernel/sched/fair.c:5994
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810df769)
Location: kernel/sched/fair.c:5859
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810e9e09)
Location: kernel/sched/fair.c:5814
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea2c6)
Location: kernel/sched/fair.c:5986
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e7e86)
Location: kernel/sched/fair.c:6035
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff810ec0a6)
Location: kernel/sched/fair.c:6106
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff81104676)
Location: kernel/sched/fair.c:6157
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff81121b11)
Location: kernel/sched/fair.c:6214
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff8114d4d6)
Location: kernel/sched/fair.c:6589
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff8115b571)
Location: kernel/sched/fair.c:6842
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff81166f7f)
Location: kernel/sched/fair.c:7238
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffff800010149fc4)
Location: kernel/sched/fair.c:5814
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (c00000000019c028)
Location: kernel/sched/fair.c:5814
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810e3f69)
Location: kernel/sched/fair.c:5814
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810d3119)
Location: kernel/sched/fair.c:5814
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810e0339)
Location: kernel/sched/fair.c:5814
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
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
In kernel/sched/fair.c (ffffffff810ebec5)
Location: kernel/sched/fair.c:5814
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
</details>
</li>
</ul>

## Differences
