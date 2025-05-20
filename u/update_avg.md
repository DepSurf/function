# Function: <code>update_avg</code>

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
In kernel/sched/core.c (ffffffff810aae98)
Location: kernel/sched/core.c:1647
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_wakeup
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
In kernel/sched/core.c (ffffffff810adadf)
Location: kernel/sched/core.c:1613
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_wakeup
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
In kernel/sched/core.c (ffffffff810b3be0)
Location: kernel/sched/core.c:1624
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_wakeup
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
In kernel/sched/core.c (ffffffff810afbbc)
Location: kernel/sched/core.c:1556
Inline: True
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
In kernel/sched/core.c (ffffffff810b6f98)
Location: kernel/sched/core.c:1575
Inline: True
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
In kernel/sched/core.c (ffffffff810beafc)
Location: kernel/sched/core.c:1571
Inline: True
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
In kernel/sched/core.c (ffffffff810c7d9c)
Location: kernel/sched/core.c:1569
Inline: True
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
In kernel/sched/core.c (ffffffff810cf0b3)
Location: kernel/sched/core.c:2009
Inline: True
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
In kernel/sched/core.c (ffffffff810d8e73)
Location: kernel/sched/core.c:2129
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e25a3)
Location: kernel/sched/sched.h:198
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff810ea004)
Location: kernel/sched/sched.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df953)
Location: kernel/sched/sched.h:201
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff810e7d64)
Location: kernel/sched/sched.h:201
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1750)
Location: kernel/sched/sched.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff810ebf97)
Location: kernel/sched/sched.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f787d)
Location: kernel/sched/sched.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff81103d08)
Location: kernel/sched/sched.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81113acd)
Location: kernel/sched/sched.h:221
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff8111fb94)
Location: kernel/sched/sched.h:221
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113ac9d)
Location: kernel/sched/sched.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff81145c9b)
Location: kernel/sched/sched.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115077c)
Location: kernel/sched/sched.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81156a64)
Location: kernel/sched/sched.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
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
In kernel/sched/core.c (ffffffff8115c644)
Location: kernel/sched/sched.h:211
Inline: True
Inline callers:
  - kernel/sched/core.c:ttwu_do_activate
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
In kernel/sched/core.c (ffff80001013912c)
Location: kernel/sched/core.c:2129
Inline: True
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
In kernel/sched/core.c (c03884ac)
Location: kernel/sched/core.c:2129
Inline: True
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
In kernel/sched/core.c (c000000000185814)
Location: kernel/sched/core.c:2129
Inline: True
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
In kernel/sched/core.c (ffffffe0000e8e82)
Location: kernel/sched/core.c:2129
Inline: True
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
In kernel/sched/core.c (ffffffff810d3343)
Location: kernel/sched/core.c:2129
Inline: True
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
In kernel/sched/core.c (ffffffff810c1973)
Location: kernel/sched/core.c:2129
Inline: True
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
In kernel/sched/core.c (ffffffff810d0a23)
Location: kernel/sched/core.c:2129
Inline: True
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
In kernel/sched/core.c (ffffffff810daac3)
Location: kernel/sched/core.c:2129
Inline: True
```
</details>
</li>
</ul>

## Differences
