# Function: <code>request_percpu_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int request_percpu_irq(unsigned int irq, irq_handler_t handler, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dcf40)
Location: kernel/irq/manage.c:1886
Inline: False
```
**Symbols:**

```
ffffffff810dcf40-ffffffff810dd04c: request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int request_percpu_irq(unsigned int irq, irq_handler_t handler, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e2690)
Location: kernel/irq/manage.c:1971
Inline: False
```
**Symbols:**

```
ffffffff810e2690-ffffffff810e27a7: request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int request_percpu_irq(unsigned int irq, irq_handler_t handler, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e8fb0)
Location: kernel/irq/manage.c:1971
Inline: False
```
**Symbols:**

```
ffffffff810e8fb0-ffffffff810e90c4: request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7b92)
Location: include/linux/interrupt.h:181
Inline: True
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
In drivers/clocksource/hyperv_timer.c (ffffffff81a55148)
Location: include/linux/interrupt.h:185
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
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
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4878)
Location: include/linux/interrupt.h:185
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
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
In drivers/clocksource/hyperv_timer.c (ffffffff81d6a0c8)
Location: include/linux/interrupt.h:185
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
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
In drivers/clocksource/hyperv_timer.c (ffffffff81dd5488)
Location: include/linux/interrupt.h:185
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
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
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d5d8)
Location: include/linux/interrupt.h:185
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
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
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100de434)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ed9dc)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
```
```
In arch/arm/xen/enlighten.c (ffff80001143a918)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_guest_init
```
```
In drivers/clocksource/timer-of.c (ffff8000114a7e6c)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_init
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a8d3c)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
```
```
In drivers/perf/arm_pmu.c (ffff800010b9553c)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
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
In arch/arm/kernel/smp_twd.c (c1505dd8)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
```
```
In drivers/clocksource/timer-of.c (c15aa44c)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_init
```
```
In drivers/clocksource/timer-armada-370-xp.c (c15ab510)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
```
```
In drivers/clocksource/exynos_mct.c (c15ac114)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:mct_init_dt
```
```
In drivers/clocksource/timer-qcom.c (c15ac58c)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
```
```
In drivers/clocksource/arm_arch_timer.c (c15ad1c4)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
```
```
In drivers/clocksource/arm_global_timer.c (c15ad9a4)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
```
```
In drivers/perf/arm_pmu.c (c0c7eadc)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-of.c (ffffffe00003a2ea)
Location: include/linux/interrupt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
