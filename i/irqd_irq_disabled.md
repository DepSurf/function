# Function: <code>irqd_irq_disabled</code>

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
In kernel/irq/manage.c (ffffffff810dba61)
Location: include/linux/irq.h:267
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff810dd233)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
```
```
In kernel/irq/chip.c (ffffffff810ddbdd)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_offline
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:267
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
In kernel/irq/manage.c (ffffffff810e0d94)
Location: include/linux/irq.h:275
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff810e29d9)
Location: include/linux/irq.h:275
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
```
```
In kernel/irq/chip.c (ffffffff810e42a1)
Location: include/linux/irq.h:275
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:275
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/irq.h:275
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
In kernel/irq/manage.c (ffffffff810e7ce4)
Location: include/linux/irq.h:277
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff810e92f2)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
```
```
In kernel/irq/chip.c (ffffffff810eab41)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:277
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/irq.h:277
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
In kernel/irq/manage.c (ffffffff810e6ba4)
Location: include/linux/irq.h:305
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff810e87c7)
Location: include/linux/irq.h:305
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
```
```
In kernel/irq/chip.c (ffffffff810ea23e)
Location: include/linux/irq.h:305
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:305
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/irq.h:305
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
In kernel/irq/manage.c (ffffffff810eee64)
Location: include/linux/irq.h:317
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff810f0b97)
Location: include/linux/irq.h:317
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
```
```
In kernel/irq/chip.c (ffffffff810f27c1)
Location: include/linux/irq.h:317
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:317
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/irq.h:317
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
In kernel/irq/manage.c (ffffffff810f8244)
Location: include/linux/irq.h:312
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff810f8fe5)
Location: include/linux/irq.h:312
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff810faba1)
Location: include/linux/irq.h:312
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (ffffffff810ff400)
Location: include/linux/irq.h:312
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In drivers/xen/events/events_base.c (ffffffff815f5fc4)
Location: include/linux/irq.h:312
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In kernel/irq/manage.c (ffffffff811039e4)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81104785)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff81106361)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (ffffffff8110abe0)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In drivers/xen/events/events_base.c (ffffffff81611084)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In kernel/irq/manage.c (ffffffff8110c430)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff8110d9a7)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff8110f921)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (ffffffff81114290)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In drivers/xen/events/events_base.c (ffffffff81644df5)
Location: include/linux/irq.h:313
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In kernel/irq/manage.c (ffffffff81118810)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81119c67)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff8111bbe1)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (ffffffff81120400)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In drivers/xen/events/events_base.c (ffffffff816673a5)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In kernel/irq/manage.c (ffffffff81124100)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81125b97)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff81127f11)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff8112c940)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In drivers/xen/events/events_base.c (ffffffff817171e5)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In kernel/irq/manage.c (ffffffff8111ff60)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff811218a7)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff81123a91)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff81128370)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/pm.c (ffffffff81128a61)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/manage.c (ffffffff81120220)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81121b87)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff81123df1)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff81128630)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/pm.c (ffffffff81128cf1)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/manage.c (ffffffff81140750)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81142127)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff811443d1)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff81148c00)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/pm.c (ffffffff811492d1)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/manage.c (ffffffff81164143)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81165c5d)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff81167168)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff8116d740)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/pm.c (ffffffff8116de48)
Location: include/linux/irq.h:344
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/manage.c (ffffffff81197ee3)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81199c2d)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff8119b4b8)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff811a28f0)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/pm.c (ffffffff811a3208)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/manage.c (ffffffff811a9ba3)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff811ab85d)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff811ad2f8)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff811b47f0)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/pm.c (ffffffff811b5108)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/manage.c (ffffffff811b9703)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff811bb45d)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff811bcef8)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff811c4670)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/pm.c (ffffffff811c4f88)
Location: include/linux/irq.h:346
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In arch/arm64/kernel/machine_kexec.c (ffff8000100aa038)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_crash_shutdown
```
```
In kernel/irq/manage.c (ffff80001017b15c)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffff80001017cc88)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffff80001017ecb8)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In drivers/xen/events/events_base.c (ffff800010831134)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/arm/kernel/machine_kexec.c (c0315444)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_shutdown
```
```
In kernel/irq/manage.c (c03cc290)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (c03cd7f4)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (c03d0008)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081e514)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume
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
In arch/powerpc/kernel/eeh_driver.c (c00000000004a604)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state
```
```
In arch/powerpc/kernel/machine_kexec.c (c000000000070258)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec.c:machine_kexec_mask_interrupts
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bdef0)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_irq_eoi
```
```
In kernel/irq/manage.c (c0000000001d57a4)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (c0000000001d7660)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (c0000000001dab78)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/manage.c (ffffffe000114d3e)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffe000115eb6)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffe0001181d6)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/manage.c (ffffffff81110df0)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81112247)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff811141c1)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (ffffffff811189e0)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In drivers/xen/events/events_base.c (ffffffff8162d0d5)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In kernel/irq/manage.c (ffffffff81101b20)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81102f77)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff81104ed1)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (ffffffff81109a50)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
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
In kernel/irq/manage.c (ffffffff8110ece0)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff81110137)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff811120b1)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (ffffffff811168d0)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In drivers/xen/events/events_base.c (ffffffff8165b1e5)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In kernel/irq/manage.c (ffffffff8111a210)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/spurious.c (ffffffff8111b6a9)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffff8111d6d1)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/migration.c (ffffffff81121f10)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In drivers/xen/events/events_base.c (ffffffff816757d5)
Location: include/linux/irq.h:316
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
</details>
</li>
</ul>

## Differences
