# Function: <code>irq_put_desc_busunlock</code>

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
In kernel/irq/manage.c (ffffffff810dad36)
Location: kernel/irq/internals.h:146
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
```
```
In kernel/irq/chip.c (ffffffff810ddadb)
Location: kernel/irq/internals.h:146
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
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
In kernel/irq/manage.c (ffffffff810e0477)
Location: kernel/irq/internals.h:153
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810e4161)
Location: kernel/irq/internals.h:153
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
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
In kernel/irq/manage.c (ffffffff810e6dc7)
Location: kernel/irq/internals.h:153
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810ea6b1)
Location: kernel/irq/internals.h:153
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
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
In kernel/irq/manage.c (ffffffff810e64c7)
Location: kernel/irq/internals.h:168
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810e9dd5)
Location: kernel/irq/internals.h:168
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
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
In kernel/irq/manage.c (ffffffff810ee77a)
Location: kernel/irq/internals.h:171
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810f2325)
Location: kernel/irq/internals.h:171
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
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
In kernel/irq/manage.c (ffffffff810f6b6a)
Location: kernel/irq/internals.h:171
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810fa775)
Location: kernel/irq/internals.h:171
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
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
In kernel/irq/manage.c (ffffffff811022da)
Location: kernel/irq/internals.h:171
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81105f35)
Location: kernel/irq/internals.h:171
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
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
In kernel/irq/manage.c (ffffffff8110a9f0)
Location: kernel/irq/internals.h:178
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8110f3d5)
Location: kernel/irq/internals.h:178
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
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
In kernel/irq/manage.c (ffffffff81116dc0)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8111b695)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff81120c0b)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff811228aa)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff811278dc)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8112d1ae)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff8111e6da)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff811234dc)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff81128c0e)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff8111e9ea)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8112383c)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff81128e8e)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff8113ee7a)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81143e0c)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8114946e)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff811624c5)
Location: kernel/irq/internals.h:178
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8116831c)
Location: kernel/irq/internals.h:178
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8116e024)
Location: kernel/irq/internals.h:178
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff81196035)
Location: kernel/irq/internals.h:180
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8119c80c)
Location: kernel/irq/internals.h:180
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff811a32a4)
Location: kernel/irq/internals.h:180
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff811a79f5)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff811ae68c)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff811b51a4)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff811b7555)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff811be28c)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff811c5024)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffff800010178d30)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffff80001017f6fc)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffff800010186c50)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (c03ca6d4)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (c03cf900)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (c03d58b8)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (c0000000001d3004)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (c0000000001da18c)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (c0000000001e149c)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffe0001137c8)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffe000117b58)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
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
In kernel/irq/manage.c (ffffffff8110f3a0)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81113c75)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff811191eb)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff811000e0)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81104985)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8110a25b)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff8110d290)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81111b65)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff811170db)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
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
In kernel/irq/manage.c (ffffffff811187f0)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8111d125)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8112276b)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
```
</details>
</li>
</ul>

## Differences
