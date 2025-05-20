# Function: <code>xen_vcpu_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81891c12)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
```
```
In arch/x86/xen/irq.c (ffffffff81022739)
Location: include/xen/xen-ops.h:13
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff81f8b536)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/smp.c (ffffffff8102a080)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/time.c (ffffffff815180aa)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff8151a57a)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151b763)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff818c6529)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
```
```
In arch/x86/xen/irq.c (ffffffff81022e89)
Location: include/xen/xen-ops.h:13
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff81fc6919)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/smp.c (ffffffff8102a7d0)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/time.c (ffffffff815445ba)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81546a6a)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff81547c53)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff81019995)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/irq.c (ffffffff8101ab69)
Location: include/xen/xen-ops.h:13
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff820a383b)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/smp.c (ffffffff820a8406)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff810292f0)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/time.c (ffffffff8155844a)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff8155a848)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155bc86)
Location: include/xen/xen-ops.h:13
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8101a275)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/irq.c (ffffffff8101b469)
Location: include/xen/xen-ops.h:14
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff826a9d25)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/smp.c (ffffffff826aea1c)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff810294df)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/time.c (ffffffff815bc7fa)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff815becd8)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bffa6)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8101ac55)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/irq.c (ffffffff8101be57)
Location: include/xen/xen-ops.h:14
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff826d2e8b)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
```
```
In arch/x86/xen/smp.c (ffffffff826d7cf3)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029f57)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/time.c (ffffffff815f4e5a)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff815f7319)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f85c2)
Location: include/xen/xen-ops.h:14
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8101b425)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff82888f1b)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
```
```
In arch/x86/xen/irq.c (ffffffff81026077)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8288dd13)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a537)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/time.c (ffffffff8160fcba)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff816123b9)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff81613412)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8101cf45)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828a01c4)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
```
```
In arch/x86/xen/irq.c (ffffffff81027d97)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff828a528c)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c389)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
```
In drivers/xen/time.c (ffffffff81643aea)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81646148)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff81647304)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8101d8c5)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828a32b4)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/irq.c (ffffffff810286a7)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff828a831c)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cd2a)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
```
In drivers/xen/time.c (ffffffff8166609a)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff816686c8)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff816697a4)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8101fdbc)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff82cc96a3)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8102a607)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff82ccdc6e)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ec92)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/time.c (ffffffff817157d8)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff8171695f)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff817195c6)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8102085c)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff82fb54f4)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8102af27)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff82fb9a9e)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102faa2)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/time.c (ffffffff817321a8)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff817344ff)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff81736776)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff81022bfc)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff831bfcc7)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8102bb07)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff831c415d)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103060a)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/time.c (ffffffff81715c78)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81719899)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a1c7)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff81026b89)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff832a03c9)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8103025a)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff832a4ce7)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff81035493)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/time.c (ffffffff81792ea3)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff817977c9)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff817987ed)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8102ad0a)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff8344f503)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff81035849)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b402)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/time.c (ffffffff818cb7eb)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff818d0838)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1ab5)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8103194a)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff83e6afe7)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8103d4d9)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043bc2)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/time.c (ffffffff81a1cb7b)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81a22038)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a238a5)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8103194a)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff8368ba87)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8103d369)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043ce2)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/time.c (ffffffff81a65d7b)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81a6b3cf)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6cd54)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff81037c3a)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_info_reset
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff838bb647)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff81043829)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a1e2)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/time.c (ffffffff81ab85db)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81abd4a3)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abee24)
Location: include/xen/xen-ops.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/arm/xen/enlighten.c (ffff8000100f00b0)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_starting_cpu
```
```
In drivers/xen/time.c (ffff80001082fc14)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffff800010832778)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffff800010833880)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d8c5)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828912b4)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/irq.c (ffffffff81028807)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8289632c)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ce8a)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
```
In drivers/xen/time.c (ffffffff8162bdca)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff8162e3f8)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f614)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d885)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828a42b4)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/irq.c (ffffffff81028667)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff828a931c)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ccea)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
```
In drivers/xen/time.c (ffffffff81659eda)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff8165c508)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d5e4)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
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
In arch/x86/xen/enlighten.c (ffffffff8101dad5)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828a42c8)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/irq.c (ffffffff810292f7)
Location: include/xen/xen-ops.h:15
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff828a932c)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102dada)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
```
In drivers/xen/time.c (ffffffff816744aa)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81676af8)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677bf4)
Location: include/xen/xen-ops.h:15
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
</details>
</li>
</ul>

## Differences
