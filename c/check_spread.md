# Function: <code>check_spread</code>

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
In kernel/sched/fair.c (ffffffff810b7f8f)
Location: kernel/sched/fair.c:2967
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:put_prev_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bc847)
Location: kernel/sched/fair.c:3248
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810b5360-ffffffff810b5375: check_spread.isra.35.part.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1d65)
Location: kernel/sched/fair.c:3463
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810bb830-ffffffff810bb845: check_spread.isra.40.part.41 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810bc673)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810c44e5)
Location: kernel/sched/fair.c:3907
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cbee3)
Location: kernel/sched/fair.c:4078
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810c56a0-ffffffff810c56b5: check_spread.isra.73.part.74 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d45f5)
Location: kernel/sched/fair.c:3769
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810ce2e0-ffffffff810ce2f5: check_spread.isra.77.part.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dca83)
Location: kernel/sched/fair.c:3864
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810d6840-ffffffff810d6855: check_spread.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6eb3)
Location: kernel/sched/fair.c:3863
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e0ec0-ffffffff810e0ed5: check_spread.isra.0.part.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810f0fa7)
Location: kernel/sched/fair.c:4082
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810efc27)
Location: kernel/sched/fair.c:4116
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810f1657)
Location: kernel/sched/fair.c:4179
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff8110b173)
Location: kernel/sched/fair.c:4191
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff8111b930)
Location: kernel/sched/fair.c:4241
Inline: True
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff8111b930-ffffffff8111b977: check_spread.isra.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff81143480)
Location: kernel/sched/fair.c:4642
Inline: True
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff81143480-ffffffff811434c7: check_spread.isra.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff8115ef25)
Location: kernel/sched/fair.c:4695
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/sched/fair.c (ffff800010146db4)
Location: kernel/sched/fair.c:3863
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffff800010140d78-ffff800010140db8: check_spread.isra.0.part.0 (STB_LOCAL)
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
In kernel/sched/fair.c (c0394f84)
Location: kernel/sched/fair.c:3863
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (c000000000198350)
Location: kernel/sched/fair.c:3863
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
c000000000190e50-c000000000190e70: check_spread.isra.0.part.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffe0000f2620)
Location: kernel/sched/fair.c:3863
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
</details>
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
In kernel/sched/fair.c (ffffffff810e1063)
Location: kernel/sched/fair.c:3863
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810db070-ffffffff810db085: check_spread.isra.0.part.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810d0143)
Location: kernel/sched/fair.c:3863
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810ca080-ffffffff810ca095: check_spread.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dd3e3)
Location: kernel/sched/fair.c:3863
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810d73f0-ffffffff810d7405: check_spread.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9163)
Location: kernel/sched/fair.c:3863
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e2da0-ffffffff810e2db5: check_spread.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
