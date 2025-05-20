# Function: <code>prefetch</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102d705)
Location: arch/x86/include/asm/processor.h:673
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
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
In arch/x86/kernel/process_64.c (ffffffff8102c55b)
Location: arch/x86/include/asm/processor.h:684
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
</details>
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
In kernel/sched/core.c (ffff80001013bea0)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
```
```
In kernel/bpf/devmap.c (ffff8000102864f8)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In mm/page_alloc.c (ffff800010314a70)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/slub.c (ffff80001034c9d4)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In fs/d_path.c (ffff8000103d1c44)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In fs/direct-io.c (ffff8000103e57b8)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In block/blk-mq.c (ffff8000105ed830)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
```
```
In drivers/soc/fsl/qbman/bman.c (ffff800010811ac8)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_acquire
  - drivers/soc/fsl/qbman/bman.c:bman_acquire
  - drivers/soc/fsl/qbman/bman.c:bman_release
  - drivers/soc/fsl/qbman/bman.c:bm_shutdown_pool
  - drivers/soc/fsl/qbman/bman.c:bm_shutdown_pool
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816f24)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:_qm_dqrr_consume_and_match
  - drivers/soc/fsl/qbman/qman.c:_qm_dqrr_consume_and_match
  - drivers/soc/fsl/qbman/qman.c:_qm_mr_consume_and_match_verb
  - drivers/soc/fsl/qbman/qman.c:_qm_mr_consume_and_match_verb
  - drivers/soc/fsl/qbman/qman.c:qman_enqueue
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq_np
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq_np
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq
  - drivers/soc/fsl/qbman/qman.c:qman_oos_fq
  - drivers/soc/fsl/qbman/qman.c:qman_oos_fq
  - drivers/soc/fsl/qbman/qman.c:qman_retire_fq
  - drivers/soc/fsl/qbman/qman.c:qman_retire_fq
  - drivers/soc/fsl/qbman/qman.c:qman_schedule_fq
  - drivers/soc/fsl/qbman/qman.c:qman_schedule_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qman_p_poll_dqrr
  - drivers/soc/fsl/qbman/qman.c:qm_mr_process_task
  - drivers/soc/fsl/qbman/qman.c:qm_congestion_task
  - drivers/soc/fsl/qbman/qman.c:qm_congestion_task
  - drivers/soc/fsl/qbman/qman.c:drain_mr_fqrni
  - drivers/soc/fsl/qbman/qman.c:drain_mr_fqrni
  - drivers/soc/fsl/qbman/qman.c:portal_isr
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6e10)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In net/core/sock.c (ffff800010badd28)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/ipv4/tcp_input.c (ffff800010c7d634)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/udp.c (ffff800010c9d650)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
```
In net/ipv6/udp.c (ffff800010d26374)
Location: arch/arm64/include/asm/processor.h:264
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
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
In kernel/sched/core.c (c038b60c)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
```
```
In kernel/bpf/devmap.c (c04b6734)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In mm/page_alloc.c (c052ed34)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/slub.c (c05502b8)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In fs/d_path.c (c05ac9a8)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
```
```
In fs/direct-io.c (c05bd6d4)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In block/blk-mq.c (c079b14c)
Location: arch/arm/include/asm/processor.h:121
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acbc10)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/usb/musb/musb_core.c (c0b658a8)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_default_write_fifo
```
```
In net/core/sock.c (c0ccb830)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/ipv4/tcp_input.c (c0d8c4c4)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/udp.c (c0dab110)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
```
In net/ipv6/udp.c (c0e299b8)
Location: arch/arm/include/asm/processor.h:121
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
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
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008dc2c)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache
```
```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090e6c)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:update_mmu_cache_pmd
```
```
In arch/powerpc/lib/sstep.c (c0000000000b201c)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - arch/powerpc/lib/sstep.c:emulate_step
```
```
In kernel/sched/core.c (c000000000189da4)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
```
```
In kernel/bpf/devmap.c (c0000000003311c4)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In mm/page_alloc.c (c0000000003e6234)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/slub.c (c00000000042c88c)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In fs/d_path.c (c0000000004d49a8)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In fs/direct-io.c (c0000000004ebc00)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In block/blk-mq.c (c000000000784f00)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
```
```
In net/core/sock.c (c000000000c83718)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/ipv4/tcp_input.c (c000000000d87404)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/udp.c (c000000000daeebc)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
```
In net/ipv6/udp.c (c000000000e55f64)
Location: arch/powerpc/include/asm/processor.h:377
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
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
