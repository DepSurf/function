# Function: <code>irq_state_set_masked</code>

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
In kernel/irq/chip.c (ffffffff810ddc98)
Location: kernel/irq/chip.c:184
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:__irq_do_set_handler
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
In kernel/irq/chip.c (ffffffff810e3fd4)
Location: kernel/irq/chip.c:184
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown
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
In kernel/irq/chip.c (ffffffff810ea52a)
Location: kernel/irq/chip.c:183
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown
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
In kernel/irq/chip.c (ffffffff810e9b9f)
Location: kernel/irq/internals.h:235
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff810eebc2)
Location: kernel/irq/internals.h:235
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff810f20e7)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff810f766e)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff810fa58b)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff810ff9ce)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff81105d4b)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff8110b1ae)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff8110f205)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
```
```
In kernel/irq/pm.c (ffffffff8111488d)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff8111b4ce)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
```
```
In kernel/irq/pm.c (ffffffff811209ed)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff8112766e)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff8112cfad)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff8112326e)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff81128847)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irq
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
In kernel/irq/chip.c (ffffffff811235ce)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff81128b43)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff81143b9e)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff81149123)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff8116804e)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff8116dca9)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff8119c50e)
Location: kernel/irq/internals.h:247
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff811a2ee9)
Location: kernel/irq/internals.h:247
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff811ae382)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
```
In kernel/irq/pm.c (ffffffff811b4de9)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff811bdf82)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
```
In kernel/irq/pm.c (ffffffff811c4c69)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffff80001017ec80)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
```
```
In kernel/irq/pm.c (ffff8000101867ac)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (c03cf718)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
```
```
In kernel/irq/pm.c (c03d55d8)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (c0000000001d9f2c)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
```
```
In kernel/irq/pm.c (c0000000001e1174)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffe000117a02)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
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
In kernel/irq/chip.c (ffffffff81113aae)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
```
```
In kernel/irq/pm.c (ffffffff81118fcd)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff811047be)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
```
```
In kernel/irq/pm.c (ffffffff8110a03d)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff8111199e)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
```
```
In kernel/irq/pm.c (ffffffff81116ebd)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/chip.c (ffffffff8111cf5e)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
```
```
In kernel/irq/pm.c (ffffffff8112254d)
Location: kernel/irq/internals.h:243
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
```
</details>
</li>
</ul>

## Differences
