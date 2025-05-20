# Function: <code>irqd_has_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:186
Inline: True
```
```
In kernel/irq/chip.c (ffffffff810ddb45)
Location: kernel/irq/internals.h:186
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:195
Inline: True
```
```
In kernel/irq/chip.c (ffffffff810e3395)
Location: kernel/irq/internals.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:195
Inline: True
```
```
In kernel/irq/chip.c (ffffffff810e9c55)
Location: kernel/irq/internals.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:225
Inline: True
```
```
In kernel/irq/chip.c (ffffffff810e9165)
Location: kernel/irq/internals.h:225
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:228
Inline: True
```
```
In kernel/irq/chip.c (ffffffff810f15c5)
Location: kernel/irq/internals.h:228
Inline: True
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:228
Inline: True
```
```
In kernel/irq/chip.c (ffffffff810f9a05)
Location: kernel/irq/internals.h:228
Inline: True
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:228
Inline: True
```
```
In kernel/irq/chip.c (ffffffff811051b5)
Location: kernel/irq/internals.h:228
Inline: True
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:235
Inline: True
```
```
In kernel/irq/chip.c (ffffffff8110e495)
Location: kernel/irq/internals.h:235
Inline: True
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffff8111a755)
Location: kernel/irq/internals.h:233
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffff81126f4b)
Location: kernel/irq/internals.h:233
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffff81122b4b)
Location: kernel/irq/internals.h:233
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffff81122c8b)
Location: kernel/irq/internals.h:233
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffff8114325b)
Location: kernel/irq/internals.h:233
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:235
Inline: True
```
```
In kernel/irq/chip.c (ffffffff8116715b)
Location: kernel/irq/internals.h:235
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:237
Inline: True
```
```
In kernel/irq/chip.c (ffffffff8119b4ab)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:242
Inline: True
```
```
In kernel/irq/chip.c (ffffffff811ad2eb)
Location: kernel/irq/internals.h:242
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:242
Inline: True
```
```
In kernel/irq/chip.c (ffffffff811bceeb)
Location: kernel/irq/internals.h:242
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffff80001017de60)
Location: kernel/irq/internals.h:233
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (c03ce658)
Location: kernel/irq/internals.h:233
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (c0000000001d87c0)
Location: kernel/irq/internals.h:233
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffe0001170ec)
Location: kernel/irq/internals.h:233
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffff81112d35)
Location: kernel/irq/internals.h:233
Inline: True
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffff81103a55)
Location: kernel/irq/internals.h:233
Inline: True
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffff81110c25)
Location: kernel/irq/internals.h:233
Inline: True
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
In kernel/irq/manage.c (0)
Location: kernel/irq/internals.h:233
Inline: True
```
```
In kernel/irq/chip.c (ffffffff8111c285)
Location: kernel/irq/internals.h:233
Inline: True
```
</details>
</li>
</ul>

## Differences
