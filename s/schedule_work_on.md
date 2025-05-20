# Function: <code>schedule_work_on</code>

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
In kernel/workqueue.c (ffffffff8109b059)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff810d657a)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff811486d3)
Location: include/linux/workqueue.h:512
Inline: True
```
```
In mm/swap.c (ffffffff8119e2d8)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/memcontrol.c (ffffffff811fbd9d)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff81201af9)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
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
In kernel/workqueue.c (ffffffff8109e659)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff810db3fa)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8115055e)
Location: include/linux/workqueue.h:513
Inline: True
```
```
In mm/memcontrol.c (ffffffff8121f23a)
Location: include/linux/workqueue.h:513
Inline: True
```
```
In mm/memory-failure.c (ffffffff81226239)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81716d46)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810a3239)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff810e1ecc)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8115b5f9)
Location: include/linux/workqueue.h:527
Inline: True
```
```
In mm/memcontrol.c (ffffffff8123174d)
Location: include/linux/workqueue.h:527
Inline: True
```
```
In mm/memory-failure.c (ffffffff81238809)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81748b26)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810a050a)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff810e100b)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e4e7)
Location: include/linux/workqueue.h:529
Inline: True
```
```
In mm/memcontrol.c (ffffffff8123cf7f)
Location: include/linux/workqueue.h:529
Inline: True
```
```
In mm/memory-failure.c (ffffffff812442d9)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817671e6)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810a6aaa)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff810e92db)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b4f8)
Location: include/linux/workqueue.h:529
Inline: True
```
```
In mm/memcontrol.c (ffffffff8125caa8)
Location: include/linux/workqueue.h:529
Inline: True
```
```
In mm/memory-failure.c (ffffffff81264159)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dd106)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f9b7d)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
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
In kernel/workqueue.c (ffffffff810ad76d)
Location: include/linux/workqueue.h:552
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff810f160b)
Location: include/linux/workqueue.h:552
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8117a3b6)
Location: include/linux/workqueue.h:552
Inline: True
```
```
In mm/memcontrol.c (ffffffff8128074d)
Location: include/linux/workqueue.h:552
Inline: True
```
```
In mm/memory-failure.c (ffffffff812883c6)
Location: include/linux/workqueue.h:552
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825d8b)
Location: include/linux/workqueue.h:552
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
```
```
In net/xfrm/xfrm_policy.c (ffffffff819505dd)
Location: include/linux/workqueue.h:552
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
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
In kernel/workqueue.c (ffffffff810b6a5d)
Location: include/linux/workqueue.h:552
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff810fcc9b)
Location: include/linux/workqueue.h:552
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff81187386)
Location: include/linux/workqueue.h:552
Inline: True
```
```
In mm/memcontrol.c (ffffffff812952fd)
Location: include/linux/workqueue.h:552
Inline: True
```
```
In mm/memory-failure.c (ffffffff8129d308)
Location: include/linux/workqueue.h:552
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81851c63)
Location: include/linux/workqueue.h:552
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810bcea9)
Location: include/linux/workqueue.h:530
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff8110539c)
Location: include/linux/workqueue.h:530
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8119477b)
Location: include/linux/workqueue.h:530
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b12bd)
Location: include/linux/workqueue.h:530
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b8405)
Location: include/linux/workqueue.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81895199)
Location: include/linux/workqueue.h:530
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810c2b29)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff8111171c)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff811a023b)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c2d0e)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memory-failure.c (ffffffff812ca2e5)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c71b9)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810ca2ac)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff8111c7ec)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff811b892f)
Location: include/linux/workqueue.h:547
Inline: True
```
```
In mm/memcontrol.c (ffffffff812f8845)
Location: include/linux/workqueue.h:547
Inline: True
```
```
In mm/memory-failure.c (ffffffff81300075)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff819993f9)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810c53dc)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff8111714c)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff811b637f)
Location: include/linux/workqueue.h:547
Inline: True
```
```
In mm/memcontrol.c (ffffffff81304669)
Location: include/linux/workqueue.h:547
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130c3b5)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c4d9)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810c6ccc)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff8111786b)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff811b64cf)
Location: include/linux/workqueue.h:547
Inline: True
```
```
In mm/memcontrol.c (ffffffff8130b669)
Location: include/linux/workqueue.h:547
Inline: True
```
```
In mm/memory-failure.c (ffffffff81312b15)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff819811a9)
Location: include/linux/workqueue.h:547
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810d997c)
Location: include/linux/workqueue.h:541
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff81137bcb)
Location: include/linux/workqueue.h:541
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff811e06bf)
Location: include/linux/workqueue.h:541
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6600)
Location: include/linux/workqueue.h:541
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_cpu_init
```
```
In mm/slub.c (ffffffff81333188)
Location: include/linux/workqueue.h:541
Inline: True
Inline callers:
  - mm/slub.c:flush_all_cpus_locked
