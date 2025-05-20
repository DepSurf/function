# Function: <code>apic_chip_data</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff81054d06)
Location: arch/x86/kernel/apic/vector.c:53
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
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
In arch/x86/kernel/apic/vector.c (ffffffff81055d95)
Location: arch/x86/kernel/apic/vector.c:53
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:irq_cfg
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
In arch/x86/kernel/apic/vector.c (ffffffff81058b5e)
Location: arch/x86/kernel/apic/vector.c:53
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810581b8)
Location: arch/x86/kernel/apic/vector.c:53
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff81057490-ffffffff810574ad: apic_chip_data.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105c6bf)
Location: arch/x86/kernel/apic/vector.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff8105b2d0-ffffffff8105b2ed: apic_chip_data.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f71f)
Location: arch/x86/kernel/apic/vector.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff8105e210-ffffffff8105e22d: apic_chip_data.part.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106538f)
Location: arch/x86/kernel/apic/vector.c:81
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff81063ea0-ffffffff81063ebd: apic_chip_data.part.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068a6f)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff81067560-ffffffff8106757b: apic_chip_data.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810693df)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff81067ea0-ffffffff81067ebb: apic_chip_data.part.0 (STB_LOCAL)
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
In arch/x86/kernel/apic/vector.c (ffffffff810703af)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:vector_free_reserved_and_managed
  - arch/x86/kernel/apic/vector.c:vector_free_reserved_and_managed
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_reserved
  - arch/x86/kernel/apic/vector.c:activate_reserved
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_managed_vector
  - arch/x86/kernel/apic/vector.c:reserve_managed_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
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
In arch/x86/kernel/apic/vector.c (ffffffff8107190f)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:vector_free_reserved_and_managed
  - arch/x86/kernel/apic/vector.c:vector_free_reserved_and_managed
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_reserved
  - arch/x86/kernel/apic/vector.c:activate_reserved
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_managed_vector
  - arch/x86/kernel/apic/vector.c:reserve_managed_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
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
In arch/x86/kernel/apic/vector.c (ffffffff8107240f)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
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
In arch/x86/kernel/apic/vector.c (ffffffff8107e2ef)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
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
In arch/x86/kernel/apic/vector.c (ffffffff8108d98f)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
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
In arch/x86/kernel/apic/vector.c (ffffffff810a20cf)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
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
In arch/x86/kernel/apic/vector.c (ffffffff810a50af)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
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
In arch/x86/kernel/apic/vector.c (ffffffff810ac13f)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068ecf)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff81067990-ffffffff810679ab: apic_chip_data.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105923f)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff81057d00-ffffffff81057d1b: apic_chip_data.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106937f)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff81067e40-ffffffff81067e5b: apic_chip_data.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106aa7f)
Location: arch/x86/kernel/apic/vector.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/vector.c:irq_cfg
```
**Symbols:**

```
ffffffff81069500-ffffffff8106951b: apic_chip_data.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
