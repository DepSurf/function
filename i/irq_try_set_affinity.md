# Function: <code>irq_try_set_affinity</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f7d7d)
Location: kernel/irq/manage.c:232
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff811034cd)
Location: kernel/irq/manage.c:232
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff8110bebb)
Location: kernel/irq/manage.c:259
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff811182bf)
Location: kernel/irq/manage.c:259
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff81123b6d)
Location: kernel/irq/manage.c:308
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff8111f9bd)
Location: kernel/irq/manage.c:308
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff8111fc79)
Location: kernel/irq/manage.c:308
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff81140119)
Location: kernel/irq/manage.c:301
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff81163a3d)
Location: kernel/irq/manage.c:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff8119770d)
Location: kernel/irq/manage.c:308
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff811a92dc)
Location: kernel/irq/manage.c:311
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff811b8e3c)
Location: kernel/irq/manage.c:313
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffff80001017aafc)
Location: kernel/irq/manage.c:259
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
In kernel/irq/manage.c (c03cbd88)
Location: kernel/irq/manage.c:259
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
In kernel/irq/manage.c (c0000000001d5068)
Location: kernel/irq/manage.c:259
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
In kernel/irq/manage.c (ffffffe0001148f2)
Location: kernel/irq/manage.c:259
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111089f)
Location: kernel/irq/manage.c:259
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff811015cf)
Location: kernel/irq/manage.c:259
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff8110e78f)
Location: kernel/irq/manage.c:259
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffff81119cbf)
Location: kernel/irq/manage.c:259
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
</details>
</li>
</ul>

## Differences
