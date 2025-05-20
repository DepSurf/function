# Function: <code>bitmap_fill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104545c)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f72613)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff81068726)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain
```
```
In kernel/sched/core.c (ffffffff810af974)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff81f7ef49)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cpuset.c (ffffffff81f81fb4)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init_current_mems_allowed
```
```
In kernel/trace/trace.c (ffffffff8114d713)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff81208edd)
Location: include/linux/bitmap.h:191
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In drivers/dma/dmaengine.c (ffffffff81fa458d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816ae9b1)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/ipv4/devinet.c (ffffffff81791abe)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff817a7dd4)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/addrconf.c (ffffffff817ca62f)
Location: include/linux/bitmap.h:191
Inline: True
```
**Symbols:**

```
ffffffff81208edd-ffffffff81208f0c: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045517)
Location: include/linux/bitmap.h:201
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9ae30)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff81068426)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain
```
```
In kernel/sched/core.c (ffffffff810b217a)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff81fa7fa8)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cpuset.c (ffffffff81fab66f)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff81155f2b)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff8122ebdc)
Location: include/linux/bitmap.h:201
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In drivers/dma/dmaengine.c (ffffffff81fd0aea)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81710260)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:201
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817ffffa)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff818905aa)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81837832)
Location: include/linux/bitmap.h:201
Inline: True
```
**Symbols:**

```
ffffffff8122ebdc-ffffffff8122ec11: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047127)
Location: include/linux/bitmap.h:201
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd6300)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff8106c079)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain
```
```
In kernel/sched/core.c (ffffffff810b8569)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff81fe3ddb)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cpuset.c (ffffffff811aeab6)
Location: include/linux/bitmap.h:201
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff81160686)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff81240f0e)
Location: include/linux/bitmap.h:201
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In drivers/dma/dmaengine.c (ffffffff8200e462)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8174224b)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:201
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81830f5a)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff818c4bc4)
Location: include/linux/bitmap.h:201
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81869322)
Location: include/linux/bitmap.h:201
Inline: True
```
**Symbols:**

```
ffffffff811aeab6-ffffffff811aeaeb: bitmap_fill (STB_LOCAL)
ffffffff81240f0e-ffffffff81240f43: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810469b7)
Location: include/linux/bitmap.h:200
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b700b)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff8106b489)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain
```
```
In kernel/irq/irqdesc.c (ffffffff820c48de)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81130a26)
Location: include/linux/bitmap.h:200
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff81163a76)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff811e4b82)
Location: include/linux/bitmap.h:200
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff8149c7e3)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
```
In drivers/dma/dmaengine.c (ffffffff820effb0)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817608eb)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:200
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81852205)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81868d8b)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81890090)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff818f2b53)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81130a26-ffffffff81130a5b: bitmap_fill (STB_LOCAL)
ffffffff811e4b82-ffffffff811e4bb7: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a408)
Location: include/linux/bitmap.h:210
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff826ccb77)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d974)
Location: include/linux/bitmap.h:210
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811709f6)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff826d9ada)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff814dacc7)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/dma/dmaengine.c (ffffffff826f97a1)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d68bb)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:210
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818d2011)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff818e92cb)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff8191162d)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff81978fa4)
Location: include/linux/bitmap.h:210
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff8113d974-ffffffff8113d9a9: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104cac8)
Location: include/linux/bitmap.h:212
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff826f6d51)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c234)
Location: include/linux/bitmap.h:212
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8117fb04)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff82703fd7)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff815092ce)
Location: include/linux/bitmap.h:212
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff82723a71)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8181f5a6)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:212
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8192852e)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff8193ed92)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81968a3e)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff819d5826)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff8114c234-ffffffff8114c247: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff828adc7d)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81158e64)
Location: include/linux/bitmap.h:221
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8118d474)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff828bb703)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff8151dc5e)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184b446)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81957981)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff8196f654)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff8199e375)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff81a0da56)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a181f7)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81158e64-ffffffff81158e77: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff828c6633)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff811655b7)
Location: include/linux/bitmap.h:221
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8119ad8b)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff828d2bc9)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff8154bd6e)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188e506)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819bc308)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff819d8da5)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81a0a401)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff81a7d408)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a87ddf)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff811655b7-ffffffff811655ca: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff828cec60)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff811714a7)
Location: include/linux/bitmap.h:225
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811a6c58)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff828db03b)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff8156bbf2)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c0696)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f3007)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a0fb15)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81a410b1)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff81ab473e)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81abf07f)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff811714a7-ffffffff811714ba: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitmap.h:241
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff82cf0041)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/cgroup/cpuset.c (ffffffff811831b7)
Location: include/linux/bitmap.h:241
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811bf85f)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff82cf907f)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In lib/radix-tree.c (ffffffff815ef091)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff815fb421)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_expand
```
```
In drivers/gpio/gpiolib.c (ffffffff8160cf86)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:241
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819925e6)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitmap.h:241
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a87a37)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/devinet.c (ffffffff81ae19f5)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81b00c55)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81b36b7e)
Location: include/linux/bitmap.h:241
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff811831b7-ffffffff811831ca: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff82fdca2c)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/cgroup/cpuset.c (ffffffff81be47ec)
Location: include/linux/bitmap.h:239
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/seccomp.c (ffffffff811a384a)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811bd488)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff82fe5d78)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In fs/iomap/buffered-io.c (ffffffff813bcc6a)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In lib/radix-tree.c (ffffffff816137e1)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff8161fa21)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_expand
```
```
In drivers/gpio/gpiolib.c (ffffffff81633d56)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819957f6)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a913be)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/devinet.c (ffffffff81aee895)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81b0ed35)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81b458ae)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81be47ec-ffffffff81be47ff: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052c91)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/irq/irqdesc.c (ffffffff831e780e)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81bd6615)
Location: include/linux/bitmap.h:239
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/seccomp.c (ffffffff811a446a)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811bcf88)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff831f0856)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In fs/iomap/buffered-io.c (ffffffff813c3d7f)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In lib/radix-tree.c (ffffffff815f6e7b)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff816031a1)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_create
```
```
In drivers/gpio/gpiolib.c (ffffffff816178f6)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197a666)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a7abb0)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/devinet.c (ffffffff81ad9f8d)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81afca35)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81b335f1)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81bd6615-ffffffff81bd6628: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b191)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff832cb900)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81cb3245)
Location: include/linux/bitmap.h:245
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/seccomp.c (ffffffff811cdc9f)
Location: include/linux/bitmap.h:245
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811e7a40)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff832d61e1)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In fs/iomap/buffered-io.c (ffffffff81413026)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In lib/radix-tree.c (ffffffff8166451b)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff8167167d)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_create
```
```
In drivers/gpio/gpiolib.c (ffffffff81686b76)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:245
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a23686)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitmap.h:245
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81b34fce)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/devinet.c (ffffffff81b990cd)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81bbe1b7)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81bf9c61)
Location: include/linux/bitmap.h:245
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81cb3245-ffffffff81cb3258: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067c07)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff8347f0aa)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81e6404a)
Location: include/linux/bitmap.h:244
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/seccomp.c (ffffffff81201a2d)
Location: include/linux/bitmap.h:244
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8121cc1f)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/watch_queue.c (ffffffff812edac9)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/percpu.c (ffffffff8348abff)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In fs/iomap/buffered-io.c (ffffffff81489175)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In lib/radix-tree.c (ffffffff8177e840)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff8178c0ee)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_create
```
```
In drivers/gpio/gpiolib.c (ffffffff817a3a06)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (ffffffff834b0586)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8c98b)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/ethtool/ioctl.c (ffffffff81cb97a9)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/ethtool/bitset.c (ffffffff81cc079f)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/devinet.c (ffffffff81d2afe9)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81d530d6)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81d9303e)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/mptcp/pm.c (ffffffff81e2d7c6)
Location: include/linux/bitmap.h:244
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
```
**Symbols:**

