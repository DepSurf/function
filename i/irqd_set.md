# Function: <code>irqd_set</code>

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
In kernel/irq/irqdesc.c (ffffffff810da1cd)
Location: kernel/irq/internals.h:181
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff810daa59)
Location: kernel/irq/internals.h:181
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810db023)
Location: kernel/irq/internals.h:181
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/chip.c (ffffffff810dda02)
Location: kernel/irq/internals.h:181
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/pm.c (ffffffff810e2771)
Location: kernel/irq/internals.h:181
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff810df6c5)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff810e0069)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810e20f7)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff810e3212)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff810e8201)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff810e5de8)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff810e69b6)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810e8ad6)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff810e9ae5)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_shutdown
```
```
In kernel/irq/pm.c (ffffffff810eec3b)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff810e543b)
Location: kernel/irq/internals.h:220
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff810e6006)
Location: kernel/irq/internals.h:220
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810e7f03)
Location: kernel/irq/internals.h:220
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff810e8ff4)
Location: kernel/irq/internals.h:220
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff810eebb8)
Location: kernel/irq/internals.h:220
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff810ed697)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff810ee286)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810f02eb)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff810f1454)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff810f7668)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff810f5a67)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff810f64d3)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810f864d)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff810f9894)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff810ff9c8)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff811011f7)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff81101c43)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81103ded)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff81105044)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8110b1a8)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff811099f0)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff8110a453)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff8110c89a)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff8110e327)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff81114887)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff81115dc0)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff81116823)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81118c7a)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff8111a5e7)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff81120c00)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff81121896)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:desc_set_defaults
  - kernel/irq/irqdesc.c:desc_set_defaults
```
```
In kernel/irq/handle.c (ffffffff81122466)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff8112455e)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff81126663)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
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
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8112d1df)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff8111d9c6)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:desc_set_defaults
  - kernel/irq/irqdesc.c:desc_set_defaults
```
```
In kernel/irq/handle.c (ffffffff8111e436)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff811203be)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff811222a3)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
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
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff81128c3f)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irq
  - kernel/irq/pm.c:resume_irq
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff8111dbb1)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff8111e746)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81120659)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff81122623)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
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
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff81128ebf)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff8113dfc8)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff8113ebe6)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81140b87)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff81142bd3)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
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
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8114949f)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff811615db)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff81162203)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff8116466a)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff8116687b)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
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
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8116e061)
Location: kernel/irq/internals.h:230
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff81194c58)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff81195ca3)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81198440)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff8119ab2b)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
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
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811a32e1)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff811a63d8)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff811a7663)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff811aa143)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff811ac88b)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
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
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811b51e1)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff811b5ef7)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff811b71c3)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff811b9c39)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff811bc48b)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
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
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811c5061)
Location: kernel/irq/internals.h:237
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffff800010177558)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffff8000101789e4)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffff80001017b720)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffff80001017ec84)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffff800010186c40)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (c03c9468)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (c03ca15c)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (c03cc720)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (c03ce438)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (c03d58a8)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (c0000000001d113c)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (c0000000001d291c)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (c0000000001d5d88)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (c0000000001d8564)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (c0000000001e1488)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffe000112516)
Location: kernel/irq/internals.h:228
Inline: True
```
```
In kernel/irq/handle.c (ffffffe000113352)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffe0001152c4)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffe000116862)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
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
In kernel/irq/irqdesc.c (ffffffff8110e3a0)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff8110ee03)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff8111125a)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff81112bc7)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811191e0)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff810ff100)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff810ffb43)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81101f8a)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff811038e7)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8110a250)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff8110c290)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff8110ccf3)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff8110f14a)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff81110ab7)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811170d0)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/irqdesc.c (ffffffff811179c0)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/handle.c (ffffffff81118253)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff8111a67a)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff8111c037)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff81122760)
Location: kernel/irq/internals.h:228
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
</details>
</li>
</ul>

## Differences
