# Function: <code>schedule_delayed_work_on</code>

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
In arch/x86/kernel/hpet.c (ffffffff81062662)
Location: include/linux/workqueue.h:571
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_notify
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
In arch/x86/kernel/hpet.c (ffffffff81062489)
Location: include/linux/workqueue.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff810654f9)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104476d)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
```
```
In arch/x86/kernel/hpet.c (ffffffff81064423)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047f3d)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
```
```
In arch/x86/kernel/hpet.c (ffffffff810685a1)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a7c4)
Location: include/linux/workqueue.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
```
```
In arch/x86/kernel/hpet.c (ffffffff8106b0f1)
Location: include/linux/workqueue.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ab44)
Location: include/linux/workqueue.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
```
In arch/x86/kernel/hpet.c (ffffffff81070e81)
Location: include/linux/workqueue.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105de48)
Location: include/linux/workqueue.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e708)
Location: include/linux/workqueue.h:593
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057901)
Location: include/linux/workqueue.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81064218)
Location: include/linux/workqueue.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In kernel/rcu/tree.c (ffffffff82cf0f81)
Location: include/linux/workqueue.h:609
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056681)
Location: include/linux/workqueue.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062618)
Location: include/linux/workqueue.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In kernel/rcu/tree.c (ffffffff82fdd966)
Location: include/linux/workqueue.h:609
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062d86)
Location: include/linux/workqueue.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
```
In kernel/rcu/tree.c (ffffffff831e8458)
Location: include/linux/workqueue.h:609
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81946e97)
Location: include/linux/workqueue.h:609
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106cc13)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
```
In kernel/rcu/tree.c (ffffffff832cc85b)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ebac4)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
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
In arch/x86/kernel/cpu/intel.c (ffffffff81062fc4)
Location: include/linux/workqueue.h:652
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8107a0d3)
Location: include/linux/workqueue.h:652
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
```
In kernel/rcu/tree.c (ffffffff83480210)
Location: include/linux/workqueue.h:652
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b51af3)
Location: include/linux/workqueue.h:652
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
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
In arch/x86/kernel/cpu/intel.c (ffffffff81071e2d)
Location: include/linux/workqueue.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108b1d3)
Location: include/linux/workqueue.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81ce9bf6)
Location: include/linux/workqueue.h:653
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
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
In arch/x86/kernel/cpu/intel.c (ffffffff81073a1d)
Location: include/linux/workqueue.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108e273)
Location: include/linux/workqueue.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52799)
Location: include/linux/workqueue.h:656
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
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
In arch/x86/kernel/cpu/intel.c (ffffffff8107af5d)
Location: include/linux/workqueue.h:660
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81095603)
Location: include/linux/workqueue.h:660
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e094f9)
Location: include/linux/workqueue.h:660
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/rtasd.c (c00000000134da84)
Location: include/linux/workqueue.h:593
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan_init
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eb0ac)
Location: include/linux/workqueue.h:593
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:dtl_worker_online
  - arch/powerpc/platforms/pseries/lpar.c:process_dtl_buffer
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e288)
Location: include/linux/workqueue.h:593
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e5b8)
Location: include/linux/workqueue.h:593
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e6b8)
Location: include/linux/workqueue.h:593
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fbf8)
Location: include/linux/workqueue.h:593
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
</details>
</li>
</ul>

## Differences
