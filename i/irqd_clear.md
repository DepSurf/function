# Function: <code>irqd_clear</code>

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
In kernel/irq/handle.c (ffffffff810daa80)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810db032)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/chip.c (ffffffff810dd9ed)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/pm.c (ffffffff810e2867)
Location: kernel/irq/internals.h:176
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff810e0090)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810e20e0)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/irq/chip.c (ffffffff810e31fd)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/pm.c (ffffffff810e82f7)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff810e69dd)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810e8ac0)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/irq/chip.c (ffffffff810e9ad3)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/pm.c (ffffffff810eed31)
Location: kernel/irq/internals.h:185
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff810e602d)
Location: kernel/irq/internals.h:215
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810e7eed)
Location: kernel/irq/internals.h:215
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff810e8fde)
Location: kernel/irq/internals.h:215
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff810eeb95)
Location: kernel/irq/internals.h:215
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff810ee2ad)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810f02b8)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff810f143e)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff810f7645)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff810f64fa)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff810f861a)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff810f987e)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff810ff9a5)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff81101c6a)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81103dba)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff8110502e)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8110b185)
Location: kernel/irq/internals.h:218
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff8110a47a)
Location: kernel/irq/internals.h:225
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff8110c861)
Location: kernel/irq/internals.h:225
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff8110e311)
Location: kernel/irq/internals.h:225
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8111485d)
Location: kernel/irq/internals.h:225
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff8111684a)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81118c41)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff8111a5d1)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811209bd)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff811224a8)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81124525)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff81126651)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8112cf78)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff8111e478)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81120385)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff81122291)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff81128805)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irq
  - kernel/irq/pm.c:resume_irq
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff8111e788)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81120645)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff81122611)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff81128b00)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff8113ec25)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81140b75)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff81142bc1)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811490e0)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff81162232)
Location: kernel/irq/internals.h:225
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81164619)
Location: kernel/irq/internals.h:225
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff81166869)
Location: kernel/irq/internals.h:225
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8116dc6f)
Location: kernel/irq/internals.h:225
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff81195cd2)
Location: kernel/irq/internals.h:227
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff811983ef)
Location: kernel/irq/internals.h:227
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff8119ab19)
Location: kernel/irq/internals.h:227
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811a2eaf)
Location: kernel/irq/internals.h:227
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff811a7692)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff811aa0f2)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff811ac879)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811b4daf)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff811b71f2)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff811b9be8)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff811bc479)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff811c4c2f)
Location: kernel/irq/internals.h:232
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffff800010178a2c)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffff80001017b6e4)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffff80001017dc50)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffff800010186774)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (c03ca194)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (c03cc704)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (c03ce424)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (c03d55ac)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (c0000000001d2968)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (c0000000001d5d40)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (c0000000001d854c)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (c0000000001e1134)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffe0001133b4)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffe0001152a6)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffe00011684c)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
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
In kernel/irq/handle.c (ffffffff8110ee2a)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81111221)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff81112bb1)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff81118f9d)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff810ffb6a)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff81101f51)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff811038d1)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8110a00d)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff8110cd1a)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff8110f111)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff81110aa1)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff81116e8d)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/handle.c (ffffffff81118278)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffff8111a641)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff8111c021)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/pm.c (ffffffff8112251d)
Location: kernel/irq/internals.h:223
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
</details>
</li>
</ul>

## Differences
