# Function: <code>irqd_set_move_pending</code>

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
In kernel/irq/manage.c (ffffffff810dc0ca)
Location: kernel/irq/internals.h:166
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff810e17da)
Location: kernel/irq/internals.h:175
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff810e8136)
Location: kernel/irq/internals.h:175
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff810e7590)
Location: kernel/irq/internals.h:195
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff810ef904)
Location: kernel/irq/internals.h:198
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f7d05)
Location: kernel/irq/internals.h:198
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff810ff3dd)
Location: kernel/irq/internals.h:198
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81103455)
Location: kernel/irq/internals.h:198
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff8110abbd)
Location: kernel/irq/internals.h:198
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110be41)
Location: kernel/irq/internals.h:205
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff81114273)
Location: kernel/irq/internals.h:205
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118241)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff811203e3)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In kernel/irq/manage.c (ffffffff81123a79)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff8112c91f)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In kernel/irq/manage.c (ffffffff8111f8c9)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff8112834f)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In kernel/irq/manage.c (ffffffff8111fb89)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff81128611)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In kernel/irq/manage.c (ffffffff81140029)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff81148be1)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In kernel/irq/manage.c (ffffffff81163929)
Location: kernel/irq/internals.h:205
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff8116d71d)
Location: kernel/irq/internals.h:205
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In kernel/irq/manage.c (ffffffff811975f9)
Location: kernel/irq/internals.h:207
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff811a28bd)
Location: kernel/irq/internals.h:207
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In kernel/irq/manage.c (ffffffff811a919d)
Location: kernel/irq/internals.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff811b47bd)
Location: kernel/irq/internals.h:212
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b8cfd)
Location: kernel/irq/internals.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff811c463d)
Location: kernel/irq/internals.h:212
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In kernel/irq/manage.c (ffff80001017aa9c)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (c03cbd28)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (c0000000001d4f9c)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffe000114888)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81110821)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff811189c3)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81101551)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff81109a33)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110e711)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff811168b3)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119c41)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/migration.c (ffffffff81121ef3)
Location: kernel/irq/internals.h:203
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
</details>
</li>
</ul>

## Differences
