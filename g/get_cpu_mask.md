# Function: <code>get_cpu_mask</code>

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
In arch/x86/xen/time.c (ffffffff81023a99)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102ae15)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/kernel/smp.c (ffffffff810507b5)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_single_ipi
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052e69)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054a04)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81054d78)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059250)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810596d0)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059fec)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a4c0)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/hpet.c (ffffffff810622d8)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_resume
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/cpu.c (ffffffff81081631)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff81f7c46d)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/kthread.c (ffffffff810a0715)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_bind
```
```
In kernel/reboot.c (ffffffff810a29f5)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810ae663)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/time/clockevents.c (ffffffff810fb9ac)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff810fc577)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_install_replacement
  - kernel/time/tick-common.c:tick_check_new_device
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcd74)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff81120416)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff8118686e)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ad9b3)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff814c8035)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
```
In drivers/net/virtio_net.c (ffffffff815f173f)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b1acf)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b5db5)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:boost_notify
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/clocksource/i8253.c (ffffffff81fb7486)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff81fb7531)
Location: include/linux/cpumask.h:756
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
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
In arch/x86/xen/time.c (ffffffff81022d39)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102a135)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:791
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81053039)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054b84)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81054f05)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81054fb8)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810596b0)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059920)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a2bc)
Location: include/linux/cpumask.h:791
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a685)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/hpet.c (ffffffff810623a3)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_resume
```
```
In kernel/cpu.c (ffffffff810838ab)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff81fa5215)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/kthread.c (ffffffff810a3e05)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_bind
```
```
In kernel/reboot.c (ffffffff810a6105)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810b1013)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/irqdesc.c (ffffffff81892b7d)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/time/clockevents.c (ffffffff81102cde)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81103d37)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff811040d4)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8112837b)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff81198f1c)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/pci/msi.c (ffffffff814a0eb7)
Location: include/linux/cpumask.h:791
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd3b0)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:791
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8151a3cd)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/net/virtio_net.c (ffffffff8165115f)
Location: include/linux/cpumask.h:791
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713ac2)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8171790b)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:boost_notify
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff81fe4f62)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff81fe500b)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
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
In arch/x86/xen/time.c (ffffffff81023489)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102a885)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:796
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81055d29)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8105796b)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057cd5)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057d88)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c466)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c6d6)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d094)
Location: include/linux/cpumask.h:796
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d6f6)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/hpet.c (ffffffff81065413)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_msi_resume
```
```
In kernel/cpu.c (ffffffff8108803b)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff81fe0dcd)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810a9756)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810abd67)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810b72a4)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/time/clockevents.c (ffffffff8110a3cf)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8110b427)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff8110b7d4)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8113200b)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff811a88fc)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/acpi/processor_throttling.c (ffffffff8151fe6e)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:796
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff815468bd)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81745814)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81749b8b)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff820238f7)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff820239a0)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
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
In init/main.c (ffffffff818fda86)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff8101b14e)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff81028eb5)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:839
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:839
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056e4a)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810570eb)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057455)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057511)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105bb66)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105be06)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c47e)
Location: include/linux/cpumask.h:839
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cdf6)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/hpet.c (ffffffff81064342)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/cpu.c (ffffffff81084fbb)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff820c1bff)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810a6407)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810a8936)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810b35b4)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/rcu/tree.c (ffffffff810f6ecd)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff8110c332)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8110d317)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff8110d6c4)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff811335d1)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff811b00ab)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:839
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8155911b)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81763f35)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817681af)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff8210662b)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff821066d9)
Location: include/linux/cpumask.h:839
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
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
In init/main.c (ffffffff81987b36)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff8101ba4e)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff810290c5)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:843
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:843
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810594e9)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8105b0c5)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105b3c6)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81060ab6)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/hpet.c (ffffffff810684c2)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/cpu.c (ffffffff8108ba4b)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff826c9da1)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810aca37)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810af1a6)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810ba824)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff810f9557)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81100f34)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff81117582)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81118597)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff81118954)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff81140381)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff811c3bcb)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:843
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff815bd50b)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d9f25)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de0a5)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff8270fd36)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff8270fe07)
Location: include/linux/cpumask.h:843
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
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
In init/main.c (ffffffff819e44fa)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff8101c432)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff81029b25)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:845
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:845
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105c2f9)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8105e0c5)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105e2f5)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81063bb6)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/hpet.c (ffffffff826e938a)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/cpu.c (ffffffff8108f313)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff826f403a)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810b3487)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810b5ff4)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810c1cab)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff81101aa4)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81108c68)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff81124021)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81125137)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff811254d7)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8114ec9b)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff811e3df5)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:845
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff815f5ba7)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81822a30)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81826d6a)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff82739fcf)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff8273a0e4)
Location: include/linux/cpumask.h:845
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
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
In init/main.c (ffffffff81a1f6a6)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff8101bf52)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102a105)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:857
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:857
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81061f79)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81063d55)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81063f85)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810698a9)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/hpet.c (ffffffff8289ff46)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/cpu.c (ffffffff81097613)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff828aae22)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810bc5c7)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810bf284)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810cafdb)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff8110d3c4)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81114488)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff8112f6fc)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81130827)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff81130bc7)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8115b97b)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff811f42a5)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:857
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81610c67)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184e910)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81852c6a)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff828f3f9e)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff828f409a)
Location: include/linux/cpumask.h:857
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
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
In init/main.c (ffffffff81a8fe79)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff8101dc72)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102bec5)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:856
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:856
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065628)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067415)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067646)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d096)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/hpet.c (ffffffff828b7fd8)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/cpu.c (ffffffff8109bb83)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff828c360c)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810c24de)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810c53a4)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810d2c6e)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff81116ac5)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff8111e1b3)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff8113a222)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8113b38a)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b727)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8116805b)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120bf97)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:856
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff816449c5)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81891e2f)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81896212)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff8290f9ca)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff8290fae2)
Location: include/linux/cpumask.h:856
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff818bca41)
Location: include/linux/cpumask.h:856
Inline: True
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
In init/main.c (ffffffff81ac7209)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff8101e5ec)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102c7a5)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065c98)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067c65)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067f86)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff828be4d6)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097789)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810985ed)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828c9ca5)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff810a2103)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff828cbbdf)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810c8c1e)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810ce4a4)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810dd0de)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff81122e95)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff8112a781)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff81145e8e)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81146f9a)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff81147337)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff81173f1b)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff81219277)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81666f75)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c3e87)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c8222)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff829196a5)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff829197bd)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef4b1)
Location: include/linux/cpumask.h:879
Inline: True
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
In init/main.c (ffffffff81bbfc79)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff81020b6b)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102e785)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:884
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031e5b)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:884
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106c5c8)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106e9b5)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106f090)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d1f7)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109c8c4)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109dddd)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82cec5f6)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff810a96f3)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff82cedba3)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810d0eca)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810d8214)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810e5cbe)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff8112f4d8)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81138b06)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff81155cfd)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81156e1f)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff811571b7)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff81185ef0)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff81244cfe)
Location: include/linux/cpumask.h:884
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:884
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81716d85)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8199608b)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199a3bf)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff82d2bdc1)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff82d2bedf)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c2ecd)
Location: include/linux/cpumask.h:884
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_init
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
In init/main.c (ffffffff81c38c39)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff81bd2858)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102f5e5)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:890
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032b24)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:890
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106dd78)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106fe35)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107061e)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d167)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810999ad)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82fd8c4c)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff810a5123)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff82fda1fd)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810cb97a)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810d34d4)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810e39ef)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__schedule
```
```
In kernel/irq/matrix.c (ffffffff8112b404)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81be23eb)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff81151e9d)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81152f3f)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff81153287)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff81183049)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff8124f34e)
Location: include/linux/cpumask.h:890
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:890
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81734220)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/xen/platform-pci.c (0)
Location: include/linux/cpumask.h:890
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8199919b)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d51f)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff8301a789)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff8301a8a7)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c32bd)
Location: include/linux/cpumask.h:890
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_init
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
In init/main.c (ffffffff81c2aff9)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff81bc49fa)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff81030105)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:869
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810334ad)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033f84)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:869
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e7d8)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81070985)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070e0e)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff831da7fd)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a1bd)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff831e34c9)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff810a5e43)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff831e4b9e)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810cd1fa)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810d51c4)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff831e5716)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__schedule
```
```
In kernel/irq/matrix.c (ffffffff8112b6b4)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81bd41ad)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/rcu/tree.c:trigger_single_cpu_backtrace
```
```
In kernel/time/clockevents.c (ffffffff8115324d)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81154325)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff81154687)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8118406d)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff81253e96)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In fs/io_uring.c (ffffffff813a0ee9)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:869
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81717d34)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/xen/platform-pci.c (0)
Location: include/linux/cpumask.h:869
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197d9ff)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff819820cd)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff832257d7)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff832258f5)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819a772d)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_init
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
In init/main.c (ffffffff81d49597)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff81c9705f)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff81034f35)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:869
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103863c)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810391d6)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:869
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107a131)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c5ee)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107cad2)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd9c1)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa1d9)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff832c6e6f)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff810b7634)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff832c89c1)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810df823)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_bind
```
```
In kernel/reboot.c (ffffffff810e83a8)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff832c964c)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__schedule
```
```
In kernel/irq/matrix.c (ffffffff8114c11c)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81cae3f8)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/rcu/tree.c:trigger_single_cpu_backtrace
```
```
In kernel/time/clockevents.c (ffffffff81177810)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81178ae9)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff811790ab)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff8128fa22)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In fs/io_uring.c (ffffffff813f074a)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:869
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff817955ef)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/xen/platform-pci.c (0)
Location: include/linux/cpumask.h:869
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a26a9c)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2b482)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff8330f950)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff8330fa82)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81a54c31)
Location: include/linux/cpumask.h:869
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_init
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
In init/main.c (ffffffff81f18a6b)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff81e4645e)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8103ac85)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:895
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e8c9)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81040082)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:895
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108909e)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8108b99e)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108c0f2)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f3b1)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfc29)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83479c72)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff810cdfb5)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff8347bafa)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810f9a80)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_bind
```
```
In kernel/reboot.c (ffffffff81102cee)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff8347c8c9)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__schedule
```
```
In kernel/irq/matrix.c (ffffffff81171a67)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81e5ea70)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/rcu/tree.c:trigger_single_cpu_backtrace
```
```
In kernel/time/clockevents.c (ffffffff811ac8c2)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff811add2b)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff811ae4fb)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff811ddebf)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff812e4a30)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In io_uring/io_uring.c (ffffffff816d902c)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:895
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff818ce32b)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/xen/platform-pci.c (0)
Location: include/linux/cpumask.h:895
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d8f7d)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b90e49)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b95a91)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff834c9764)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff834c9898)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4240)
Location: include/linux/cpumask.h:895
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_init
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
In init/main.c (ffffffff820c046b)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff81032a10)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff81043365)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:1004
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047936)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810492b2)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:1004
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109cd9e)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109fdee)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a0852)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff83e959c3)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810dbb19)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83ea41c1)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff810ec125)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff83ea6bba)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff8111c7f0)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_bind
```
```
In kernel/reboot.c (ffffffff811281ae)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff81142507)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__schedule
```
```
In kernel/irq/matrix.c (ffffffff811a80e3)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/time/clockevents.c (ffffffff811ecd12)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff811ee35b)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff811eec4b)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff812239af)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d41b)
Location: include/linux/cpumask.h:1004
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8179a4aa)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:1004
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81a1f94c)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/xen/platform-pci.c (0)
Location: include/linux/cpumask.h:1004
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b53f8d)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d3103f)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36371)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff83f0ae1b)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff83f0af7e)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81d699b0)
Location: include/linux/cpumask.h:1004
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_init
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
In init/main.c (ffffffff8214410b)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff810329b0)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff81043565)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:1056
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047b5e)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81049512)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:1056
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109fcbe)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2d6e)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a37d4)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff836b9544)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e70ca)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c84a1)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff810f9645)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff836cb417)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff81129980)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_bind
```
```
In kernel/reboot.c (ffffffff8113565e)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff8114e217)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__schedule
```
```
In kernel/irq/matrix.c (ffffffff811b9db3)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/time/clockevents.c (ffffffff81201442)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81202a8b)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff8120337b)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8123a03f)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/watchdog.c (ffffffff8125e8ac)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e2e6)
Location: include/linux/cpumask.h:1056
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff817db50a)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:1056
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81a68c95)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/xen/platform-pci.c (0)
Location: include/linux/cpumask.h:1056
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba74cd)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9a2d5)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9f6e1)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff83730feb)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff8373114e)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd5020)
Location: include/linux/cpumask.h:1056
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_init
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
In init/main.c (ffffffff8222682b)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff81038ca0)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff81049a65)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:1076
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e2c5)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81050485)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:1076
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a723e)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9c45)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aa7a4)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff838e9e66)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef47a)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f90a1)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff81102a55)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff838fc706)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff81133fc0)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_bind
```
```
In kernel/reboot.c (ffffffff811406be)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff8115a057)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__schedule
```
```
In kernel/irq/matrix.c (ffffffff811c9c73)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/time/clockevents.c (ffffffff812178e2)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8121904b)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff8121993b)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff81253d0f)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/watchdog.c (ffffffff812788a7)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7546)
Location: include/linux/cpumask.h:1076
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8181f855)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:1076
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81abb8ac)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/xen/platform-pci.c (0)
Location: include/linux/cpumask.h:1076
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb77d)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e51fb3)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e574f1)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff8396557b)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff839656e0)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d170)
Location: include/linux/cpumask.h:1076
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_init
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
In init/main.c (ffff800010d9bb64)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/arm64/kernel/smp.c (ffff80001009ce60)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:smp_send_reschedule
  - arch/arm64/kernel/smp.c:arch_irq_work_raise
  - arch/arm64/kernel/smp.c:arch_send_call_function_single_ipi
```
```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a9700)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
```
```
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e0bac)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_flush_hwstate
```
```
In kernel/cpu.c (ffff8000100f7074)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffff8000114433d0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffff800010128298)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffff80001012df28)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffff80001013cbb8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/time/clockevents.c (ffff8000101b0cb8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffff8000101b1e68)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffff8000101b244c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffff8000101e8714)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffff8000102a4350)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:toggle_bp_slot
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c3c0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f270)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010671c5c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800010676eb8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b518)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_set_affinity
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010810db4)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_online_cpu
  - drivers/soc/fsl/qbman/bman_portal.c:bman_offline_cpu
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff800010811344)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_online_cpu
  - drivers/soc/fsl/qbman/qman_portal.c:qman_offline_cpu
```
```
In drivers/soc/fsl/qbman/bman.c (ffff800010812160)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010815b24)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
```
```
In drivers/xen/events/events_base.c (ffff800010830c54)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/base/topology.c (ffff8000108f1de0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b217dc)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/cpuidle-arm.c (ffff8000114a2148)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-arm.c:arm_idle_init
```
```
In drivers/cpuidle/cpuidle-psci.c (ffff8000114a2338)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
```
```
In drivers/clocksource/timer-owl.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b679b0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
```
```
In drivers/clocksource/dummy_timer.c (ffff800010b68164)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/dummy_timer.c:dummy_timer_starting_cpu
```
```
In drivers/clocksource/timer-imx-sysctr.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/perf/arm-cci.c (ffff800010b90ba8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_cpumask_attr_show
```
```
In drivers/perf/arm-ccn.c (ffff800010b93a34)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cpumask_show
```
```
In drivers/perf/arm_pmu.c (ffff800010b95458)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96bfc)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99c24)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu
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
In init/main.c (c0e981f4)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/arm/kernel/smp.c (c0313770)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_send_reschedule
  - arch/arm/kernel/smp.c:arch_irq_work_raise
  - arch/arm/kernel/smp.c:arch_send_call_function_single_ipi
```
```
In arch/arm/kernel/smp_twd.c (c0314910)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
```
```
In arch/arm/kernel/hw_breakpoint.c (c031678c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
```
```
In arch/arm/common/mcpm_platsmp.c (c03262ec)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/common/mcpm_platsmp.c:mcpm_boot_secondary
```
```
In arch/arm/mach-exynos/platsmp.c (c032e838)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
```
```
In arch/arm/mach-hisi/platmcpm.c (c032f7d8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary
```
```
In arch/arm/mach-hisi/platsmp.c (c032f9c8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platsmp.c:hix5hd2_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hi3xxx_boot_secondary
```
```
In arch/arm/mach-mvebu/platsmp.c (c03319f4)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_boot_secondary
```
```
In arch/arm/mach-mvebu/platsmp-a9.c (c0331c28)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp-a9.c:mvebu_cortex_a9_boot_secondary
```
```
In arch/arm/mach-imx/platsmp.c (c0333a5c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-imx/platsmp.c:ls1021a_boot_secondary
```
```
In arch/arm/mach-mediatek/platsmp.c (c0334aec)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-mediatek/platsmp.c:mtk_boot_secondary
```
```
In arch/arm/mach-milbeaut/platsmp.c (c0334c7c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-milbeaut/platsmp.c:m10v_boot_secondary
```
```
In arch/arm/mach-omap2/omap-smp.c (c033c878)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_boot_secondary
```
```
In arch/arm/mach-qcom/platsmp.c (c0348be0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-qcom/platsmp.c:qcom_boot_secondary
```
```
In arch/arm/mach-shmobile/smp-emev2.c (c034a56c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/smp-emev2.c:emev2_boot_secondary
```
```
In arch/arm/plat-versatile/platsmp.c (c034fb04)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary
```
```
In kernel/cpu.c (c0355544)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (c151d2d0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (c037b200)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (c037dd6c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (c038d088)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/rcu/tree.c (c03e01f4)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (c03fb2c0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (c03fc610)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (c03fcc90)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (c0428820)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (c04d39a0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:toggle_bp_slot
```
```
In drivers/irqchip/irq-hip04.c (c0813fcc)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity
```
```
In drivers/irqchip/irq-gic.c (c0815744)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (c0818028)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081b1c0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081ebd4)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity
```
```
In drivers/soc/renesas/r9a06g032-smp.c (c0938530)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_boot_secondary
```
```
In drivers/base/topology.c (c09debc4)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
```
```
In drivers/cpufreq/cpufreq.c (c0bfbe1c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/mvebu-cpufreq.c (c15a4198)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
```
```
In drivers/cpuidle/cpuidle-arm.c (c15a4818)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-arm.c:arm_idle_init
```
```
In drivers/cpuidle/cpuidle-psci.c (c15a4b6c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
```
```
In drivers/clocksource/renesas-ostm.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/clocksource/dw_apb_timer.c (c0c48e18)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_init
```
```
In drivers/clocksource/timer-armada-370-xp.c (c0c49648)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_starting_cpu
```
```
In drivers/clocksource/timer-orion.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/clocksource/timer-tegra.c (c15abd70)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/timer-tegra.c:tegra_timer_setup
```
```
In drivers/clocksource/exynos_mct.c (c0c4a298)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:exynos4_mct_starting_cpu
```
```
In drivers/clocksource/timer-qcom.c (c0c4a618)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/timer-qcom.c:msm_local_timer_starting_cpu
```
```
In drivers/clocksource/timer-owl.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/clocksource/timer-npcm7xx.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (c0c4b48c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
```
```
In drivers/clocksource/arm_global_timer.c (c0c4ba90)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:gt_starting_cpu
```
```
In drivers/clocksource/dummy_timer.c (c0c4bd10)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/dummy_timer.c:dummy_timer_starting_cpu
```
```
In drivers/clocksource/timer-imx-gpt.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/perf/arm-cci.c (c0c7b2a8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_cpumask_attr_show
```
```
In drivers/perf/arm-ccn.c (c0c7cbb8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cpumask_show
```
```
In drivers/perf/arm_pmu.c (c0c7ea20)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
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
In init/main.c (c000000000010620)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/powerpc/kernel/time.c (c00000000002b7cc)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:register_decrementer_clockevent
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037d34)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
```
```
In arch/powerpc/mm/numa.c (c0000000000a36ec)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
```
```
In kernel/cpu.c (c00000000013d5cc)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (c0000000013673f8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (c0000000001728c4)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (c000000000176e58)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (c00000000018b2d0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/rcu/tree.c (c0000000001edf38)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (c0000000002150b8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (c00000000021716c)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (c000000000217bf0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (c000000000259168)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (c000000000356bd0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:toggle_bp_slot
```
```
In drivers/base/topology.c (c00000000098b660)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
```
```
In drivers/cpufreq/cpufreq.c (c000000000c157a8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/clocksource/dummy_timer.c (c000000000c40a24)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/dummy_timer.c:dummy_timer_starting_cpu
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
In init/main.c (ffffffe0008c400a)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/riscv/kernel/smp.c (ffffffe0000b7ba4)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/riscv/kernel/smp.c:smp_send_reschedule
  - arch/riscv/kernel/smp.c:arch_send_call_function_single_ipi
```
```
In arch/riscv/mm/cacheflush.c (ffffffe0000ba082)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/riscv/mm/cacheflush.c:flush_icache_mm
```
```
In kernel/workqueue.c (ffffffe000005518)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffe0000df852)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffe0000e1f76)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffe0000ec39e)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/time/clockevents.c (ffffffe000139880)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffe00013a5d8)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/stop_machine.c (ffffffe00015d718)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe000495bd0)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask
```
```
In drivers/base/topology.c (ffffffe000583aac)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
```
```
In drivers/clocksource/timer-riscv.c (ffffffe00071e522)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/timer-riscv.c:riscv_timer_starting_cpu
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
In init/main.c (ffffffff81a66079)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff8101e5fc)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102c905)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065788)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067755)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067a76)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff828a94ac)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/cpu.c (ffffffff8109ba23)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff828b49d2)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810c2f9e)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810c8824)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810d72ee)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff8111b475)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81122d61)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff8113e63e)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8113f74a)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff8113f957)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8116c53b)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff812118c7)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8162cca5)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818685a7)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186c942)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff828fe811)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff828fe929)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81890881)
Location: include/linux/cpumask.h:879
Inline: True
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
In init/main.c (ffffffff81a230e9)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81055b08)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057ac5)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057de6)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff828a1558)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/cpu.c (ffffffff8108a453)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff828acb53)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810b17de)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810b7044)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810c5bde)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff8110c4e5)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff8111581d)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff8113115e)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8113233a)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff811326d7)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8115f70b)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff81204657)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81831257)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835462)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff828f6347)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff828f645f)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81849a81)
Location: include/linux/cpumask.h:879
Inline: True
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
In init/main.c (ffffffff81ad2489)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff8101e5ac)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102c765)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065c38)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067c05)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067f26)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff828bc3ab)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/cpu.c (ffffffff8109b9d3)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff828c78d1)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810c24ee)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810c7d54)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810d3f2e)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff81119365)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff81120c51)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff8113c35e)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8113d46a)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff8113d807)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff8116a30b)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120f667)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8165adb5)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b9337)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bd6d2)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff82913a40)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff82913b58)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff818e42e1)
Location: include/linux/cpumask.h:879
Inline: True
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
In init/main.c (ffffffff81ade974)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - init/main.c:rest_init
```
```
In arch/x86/xen/time.c (ffffffff8101e800)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
```
In arch/x86/xen/smp.c (ffffffff8102d555)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81067218)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810691e5)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810695e6)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/hpet.c (ffffffff828bf503)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098c59)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099abd)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828cace2)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_register_clockevents
```
```
In kernel/cpu.c (ffffffff810a3643)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
```
```
In kernel/workqueue.c (ffffffff828ccc28)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810caaae)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/reboot.c (ffffffff810d0244)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810deece)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/irq/matrix.c (ffffffff81124a62)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/tree.c (ffffffff8112cf26)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clockevents.c (ffffffff81148e3e)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81149f5a)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a317)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/stop_machine.c (ffffffff81177a59)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/events/hw_breakpoint.c (ffffffff8121e577)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In drivers/xen/manage.c (0)
Location: include/linux/cpumask.h:879
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff816753a5)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d5617)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d99d6)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
```
In drivers/clocksource/i8253.c (ffffffff8291a707)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:clockevent_i8253_init
```
```
In drivers/clocksource/numachip.c (ffffffff8291a81f)
Location: include/linux/cpumask.h:879
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_each
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81900f41)
Location: include/linux/cpumask.h:879
Inline: True
```
</details>
</li>
</ul>

## Differences
