# Function: <code>irq_state_set_disabled</code>

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
In kernel/irq/chip.c (ffffffff810de143)
Location: kernel/irq/chip.c:174
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff810e3fde)
Location: kernel/irq/chip.c:174
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
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
In kernel/irq/chip.c (ffffffff810ea534)
Location: kernel/irq/chip.c:173
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
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
In kernel/irq/chip.c (ffffffff810e9ba9)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff810eebb8)
Location: kernel/irq/internals.h:230
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
In kernel/irq/chip.c (ffffffff810f20f8)
Location: kernel/irq/internals.h:233
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff810f765d)
Location: kernel/irq/internals.h:233
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
In kernel/irq/chip.c (ffffffff810fa59c)
Location: kernel/irq/internals.h:233
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff810ff9c8)
Location: kernel/irq/internals.h:233
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
In kernel/irq/chip.c (ffffffff81105d5c)
Location: kernel/irq/internals.h:233
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff8110b1a8)
Location: kernel/irq/internals.h:233
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
In kernel/irq/chip.c (ffffffff8110f214)
Location: kernel/irq/internals.h:240
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (ffffffff81114882)
Location: kernel/irq/internals.h:240
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
In kernel/irq/chip.c (ffffffff8111b4dd)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (ffffffff811209e2)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (ffffffff8112767d)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff8112cfa2)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (ffffffff8112327d)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff81128841)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (ffffffff811235dd)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff81128b38)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (ffffffff81143bad)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff81149118)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (ffffffff8116805c)
Location: kernel/irq/internals.h:240
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff8116dca3)
Location: kernel/irq/internals.h:240
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
In kernel/irq/chip.c (ffffffff8119c51c)
Location: kernel/irq/internals.h:242
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_disable
```
```
In kernel/irq/pm.c (ffffffff811a2ee3)
Location: kernel/irq/internals.h:242
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
In kernel/irq/chip.c (ffffffff811ae390)
Location: kernel/irq/internals.h:247
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
```
In kernel/irq/pm.c (ffffffff811b4de3)
Location: kernel/irq/internals.h:247
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
In kernel/irq/chip.c (ffffffff811bdf90)
Location: kernel/irq/internals.h:247
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
```
In kernel/irq/pm.c (ffffffff811c4c63)
Location: kernel/irq/internals.h:247
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
In kernel/irq/chip.c (ffff80001017f4c0)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (ffff8000101867a0)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (c03cf72c)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (c03d55cc)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (c0000000001d9e90)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (c0000000001e1168)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (ffffffe000117a10)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
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
In kernel/irq/chip.c (ffffffff81113abd)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (ffffffff81118fc2)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (ffffffff811047cd)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (ffffffff8110a032)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (ffffffff811119ad)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (ffffffff81116eb2)
Location: kernel/irq/internals.h:238
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
In kernel/irq/chip.c (ffffffff8111cf6d)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (ffffffff81122542)
Location: kernel/irq/internals.h:238
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
```
</details>
</li>
</ul>

## Differences