```
ffffffff81e4ac5a-ffffffff81e4ac6a: bitmap_fill.part.0 (STB_LOCAL)
ffffffff81e6404a-ffffffff81e6406f: bitmap_fill (STB_LOCAL)
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077557)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff83eab1ab)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/cgroup/cpuset.c (ffffffff83eb146f)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/seccomp.c (ffffffff812497fd)
Location: include/linux/bitmap.h:250
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8126753f)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/watch_queue.c (ffffffff81357eb9)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/percpu.c (ffffffff83ebb730)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In fs/iomap/buffered-io.c (ffffffff8151cdd5)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/gpio/gpiolib.c (ffffffff818bb2a6)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (ffffffff83eea045)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c3eb)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/ethtool/bitset.c (ffffffff81e7f3f8)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/devinet.c (ffffffff81ef2c04)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff81f1c3f4)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81f617d5)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/mptcp/pm.c (ffffffff82005d26)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
```
```
In lib/radix-tree.c (ffffffff8203b490)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff820486a8)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_create
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810797b7)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff836d016b)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/cgroup/cpuset.c (ffffffff836d640f)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/seccomp.c (ffffffff81260bc4)
Location: include/linux/bitmap.h:250
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8127eae1)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/bpf/cpumask.c (ffffffff8135d895)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_setall
```
```
In kernel/watch_queue.c (ffffffff81389749)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/percpu.c (ffffffff836e3d60)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In fs/iomap/buffered-io.c (ffffffff81554f7f)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/gpio/gpiolib.c (ffffffff818fe3a6)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (ffffffff8370fa35)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9567b)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/ethtool/bitset.c (ffffffff81edb9e8)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/devinet.c (ffffffff81f527b2)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff81f7bed4)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81fc1607)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/mptcp/pm.c (ffffffff820820a1)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
```
```
In lib/radix-tree.c (ffffffff820b9970)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff820c6ec5)
Location: include/linux/bitmap.h:250
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_create
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81081037)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff8390158b)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/rcu/tree.c (ffffffff839020a3)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8390883f)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/seccomp.c (ffffffff8127ad94)
Location: include/linux/bitmap.h:227
Inline: True
```
```
In kernel/trace/trace.c (ffffffff812995a8)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/bpf/cpumask.c (ffffffff81386635)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_setall
```
```
In kernel/watch_queue.c (ffffffff813b3199)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/percpu.c (ffffffff839165f0)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff81945ac6)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (ffffffff83943205)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4d16b)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/ethtool/bitset.c (ffffffff81f9f7af)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/devinet.c (ffffffff82018a94)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff820425c4)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff8208eb3f)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/mptcp/pm.c (ffffffff82157691)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
```
```
In lib/radix-tree.c (ffffffff82194280)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff821a1845)
Location: include/linux/bitmap.h:227
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/alternative.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In arch/arm64/mm/context.c (ffff8000100affc4)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In kernel/irq/irqdesc.c (ffff8000114465dc)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffff8000101e50b0)
Location: include/linux/bitmap.h:225
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffff800010223ad8)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffff8000114539b8)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ad578)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffff8000106bef5c)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1e444)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In drivers/cpufreq/cpufreq-dt.c (ffff800010b264cc)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
```
In drivers/perf/arm_pmu_platform.c (ffff800010b95bac)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca93ac)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffff800010cc97e4)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffff800010d02b64)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffff800010d8ec54)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffff800010d9a23c)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffff8000101e50b0-ffff8000101e50d8: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mm/context.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In kernel/irq/irqdesc.c (c1520c4c)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (c04259d4)
Location: include/linux/bitmap.h:225
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (c0461310)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (c152e71c)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084fe08)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask
```
```
In drivers/gpio/gpiolib.c (c085dc54)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c0bfaaf0)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In drivers/cpufreq/cpufreq-dt.c (c0c00330)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
```
In drivers/perf/arm_pmu_platform.c (c0c7f108)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/ipv4/devinet.c (c0db59b8)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (c0dd4f0c)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (c0e09834)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (c0e893a4)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (c0e97014)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
c04259d4-c04259ec: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/numa.c (c000000001357c50)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:shared_proc_topology_init
```
```
In arch/powerpc/mm/slice.c (c0000000000a511c)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - arch/powerpc/mm/slice.c:slice_init_new_context_exec
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011c784)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In kernel/irq/irqdesc.c (c00000000136b3fc)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (c000000000255438)
Location: include/linux/bitmap.h:225
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (c0000000002a8708)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (c00000000137bf60)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (c00000000083a960)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c000000000c13f64)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/ipv4/devinet.c (c000000000dbe510)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (c000000000de7794)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (c000000000e2a54c)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (c000000000ed1a10)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (c000000000ee07a0)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
c000000000255438-c000000000255478: bitmap_fill (STB_LOCAL)
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
In arch/riscv/mm/cacheflush.c (ffffffe0000ba02a)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - arch/riscv/mm/cacheflush.c:flush_icache_mm
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffe00000c81c)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
```
```
In kernel/trace/trace.c (ffffffe00017f12e)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffe000012d22)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a4e58)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe000803e78)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffe00081d2a2)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffe00084bec4)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffe0008b7510)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffe0008c1b3c)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff828b7958)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81169ac7)
Location: include/linux/bitmap.h:225
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8119f278)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff828c3eef)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff815613b2)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81864db6)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81992da7)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff819af535)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff819e0741)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff81a5358e)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a5decf)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81169ac7-ffffffff81169ada: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff828afbd8)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/rcu/tree.c (ffffffff81115b29)
Location: include/linux/bitmap.h:225
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nocb_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8115ccc7)
Location: include/linux/bitmap.h:225
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811922c8)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff828bc614)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff81552202)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182da66)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8194c867)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff8196bb65)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff8199d501)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff81a1068e)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a1af9f)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81115b29-ffffffff81115b3c: bitmap_fill (STB_LOCAL)
ffffffff8115ccc7-ffffffff8115ccda: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff828ca894)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81167897)
Location: include/linux/bitmap.h:225
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8119d048)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff828d6c6f)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff8155ff22)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b5b46)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819fd647)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a19dd5)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81a4b1c1)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff81abf97e)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81aca2bf)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81167897-ffffffff811678aa: bitmap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_fill(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff828cfc8d)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81174f67)
Location: include/linux/bitmap.h:225
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811aace8)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In mm/percpu.c (ffffffff828dc090)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
```
In drivers/gpio/gpiolib.c (ffffffff81579d92)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d1df6)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:225
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a079d7)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a24c05)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81a5711b)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In lib/radix-tree.c (ffffffff81acbe4e)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81ad688f)
Location: include/linux/bitmap.h:225
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81174f67-ffffffff81174f7a: bitmap_fill (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
