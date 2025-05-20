# Function: <code>__request_percpu_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e84d0)
Location: kernel/irq/manage.c:2018
Inline: False
```
**Symbols:**

```
ffffffff810e84d0-ffffffff810e85c9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f08a0)
Location: kernel/irq/manage.c:2075
Inline: False
```
**Symbols:**

```
ffffffff810f08a0-ffffffff810f0999: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f8c60)
Location: kernel/irq/manage.c:2119
Inline: False
```
**Symbols:**

```
ffffffff810f8c60-ffffffff810f8d59: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81104400)
Location: kernel/irq/manage.c:2135
Inline: False
```
**Symbols:**

```
ffffffff81104400-ffffffff811044f9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110cef0)
Location: kernel/irq/manage.c:2429
Inline: False
```
**Symbols:**

```
ffffffff8110cef0-ffffffff8110cff9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811192d0)
Location: kernel/irq/manage.c:2421
Inline: False
```
**Symbols:**

```
ffffffff811192d0-ffffffff811193d9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81124b70)
Location: kernel/irq/manage.c:2460
Inline: False
```
**Symbols:**

```
ffffffff81124b70-ffffffff81124c79: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811209d0)
Location: kernel/irq/manage.c:2530
Inline: False
```
**Symbols:**

```
ffffffff811209d0-ffffffff81120ad9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81120ca0)
Location: kernel/irq/manage.c:2537
Inline: False
```
**Symbols:**

```
ffffffff81120ca0-ffffffff81120da9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81141220)
Location: kernel/irq/manage.c:2566
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81141220-ffffffff81141329: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81164c30)
Location: kernel/irq/manage.c:2600
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81164c30-ffffffff81164d38: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81198a50)
Location: kernel/irq/manage.c:2592
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81198a50-ffffffff81198b58: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811aa730)
Location: kernel/irq/manage.c:2598
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff811aa730-ffffffff811aa838: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ba280)
Location: kernel/irq/manage.c:2595
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff811ba280-ffffffff811ba3b7: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017bdf8)
Location: kernel/irq/manage.c:2421
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - arch/arm/xen/enlighten.c:xen_guest_init
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
**Symbols:**

```
ffff80001017bdf8-ffff80001017bf18: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cce8c)
Location: kernel/irq/manage.c:2421
Inline: False
Direct callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
**Symbols:**

```
c03cce8c-c03ccf84: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d68a0)
Location: kernel/irq/manage.c:2421
Inline: False
```
**Symbols:**

```
c0000000001d68a0-c0000000001d6a34: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe00011569c)
Location: kernel/irq/manage.c:2421
Inline: False
Direct callers:
  - drivers/clocksource/timer-of.c:timer_of_init
```
**Symbols:**

```
ffffffe00011569c-ffffffe000115790: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811118b0)
Location: kernel/irq/manage.c:2421
Inline: False
```
**Symbols:**

```
ffffffff811118b0-ffffffff811119b9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811025e0)
Location: kernel/irq/manage.c:2421
Inline: False
```
**Symbols:**

```
ffffffff811025e0-ffffffff811026e9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f7a0)
Location: kernel/irq/manage.c:2421
Inline: False
```
**Symbols:**

```
ffffffff8110f7a0-ffffffff8110f8a9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __request_percpu_irq(unsigned int irq, irq_handler_t handler, long unsigned int flags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111acd0)
Location: kernel/irq/manage.c:2421
Inline: False
```
**Symbols:**

```
ffffffff8111acd0-ffffffff8111add9: __request_percpu_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
