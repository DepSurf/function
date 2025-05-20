# Function: <code>__percpu_read_32</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/sched/fair.c (ffff800010143444)
Location: arch/arm64/include/asm/percpu.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/printk/printk_safe.c (ffff800010176ff4)
Location: arch/arm64/include/asm/percpu.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:printk_nmi_direct_enter
```
```
In mm/page_alloc.c (ffff80001031995c)
Location: arch/arm64/include/asm/percpu.h:110
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
```
```
In fs/eventfd.c (ffff8000103f6144)
Location: arch/arm64/include/asm/percpu.h:110
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_signal
```
```
In fs/aio.c (ffff8000103fe904)
Location: arch/arm64/include/asm/percpu.h:110
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In lib/sbitmap.c (ffff80001066a1cc)
Location: arch/arm64/include/asm/percpu.h:110
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
```
```
In drivers/nvdimm/region_devs.c (ffff800010957a34)
Location: arch/arm64/include/asm/percpu.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
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