```
```
In mm/memcontrol.c (ffffffff81356914)
Location: include/linux/workqueue.h:541
Inline: True
```
```
In mm/memory-failure.c (ffffffff8135e555)
Location: include/linux/workqueue.h:541
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a419)
Location: include/linux/workqueue.h:541
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810f3669)
Location: include/linux/workqueue.h:542
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff8115a22b)
Location: include/linux/workqueue.h:542
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff81214b34)
Location: include/linux/workqueue.h:542
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace_hwlat.c (ffffffff8122ff70)
Location: include/linux/workqueue.h:542
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_cpu_init
```
```
In mm/slub.c (ffffffff813a4971)
Location: include/linux/workqueue.h:542
Inline: True
Inline callers:
  - mm/slub.c:flush_all_cpus_locked
```
```
In mm/memcontrol.c (ffffffff813cf809)
Location: include/linux/workqueue.h:542
Inline: True
```
```
In mm/memory-failure.c (ffffffff813d8dec)
Location: include/linux/workqueue.h:542
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b94748)
Location: include/linux/workqueue.h:542
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff811150a9)
Location: include/linux/workqueue.h:543
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff8118c52b)
Location: include/linux/workqueue.h:543
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff81260278)
Location: include/linux/workqueue.h:543
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127c180)
Location: include/linux/workqueue.h:543
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_cpu_init
```
```
In mm/memcontrol.c (ffffffff81454b1b)
Location: include/linux/workqueue.h:543
Inline: True
```
```
In mm/memory-failure.c (ffffffff8145e8c4)
Location: include/linux/workqueue.h:543
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d34b08)
Location: include/linux/workqueue.h:543
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff81121079)
Location: include/linux/workqueue.h:546
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff8119dc4b)
Location: include/linux/workqueue.h:546
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8127750f)
Location: include/linux/workqueue.h:546
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace_hwlat.c (ffffffff81293ca0)
Location: include/linux/workqueue.h:546
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_cpu_init
```
```
In kernel/trace/trace_osnoise.c (ffffffff81295e10)
Location: include/linux/workqueue.h:546
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpu_init
```
```
In mm/memcontrol.c (ffffffff8148a935)
Location: include/linux/workqueue.h:546
Inline: True
```
```
In mm/memory-failure.c (ffffffff81494714)
Location: include/linux/workqueue.h:546
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9de78)
Location: include/linux/workqueue.h:546
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff8112b829)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe_key
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff811acdbb)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff81291f7e)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace_hwlat.c (ffffffff812af300)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_cpu_init
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b1480)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpu_init
```
```
In mm/memcontrol.c (ffffffff814ba1f5)
Location: include/linux/workqueue.h:588
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c4024)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55bf8)
Location: include/linux/workqueue.h:588
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffff80001011f8ec)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffff800010171bd4)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffff800010219c74)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memcontrol.c (ffff8000103656f4)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memory-failure.c (ffff80001036e44c)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b2555c)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (c03738e8)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (c03c4550)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (c0457f24)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memcontrol.c (c055717c)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff258)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (c000000000169c78)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (c0000000001ca414)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (c00000000029bb0c)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memcontrol.c (c0000000004521fc)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memory-failure.c (c00000000045e2b4)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (c000000000c1a44c)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffe0000d8806)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffe00010dea4)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffe000178cfc)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memcontrol.c (ffffffe000243d9e)
Location: include/linux/workqueue.h:534
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
In kernel/workqueue.c (ffffffff810bce99)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff81109cfc)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8119885b)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memcontrol.c (ffffffff812bb2ee)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c28c5)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186b8d9)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810ab6d9)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff810fabdc)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8118bd6b)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ac45e)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b3915)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81834589)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184f19b)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_on_msg_dpc
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
In kernel/workqueue.c (ffffffff810bc3f9)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff81107bec)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff8119662b)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b90fe)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c06d5)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bc669)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
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
In kernel/workqueue.c (ffffffff810c4729)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/power/poweroff.c (ffffffff81112f9c)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/trace/ring_buffer.c (ffffffff811a423b)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c974b)
Location: include/linux/workqueue.h:534
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d117c)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8959)
Location: include/linux/workqueue.h:534
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
```
</details>
</li>
</ul>

## Differences
