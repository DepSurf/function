# Function: <code>irq_get_desc_buslock</code>

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
In kernel/irq/manage.c (ffffffff810dacd6)
Location: kernel/irq/internals.h:140
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
```
```
In kernel/irq/chip.c (ffffffff810dda96)
Location: kernel/irq/internals.h:140
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
In kernel/irq/manage.c (ffffffff810e0416)
Location: kernel/irq/internals.h:147
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810e4116)
Location: kernel/irq/internals.h:147
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
In kernel/irq/manage.c (ffffffff810e6d66)
Location: kernel/irq/internals.h:147
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810ea666)
Location: kernel/irq/internals.h:147
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
In kernel/irq/manage.c (ffffffff810e6466)
Location: kernel/irq/internals.h:162
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810e9d86)
Location: kernel/irq/internals.h:162
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
In kernel/irq/manage.c (ffffffff810ee716)
Location: kernel/irq/internals.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810f22d6)
Location: kernel/irq/internals.h:165
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
In kernel/irq/manage.c (ffffffff810f6b31)
Location: kernel/irq/internals.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff810fa752)
Location: kernel/irq/internals.h:165
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
In kernel/irq/manage.c (ffffffff811022a1)
Location: kernel/irq/internals.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81105f12)
Location: kernel/irq/internals.h:165
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
In kernel/irq/manage.c (ffffffff8110a9b1)
Location: kernel/irq/internals.h:172
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8110f3b2)
Location: kernel/irq/internals.h:172
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
In kernel/irq/manage.c (ffffffff81116d81)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8111b672)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff81120bbc)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffff81122871)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff811278b1)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8112d18c)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffff8111e6a1)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff811234b1)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff81128bec)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffff8111e9b1)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81123811)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff81128e6c)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffff8113ee41)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81143de1)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8114944c)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffff81162489)
Location: kernel/irq/internals.h:172
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff811682ff)
Location: kernel/irq/internals.h:172
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8116e003)
Location: kernel/irq/internals.h:172
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
In kernel/irq/manage.c (ffffffff81195ff9)
Location: kernel/irq/internals.h:174
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8119c7ef)
Location: kernel/irq/internals.h:174
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff811a3283)
Location: kernel/irq/internals.h:174
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
In kernel/irq/manage.c (ffffffff811a79b9)
Location: kernel/irq/internals.h:179
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff811ae66f)
Location: kernel/irq/internals.h:179
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff811b5183)
Location: kernel/irq/internals.h:179
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
In kernel/irq/manage.c (ffffffff811b7519)
Location: kernel/irq/internals.h:179
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff811be26f)
Location: kernel/irq/internals.h:179
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff811c5003)
Location: kernel/irq/internals.h:179
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
In kernel/irq/manage.c (ffff800010178ce4)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffff80001017f6cc)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffff800010186be8)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (c03ca68c)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (c03cf8e0)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (c03d5858)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (c0000000001d2fc0)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (c0000000001da168)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (c0000000001e1428)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffe000113798)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffe000117b30)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffff8110f361)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81113c52)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8111919c)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffff811000a1)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81104962)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8110a20c)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffff8110d251)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff81111b42)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8111708c)
Location: kernel/irq/internals.h:170
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
In kernel/irq/manage.c (ffffffff811187b1)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
```
```
In kernel/irq/chip.c (ffffffff8111d102)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
```
In kernel/irq/pm.c (ffffffff8112271c)
Location: kernel/irq/internals.h:170
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
```
</details>
</li>
</ul>

## Differences
