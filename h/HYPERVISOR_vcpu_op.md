# Function: <code>HYPERVISOR_vcpu_op</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101c1e3)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/irq.c (ffffffff810233b5)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff81023791)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/smp.c (ffffffff8102b427)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_smp_init
```
```
In drivers/xen/events/events_base.c (ffffffff814c97a4)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101c840)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
```
```
In arch/x86/xen/irq.c (ffffffff81022743)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff81f8b540)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/smp.c (ffffffff81f8cd6a)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_init
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/time.c (ffffffff8151809e)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff8151a2ce)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101cf62)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
```
```
In arch/x86/xen/irq.c (ffffffff81022e93)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff81fc6923)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/smp.c (ffffffff81fc8173)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_init
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/time.c (ffffffff815445ae)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff815467be)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff81019a3a)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/irq.c (ffffffff8101ab73)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff820a3845)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/smp_pv.c (ffffffff820a8821)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/time.c (ffffffff8155843e)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff8155a5de)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101a31a)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/irq.c (ffffffff8101b473)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff826a9d2f)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/smp_pv.c (ffffffff826aee18)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/time.c (ffffffff815bc7ee)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff815bea1e)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101ad04)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/irq.c (ffffffff8101be6e)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
```
```
In arch/x86/xen/time.c (ffffffff826d2ea2)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
```
```
In arch/x86/xen/smp_pv.c (ffffffff826d80b3)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In drivers/xen/time.c (ffffffff815f4e61)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff815f705b)
Location: arch/x86/include/asm/xen/hypercall.h:428
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101b4d4)
Location: arch/x86/include/asm/xen/hypercall.h:382
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff82888f32)
Location: arch/x86/include/asm/xen/hypercall.h:382
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
```
```
In arch/x86/xen/irq.c (ffffffff8102608e)
Location: arch/x86/include/asm/xen/hypercall.h:382
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8288e0d3)
Location: arch/x86/include/asm/xen/hypercall.h:382
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In drivers/xen/time.c (ffffffff8160fcc1)
Location: arch/x86/include/asm/xen/hypercall.h:382
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff816120eb)
Location: arch/x86/include/asm/xen/hypercall.h:382
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101cff4)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828a01db)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
```
```
In arch/x86/xen/irq.c (ffffffff81027dae)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a5667)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In drivers/xen/time.c (ffffffff81643af1)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81645e76)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101d974)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828a32cb)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/irq.c (ffffffff810286be)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a86fa)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In drivers/xen/time.c (ffffffff816660a1)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff816683f6)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101fdc3)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff82cc96ba)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8102a61e)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff82cce04a)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
```
```
In drivers/xen/time.c (ffffffff817157df)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81718586)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff81020863)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff82fb550b)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8102af3e)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff82fb9e7a)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
```
```
In drivers/xen/time.c (ffffffff817321af)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81735b56)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff81022c03)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff831bfcde)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8102bb1e)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff831c4520)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In drivers/xen/time.c (ffffffff81715c7f)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81719336)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff81026b9e)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff832a03f0)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff81030275)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810354a4)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In drivers/xen/time.c (ffffffff81792eb3)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81797161)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8102ad1f)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff8344f2b5)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff81035864)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b413)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In drivers/xen/time.c (ffffffff818cb7fb)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff818d0113)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8103195f)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff83e6abdf)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8103d4f4)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043bd3)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In drivers/xen/time.c (ffffffff81a1cb8b)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81a21893)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8103195f)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff8368b582)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff8103d384)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043cf3)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In drivers/xen/time.c (ffffffff81a65d8b)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81a6ac23)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff81037c4f)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff838bb142)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_vcpuop_set_oneshot
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
  - arch/x86/xen/time.c:xen_vcpuop_shutdown
```
```
In arch/x86/xen/irq.c (ffffffff81043844)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a1f3)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In drivers/xen/time.c (ffffffff81ab85eb)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81abceb1)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/xen/enlighten.c:xen_starting_cpu
  - drivers/xen/time.c:xen_setup_runstate_info
```
**Symbols:**

```
ffff8000100f0d50-ffff8000100f0d5c: HYPERVISOR_vcpu_op (STB_GLOBAL)
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
In arch/x86/xen/enlighten.c (ffffffff8101d974)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828912cb)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/irq.c (ffffffff8102881e)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8289670a)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In drivers/xen/time.c (ffffffff8162bdd1)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff8162e126)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101d934)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828a42cb)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/irq.c (ffffffff8102867e)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a96fa)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In drivers/xen/time.c (ffffffff81659ee1)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff8165c236)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
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
In arch/x86/xen/enlighten.c (ffffffff8101db84)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff828a42df)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/irq.c (ffffffff8102930e)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a970a)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In drivers/xen/time.c (ffffffff816744b1)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_setup_runstate_info
```
```
In drivers/xen/events/events_base.c (ffffffff81676826)
Location: arch/x86/include/asm/xen/hypercall.h:392
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
</details>
</li>
</ul>

## Differences
