# Function: <code>ktime_before</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178b4e6)
Location: include/linux/ktime.h:137
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
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
In kernel/time/hrtimer.c (ffffffff8111667e)
Location: include/linux/ktime.h:137
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8165fe07)
Location: include/linux/ktime.h:137
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff817cd704)
Location: include/linux/ktime.h:137
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:137
Inline: True
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
In kernel/time/hrtimer.c (ffffffff81121cbe)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e457)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff817f47c9)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
Inline: True
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
In kernel/time/hrtimer.c (ffffffff8112c5fe)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816b5107)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff816f39e2)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff818357f2)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
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
In kernel/time/hrtimer.c (ffffffff8113861e)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816d7de7)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff81717de2)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff81866fc2)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
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
In kernel/time/hrtimer.c (ffffffff8114742e)
Location: include/linux/ktime.h:122
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8178c187)
Location: include/linux/ktime.h:122
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff817d399d)
Location: include/linux/ktime.h:122
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff8193a642)
Location: include/linux/ktime.h:122
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:122
Inline: True
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
In kernel/time/hrtimer.c (ffffffff8114393e)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff81154bac)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff817a2717)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff817e83fd)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff81940a42)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/md/md.c (ffffffff8196c6bb)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff81144aee)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff811560fc)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81785417)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff817cc994)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/rtc/interface.c (ffffffff81924182)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/md/md.c (ffffffff8195167b)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff81168349)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff8117adac)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8180bf4c)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff81856f81)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/rtc/interface.c (ffffffff819c71af)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/md/md.c (ffffffff819f6bbb)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff8119bd4c)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff811afd1c)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8194c51c)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff8199d3b4)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/rtc/interface.c (ffffffff81b28243)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/md/md.c (ffffffff81b55767)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff811da68c)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff811f075c)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab06cc)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff81b0ebd4)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/rtc/interface.c (ffffffff81cbbcc3)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/md/md.c (ffffffff81cee827)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff811eebbc)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff8120517c)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81afc51c)
Location: include/linux/ktime.h:123
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff81b5cc84)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/rtc/interface.c (ffffffff81d23573)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d5514f)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/md/md.c (ffffffff81d575a7)
Location: include/linux/ktime.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff81204d3c)
Location: include/linux/ktime.h:121
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff8121b84c)
Location: include/linux/ktime.h:121
Inline: True
```
```
In drivers/pmdomain/governor.c (ffffffff81aa4784)
Location: include/linux/ktime.h:121
Inline: True
Inline callers:
  - drivers/pmdomain/governor.c:cpu_power_down_ok
  - drivers/pmdomain/governor.c:_default_power_down_ok
  - drivers/pmdomain/governor.c:_default_power_down_ok
  - drivers/pmdomain/governor.c:_default_power_down_ok
  - drivers/pmdomain/governor.c:_default_power_down_ok
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81b4fb2c)
Location: include/linux/ktime.h:121
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c198a6)
Location: include/linux/ktime.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:timeline_fence_set_deadline
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc31ea)
Location: include/linux/ktime.h:121
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_fences
```
```
In drivers/rtc/interface.c (ffffffff81dd92d3)
Location: include/linux/ktime.h:121
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c01f)
Location: include/linux/ktime.h:121
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/md/md.c (ffffffff81e141e7)
Location: include/linux/ktime.h:121
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In virt/kvm/kvm_main.c (ffff8000100bb280)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_block
```
```
In kernel/time/hrtimer.c (ffff8000101a2248)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3214)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffff80001090ac34)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (ffff800010aa8a38)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56c5c)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
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
In kernel/time/hrtimer.c (c03ebf94)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/pci/controller/pci-tegra.c (c08ad1ac)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
```
```
In drivers/base/power/domain_governor.c (c09f449c)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (c0b875b0)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/firmware/arm_scmi/driver.c (c0c38090)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
```
```
In drivers/firmware/tegra/bpmp.c (c0c42064)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
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
In kernel/time/hrtimer.c (c0000000002036fc)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/base/power/domain_governor.c (c0000000009ab2f4)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (c000000000b8a244)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
Inline: True
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
In kernel/time/hrtimer.c (ffffffe00012f3c8)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
```
```
In drivers/rtc/interface.c (ffffffe0006b421a)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
Inline: True
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
In kernel/time/hrtimer.c (ffffffff81130dce)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8169d837)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff816de112)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff81819c72)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
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
In kernel/time/hrtimer.c (ffffffff8112383e)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b227)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff816b8772)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff817e1362)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
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
In kernel/time/hrtimer.c (ffffffff8112eaee)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816cbaa7)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff8170baa2)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff8185b152)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
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
In kernel/time/hrtimer.c (ffffffff8113b4ee)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816e5f77)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff81726492)
Location: include/linux/ktime.h:140
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff818762a6)
Location: include/linux/ktime.h:140
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:140
Inline: True
```
</details>
</li>
</ul>

## Differences
