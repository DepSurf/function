# Function: <code>fls_long</code>

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
In kernel/printk/printk.c (ffffffff81f7eab4)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff81f80b63)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/bpf/hashtab.c (ffffffff8117763e)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/page_alloc.c (ffffffff81191c7c)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/readahead.c (ffffffff8119c060)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff81208d65)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff811bbc80)
Location: include/linux/bitops.h:187
Inline: True
```
```
In mm/vmalloc.c (ffffffff811cd8c0)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/hugetlb.c (ffffffff81f8c252)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff8121601e)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/pipe.c:pipe_proc_fn
  - fs/pipe.c:pipe_fcntl
```
```
In fs/file.c (ffffffff81229d85)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/super.c (ffffffff812babed)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/mballoc.c (ffffffff812d3085)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/indirect.c (ffffffff812d9f94)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/jbd2/journal.c (ffffffff812eef95)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
```
```
In lib/kfifo.c (ffffffff813fe290)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff81400125)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff81407342)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff81453ac3)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8147825d)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150ba5c)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:byt_set_termios
```
```
In drivers/iommu/iova.c (ffffffff8152ceab)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff8153643b)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
```
In drivers/iommu/intel-svm.c (ffffffff8153b59e)
Location: include/linux/bitops.h:187
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153d468)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81635d81)
Location: include/linux/bitops.h:187
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81650769)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/input/evdev.c (ffffffff8166d676)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/clk/clk-divider.c (ffffffff816e919e)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff816eac50)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
```
In net/core/sysctl_net_core.c (ffffffff817130b7)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/ipv4/inet_hashtables.c (ffffffff817620d6)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff8176a9a5)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_metrics.c (ffffffff817810f8)
Location: include/linux/bitops.h:187
Inline: True
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
In kernel/printk/printk.c (ffffffff81fa79b3)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff81fa9b98)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff8116004f)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff81173cc8)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff81186337)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff81188227)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/page_alloc.c (ffffffff81fb1223)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/readahead.c (ffffffff811b1264)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff8122ea8c)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff81fb441c)
Location: include/linux/bitops.h:187
Inline: True
```
```
In mm/memory.c (ffffffff811d6430)
Location: include/linux/bitops.h:187
Inline: True
```
```
In mm/vmalloc.c (ffffffff811ea996)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/hugetlb.c (ffffffff81fb5f53)
Location: include/linux/bitops.h:187
Inline: True
```
```
In fs/pipe.c (ffffffff8123cf3d)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_proc_fn
```
```
In fs/file.c (ffffffff812524f9)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/super.c (ffffffff812e9b10)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/mballoc.c (ffffffff81302aad)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/indirect.c (ffffffff81309964)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/jbd2/journal.c (ffffffff8131d515)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
```
```
In lib/kfifo.c (ffffffff8144590a)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff81447c22)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_alloc
```
```
In lib/genalloc.c (ffffffff8144f192)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff814a03d3)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/bitops.h:187
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814c679d)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155cfcb)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:byt_set_termios
```
```
In drivers/iommu/iova.c (ffffffff81580846)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff81582bc8)
Location: include/linux/bitops.h:187
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158acf0)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff815900ae)
Location: include/linux/bitops.h:187
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815920c5)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81696dc5)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci.c (ffffffff816b1084)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/input/evdev.c (ffffffff816cd94c)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/clk/clk-divider.c (ffffffff8174d955)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff8174f5fd)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
```
In net/core/sysctl_net_core.c (ffffffff8177ad27)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce89c)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff817d7422)
Location: include/linux/bitops.h:187
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee5f3)
Location: include/linux/bitops.h:187
Inline: True
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
In kernel/printk/printk.c (ffffffff81fe36d4)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff81fe5b50)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff8116aaaf)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff8117d74b)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff81194f7a)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff811970f7)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/page_alloc.c (ffffffff81fedaf1)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/readahead.c (ffffffff811c18ef)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff8124101c)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff81ff0e0a)
Location: include/linux/bitops.h:177
Inline: True
```
```
In mm/memory.c (ffffffff811e6390)
Location: include/linux/bitops.h:177
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fbc1a)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/hugetlb.c (ffffffff81ff28d7)
Location: include/linux/bitops.h:177
Inline: True
```
```
In fs/pipe.c (ffffffff8124fc9e)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_proc_fn
```
```
In fs/file.c (ffffffff81265769)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/super.c (ffffffff812ff880)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/mballoc.c (ffffffff81318817)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In lib/kfifo.c (ffffffff814640fa)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff81466572)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff8146da32)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff814c1f79)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814e87fd)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff815361c5)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81537e6d)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
```
In drivers/iommu/iova.c (ffffffff815acde7)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff815aefd8)
Location: include/linux/bitops.h:177
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b8350)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff815bd93e)
Location: include/linux/bitops.h:177
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bf985)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c4c7c)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci.c (ffffffff816df234)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/input/evdev.c (ffffffff816fb8ec)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/sysctl_net_core.c (ffffffff817a8343)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe6ad)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff818074f2)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
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
In kernel/printk/printk.c (ffffffff820c412a)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff820c6464)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff8116da71)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811802cb)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff8119c19f)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff8119ed64)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/page_alloc.c (ffffffff820cf732)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/readahead.c (ffffffff811c9b31)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff811e4c90)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff820d323e)
Location: include/linux/bitops.h:177
Inline: True
```
```
In mm/memory.c (ffffffff811f1410)
Location: include/linux/bitops.h:177
Inline: True
```
```
In mm/vmalloc.c (ffffffff81206937)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/hugetlb.c (ffffffff820d4f8c)
Location: include/linux/bitops.h:177
Inline: True
```
```
In fs/pipe.c (ffffffff8125bc01)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_proc_fn
```
```
In fs/file.c (ffffffff81272e99)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/mballoc.c (ffffffff8130f768)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81334664)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff8146917a)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff8146be28)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff81473172)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff814cc3c6)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff814d2bd3)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814f445d)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff815492a8)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff8154b121)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
```
In drivers/iommu/iova.c (ffffffff815c2b27)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c4d18)
Location: include/linux/bitops.h:177
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff815ce1f0)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff815d3a64)
Location: include/linux/bitops.h:177
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5522)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d926e)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci.c (ffffffff816f3a7f)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/input/evdev.c (ffffffff8171131b)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff8175ca8f)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff817c692c)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181ecce)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81827c22)
Location: include/linux/bitops.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
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
In kernel/printk/printk.c (ffffffff826cc37c)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff826ceae4)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff8117ab31)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff8118db6b)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff811aba74)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811ac9d9)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff811b1cd3)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/memremap.c (ffffffff811c8cd1)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/memremap.c:order_at
```
```
In mm/page_alloc.c (ffffffff826d8154)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/readahead.c (ffffffff811de9f1)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff811faef2)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff826dbc63)
Location: include/linux/bitops.h:179
Inline: True
```
```
In mm/memory.c (ffffffff812080dd)
Location: include/linux/bitops.h:179
Inline: True
```
```
In mm/vmalloc.c (ffffffff8121f627)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/hugetlb.c (ffffffff826ddb52)
Location: include/linux/bitops.h:179
Inline: True
```
```
In fs/pipe.c (ffffffff8127df09)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - fs/pipe.c:round_pipe_size
```
```
In fs/file.c (ffffffff812957c9)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/mballoc.c (ffffffff81334648)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81358b74)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff8149544a)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff81498128)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff814a0502)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff8150c8f6)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81512fd3)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81534b3d)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff815ac828)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff815ae787)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
```
In drivers/iommu/iova.c (ffffffff81629725)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162f2d3)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel-iommu.c (ffffffff81635030)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff8163a794)
Location: include/linux/bitops.h:179
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c2d2)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8174599e)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci.c (ffffffff8175fd4b)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/input/evdev.c (ffffffff8178259b)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff817cece4)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff817d2be2)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sysctl_net_core.c (ffffffff8184052c)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dc7e)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff818a7212)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
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
In kernel/printk/printk.c (ffffffff826f64e6)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff826f91f2)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff81189ba1)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff8119cdeb)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff811c2f3f)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811c3f77)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/sockmap.c (ffffffff811ccbcf)
Location: include/linux/bitops.h:179
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811d0a9e)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/memremap.c (ffffffff811e924e)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - kernel/memremap.c:order_at
```
```
In mm/page_alloc.c (ffffffff827025f6)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/readahead.c (ffffffff812001c2)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff8121c182)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff82706131)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff81228f77)
Location: include/linux/bitops.h:179
Inline: True
```
```
In mm/vmalloc.c (ffffffff812420b7)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/hugetlb.c (ffffffff827080bc)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff812a3a45)
Location: include/linux/bitops.h:179
Inline: True
```
```
In fs/file.c (ffffffff812bb945)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/mballoc.c (ffffffff813628f0)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813874ec)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff814ca800)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff814ccc99)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff814d5690)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff81541742)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8154837b)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8156a4fd)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff815e4a43)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff815e69d4)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
```
In drivers/iommu/iova.c (ffffffff81664408)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff81669abd)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel-iommu.c (ffffffff8167063c)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff81675d9b)
Location: include/linux/bitops.h:179
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677835)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817864be)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci.c (ffffffff817a06ec)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/input/evdev.c (ffffffff817c3822)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81817897)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff8181b9a9)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sysctl_net_core.c (ffffffff8188aa2d)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f188f)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff818fc4b5)
Location: include/linux/bitops.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
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
In kernel/printk/printk.c (ffffffff828ad4e7)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff828b00cc)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff81197451)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811ab43b)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff811d49af)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811d5b77)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff811e057e)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/page_alloc.c (ffffffff828b9d1c)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/readahead.c (ffffffff81212a92)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff8122f17f)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff828bd8de)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff8123c787)
Location: include/linux/bitops.h:160
Inline: True
```
```
In mm/vmalloc.c (ffffffff812566f3)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/hugetlb.c (ffffffff828bf48e)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff812b8b95)
Location: include/linux/bitops.h:160
Inline: True
```
```
In fs/file.c (ffffffff812d0b35)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/mballoc.c (ffffffff8137ab00)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813a002c)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff814df530)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff814e122c)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff814ea160)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff81558a97)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8155e57e)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81581f5d)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff815ff063)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81600fb4)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
```
In drivers/iommu/iova.c (ffffffff816828f3)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff8168868d)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168edbc)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff8169558b)
Location: include/linux/bitops.h:160
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696915)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817acede)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci.c (ffffffff817c69ac)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/input/evdev.c (ffffffff817eae92)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81843137)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff818471e5)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sysctl_net_core.c (ffffffff818aba0d)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff818f19fe)
Location: include/linux/bitops.h:160
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f46f)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff8192a4f5)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (ffffffff81a06591)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/printk/printk.c (ffffffff828c5ea5)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff828c8c39)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff811a5690)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b98bb)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff811e77cc)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811ea53d)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff811f617f)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffff81221d25)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (ffffffff8123f179)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff828d4ed8)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff8124dfdb)
Location: include/linux/bitops.h:160
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126a2d4)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff828d6e76)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff828d86af)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff812d5715)
Location: include/linux/bitops.h:160
Inline: True
```
```
In fs/file.c (ffffffff812edb65)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff81330e63)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff813a4ca6)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813ca37d)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff8150b3ec)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff8150d01f)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff81516e70)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff81588b1c)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8158ea50)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815b2531)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff8163175b)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff816338c5)
Location: include/linux/bitops.h:160
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816ba023)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bfc36)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c62ea)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff816cd9d1)
Location: include/linux/bitops.h:160
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf224)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ebe8a)
Location: include/linux/bitops.h:160
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81805ddf)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/input/evdev.c (ffffffff8182b9e2)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81885f3d)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff81889fa5)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sysctl_net_core.c (ffffffff818f72bf)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81943d90)
Location: include/linux/bitops.h:160
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff819535e8)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff81981dca)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff8198d6e5)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (ffffffff81a75f01)
Location: include/linux/bitops.h:160
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/printk/printk.c (ffffffff828ce4e9)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff828d11aa)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff811b0ec0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c4ece)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff811f3f2c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811f6c9d)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff811ffb5e)
Location: include/linux/bitops.h:167
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff8120313f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffff8122f7d5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (ffffffff8124d5d9)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff828dd367)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff8125c50b)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/vmalloc.c (ffffffff812791de)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff828df2e1)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff828e0b45)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff812e7285)
Location: include/linux/bitops.h:167
Inline: True
```
```
In fs/file.c (ffffffff812ff625)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff81344a53)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff813bdb11)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813e3685)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff8152920c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff8152ae6f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff81537910)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff815aa43c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815b0670)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815d34b1)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff8165348b)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff816555f5)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816dce33)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e09e2)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e883a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff816f17ad)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3064)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181cd5a)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81836c8f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183bd22)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff8185d352)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff818b7ef2)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff818bbf7e)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sysctl_net_core.c (ffffffff8192903f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81978d80)
Location: include/linux/bitops.h:167
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81989998)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b861a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff819c4045)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (ffffffff81aacdc1)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/printk/printk.c (ffffffff82cef92e)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff82cf1ff5)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff811c9070)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e17de)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff812176cf)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff8121a689)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff8122698d)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/stackmap.c (ffffffff8122af98)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffff8125c875)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (ffffffff8127b965)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff82cfa7ec)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff8128ba8b)
Location: include/linux/bitops.h:182
Inline: True
```
```
In mm/vmalloc.c (ffffffff812aa1ae)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff82cfc689)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff82cfdfe1)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff8131ebf5)
Location: include/linux/bitops.h:182
Inline: True
```
```
In fs/file.c (ffffffff81338615)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff81385723)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff81409ad1)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff814309e5)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/selinux/ss/hashtab.c (ffffffff814bf63f)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_compute_size
```
```
In block/keyslot-manager.c (ffffffff81581114)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/kfifo.c (ffffffff8158c9b5)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff8158e4c6)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_shrink
```
```
In lib/genalloc.c (ffffffff8159ba60)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff816533dd)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816598fb)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167d04d)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff817033de)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff817053d5)
Location: include/linux/bitops.h:182
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81791be8)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
```
In drivers/iommu/iova.c (ffffffff81793890)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
```
In drivers/iommu/amd/iommu.c (ffffffff81798543)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179e3cf)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179f747)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_alloc_iova
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/svm.c (ffffffff817a94bf)
Location: include/linux/bitops.h:182
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aae86)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ec781)
Location: include/linux/bitops.h:182
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81903a35)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_streams_entries
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190eb0b)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff8192f925)
Location: include/linux/bitops.h:182
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198874d)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff819fcfbf)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81a4e1ab)
Location: include/linux/bitops.h:182
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81a616af)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa2f3a)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81aaf7d5)
Location: include/linux/bitops.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
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
In kernel/printk/printk.c (ffffffff82fdc059)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff82fdeaca)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff811c6730)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811df3fe)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff812197db)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff8121d399)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff8122d729)
Location: include/linux/bitops.h:185
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812303ef)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff81232ec5)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffff81267477)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff81be70e4)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff82fe74e8)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff81296a3b)
Location: include/linux/bitops.h:185
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b52db)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff82fe90a4)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff82fea9d8)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff8132bda3)
Location: include/linux/bitops.h:185
Inline: True
```
```
In fs/file.c (ffffffff81343fa5)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff81396753)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff8141c8d7)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81449795)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/selinux/ss/hashtab.c (ffffffff814dcfd1)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In block/keyslot-manager.c (ffffffff8159e134)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/kfifo.c (ffffffff815a9405)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff815ab036)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff815b75b3)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff8165d29d)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81679cdb)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81bff7c6)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff8172063e)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff817226c5)
Location: include/linux/bitops.h:185
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a6bd3)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ac12b)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
```
```
In drivers/iommu/intel/iommu.c (ffffffff817aec6e)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/svm.c (ffffffff817b54cc)
Location: include/linux/bitops.h:185
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b8240)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bdd68)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
```
In drivers/iommu/iova.c (ffffffff817c0319)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81838fc4)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f57aa)
Location: include/linux/bitops.h:185
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81911bc9)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8191663f)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff819387d0)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff8198c52d)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff819fcbff)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81a54191)
Location: include/linux/bitops.h:185
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad46a)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81abad95)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
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
In kernel/printk/printk.c (ffffffff831e6dbc)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff831e95da)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff811c7740)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e05ae)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff8121d1cb)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff81220e9f)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812259d0)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff81232834)
Location: include/linux/bitops.h:185
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81237075)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffff8126c0b0)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff81bd8e8b)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff831f1c0a)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff8129c5db)
Location: include/linux/bitops.h:185
Inline: True
```
```
In mm/vmalloc.c (ffffffff812ba6c8)
Location: include/linux/bitops.h:185
Inline: True
```
```
In mm/page_alloc.c (ffffffff831f38d9)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff831f534f)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff81331de3)
Location: include/linux/bitops.h:185
Inline: True
```
```
In fs/file.c (ffffffff8134a345)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff81399be5)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff81422f17)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff8144f105)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/selinux/ss/hashtab.c (ffffffff814e3941)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In block/keyslot-manager.c (ffffffff815a4e84)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/kfifo.c (ffffffff815b4005)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff815b5b44)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff815c2293)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/pci.c (ffffffff81630d89)
Location: include/linux/bitops.h:185
Inline: True
```
```
In drivers/pci/msi.c (ffffffff81640653)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8165c81e)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81bf1304)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff8170187d)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81703b15)
Location: include/linux/bitops.h:185
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81788663)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178effd)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
```
```
In drivers/iommu/intel/iommu.c (ffffffff81791422)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/svm.c (ffffffff8179891c)
Location: include/linux/bitops.h:185
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b390)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a0f4b)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
```
In drivers/iommu/iova.c (ffffffff817a3408)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c284)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d8df7)
Location: include/linux/bitops.h:185
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff818f51d4)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f9ac4)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff8191c040)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81970b3d)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff819e346f)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81a4fca1)
Location: include/linux/bitops.h:185
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98544)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81aa5e85)
Location: include/linux/bitops.h:185
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
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
In kernel/printk/printk.c (ffffffff832caf33)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff832cdb9e)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff811f2ec4)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff8120f616)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff8125414b)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff81258860)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d9c7)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff8126b7d8)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/stackmap.c (ffffffff81271659)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/watch_queue.c (ffffffff812976fb)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/readahead.c (ffffffff812a8eb5)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff81cbadff)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff832d77ab)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff812dd247)
Location: include/linux/bitops.h:186
Inline: True
```
```
In mm/vmalloc.c (ffffffff812fccc8)
Location: include/linux/bitops.h:186
Inline: True
```
```
In mm/page_alloc.c (ffffffff832d9b9a)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/hugetlb.c (ffffffff832db74e)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff8137f55f)
Location: include/linux/bitops.h:186
Inline: True
```
```
In fs/file.c (ffffffff813980a5)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff813e8ca6)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff814766e2)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff814a2c6a)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/selinux/ss/hashtab.c (ffffffff8153cd37)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In block/keyslot-manager.c (ffffffff8160d8f3)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/kfifo.c (ffffffff8161a1f5)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff8161bffc)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff8162a183)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/pci.c (ffffffff8169ecbc)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_restore_rebar_state
```
```
In drivers/pci/msi.c (ffffffff816b06ac)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816ceeea)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81cedafe)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff8177c275)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff8177e9ff)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fractional_divider_general_approximation
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180ff93)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel/dmar.c (ffffffff818168ac)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
```
```
In drivers/iommu/intel/iommu.c (ffffffff818188e9)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/svm.c (ffffffff8182111a)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823eb4)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182a0b4)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
```
In drivers/iommu/iova.c (ffffffff8182c5c5)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6710)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197409a)
Location: include/linux/bitops.h:186
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81992ebb)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81998392)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff819be72c)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81a1945d)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff81a942ff)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81b08875)
Location: include/linux/bitops.h:186
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53a18)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81b62270)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
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
In kernel/printk/printk.c (ffffffff8347e567)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex/core.c (ffffffff8348183a)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff8122c49d)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124c46c)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff8129c70a)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff812a1670)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/bloom_filter.c (ffffffff812a497d)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7d17)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff812ba5d6)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/stackmap.c (ffffffff812c07c6)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/watch_queue.c (ffffffff812ed99b)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/readahead.c (ffffffff81302096)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff81e6c98e)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff8348c34a)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff8133ce3c)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - mm/memory.c:fault_around_bytes_set
```
```
In mm/vmalloc.c (ffffffff81363ea6)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff8348eb79)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/hugetlb.c (ffffffff83490e0b)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff813fd8f5)
Location: include/linux/bitops.h:152
Inline: True
```
```
In fs/file.c (ffffffff8141a805)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/mballoc.c (ffffffff814f89e7)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff8152a0f4)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/selinux/ss/hashtab.c (ffffffff815d4737)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In crypto/dh.c (ffffffff81654215)
Location: include/linux/bitops.h:152
Inline: True
```
```
In block/blk-crypto-profile.c (ffffffff816c21c8)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff81e8e448)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - io_uring/io_uring.c:__roundup_pow_of_two
```
```
In lib/kfifo.c (ffffffff816e77e5)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff816e990b)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff816fb613)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/pci.c (ffffffff817bf249)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_restore_rebar_state
```
```
In drivers/pci/msi/msi.c (ffffffff817d3bf8)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff817f7b84)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81eb50cb)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff818b2bc0)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff818b589f)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fractional_divider_general_approximation
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194f2c3)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel/dmar.c (ffffffff8195785c)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
```
```
In drivers/iommu/intel/iommu.c (ffffffff81959631)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/svm.c (ffffffff8196129d)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff819636e7)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/iommu/iova.c (ffffffff8196e3dd)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f0ce7)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad051b)
Location: include/linux/bitops.h:152
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81aef988)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af55d7)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff81b1d56f)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81b821fd)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff81c0a6c2)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81c8e851)
Location: include/linux/bitops.h:152
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce156a)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81cf12f0)
Location: include/linux/bitops.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
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
In kernel/printk/printk.c (ffffffff83eaa480)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/dma/swiotlb.c (ffffffff811c443e)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_adjust_nareas
```
```
In kernel/futex/core.c (ffffffff83eaea09)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff81277fdd)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129d43a)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/bpf/hashtab.c (ffffffff812f90c4)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff812fe8d0)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/bloom_filter.c (ffffffff813026bd)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8130639a)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff8131d996)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/stackmap.c (ffffffff81324056)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/watch_queue.c (ffffffff81357d8b)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/readahead.c (ffffffff8136c8ee)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (ffffffff8139b130)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff83ebd699)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff813b4a3c)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/memory.c:fault_around_bytes_set
```
```
In mm/vmalloc.c (ffffffff813dffb6)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff83ec0da0)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/hugetlb.c (ffffffff83ec40e6)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff81487505)
Location: include/linux/bitops.h:203
Inline: True
```
```
In fs/file.c (ffffffff814a6595)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/mballoc.c (ffffffff81593107)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff815c8a84)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/selinux/ss/hashtab.c (ffffffff81682857)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In crypto/dh.c (ffffffff8170e1e5)
Location: include/linux/bitops.h:203
Inline: True
```
```
In block/blk-crypto-profile.c (ffffffff817834c8)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff8178cab6)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_uring_create
```
```
In lib/kfifo.c (ffffffff817d7625)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff817d9aab)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff817ee253)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In lib/stackdepot.c (ffffffff8189ef12)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/pci/pci.c (ffffffff818db6c9)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_restore_rebar_state
```
```
In drivers/pci/msi/msi.c (ffffffff818f4b28)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81923694)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81950f65)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff819ff320)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81a028bf)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fractional_divider_general_approximation
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81a87ea5)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab43ff)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abe7a8)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac0f8e)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca886)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acc7d5)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/iommu/iova.c (ffffffff81ad8d6d)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e5b7)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5b66b)
Location: include/linux/bitops.h:203
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81c7c6d8)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c82e47)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff81caf54f)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81d20a6d)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff81dba152)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81e4955d)
Location: include/linux/bitops.h:203
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea261a)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5640)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd827)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/udp.c (ffffffff81edfd5b)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_pernet_init
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
In kernel/printk/printk.c (ffffffff836cf43c)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/dma/swiotlb.c (ffffffff811d75de)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_adjust_nareas
```
```
In kernel/futex/core.c (ffffffff836d39c9)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff8128fa1c)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff812baf8d)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/bpf/hashtab.c (ffffffff81326f64)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff8132d4c0)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/bloom_filter.c (ffffffff81331466)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813351e6)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff8134d796)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/stackmap.c (ffffffff813542cc)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/watch_queue.c (ffffffff8138961b)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/readahead.c (ffffffff8139eb5e)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/vmscan.c (ffffffff813b863c)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/mm_init.c (ffffffff836e2a41)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/mm_init.c:alloc_large_system_hash
```
```
In mm/percpu.c (ffffffff813ce1f0)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff836e5b59)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff813e967e)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/memory.c:fault_around_bytes_set
```
```
In mm/vmalloc.c (ffffffff81414cfa)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff8214c730)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/hugetlb.c (ffffffff836e91fc)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff814bc315)
Location: include/linux/bitops.h:203
Inline: True
```
```
In fs/file.c (ffffffff814db555)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/mballoc.c (ffffffff815ca150)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81600824)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/selinux/ss/hashtab.c (ffffffff816ba9d7)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In crypto/dh.c (ffffffff81748a85)
Location: include/linux/bitops.h:203
Inline: True
```
```
In block/blk-crypto-profile.c (ffffffff817c3822)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff817cdbdd)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_uring_create
```
```
In lib/kfifo.c (ffffffff81816835)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff81818e2b)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff8182e653)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In lib/stackdepot.c (ffffffff818e13db)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/pci/pci.c (ffffffff8191e8c9)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_restore_rebar_state
```
```
In drivers/pci/msi/msi.c (ffffffff81937f58)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819672a4)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81997465)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff81a47fda)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81a4b70f)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fractional_divider_general_approximation
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81ad3595)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b01eff)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0b138)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0d7ee)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/svm.c (ffffffff81b17596)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19366)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/iommu/iova.c (ffffffff81b26d0e)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1dc8)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc2cd0)
Location: include/linux/bitops.h:203
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81ce3948)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce9b35)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff81d16b4f)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81d89c7d)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff81e2aa42)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81ea4c6d)
Location: include/linux/bitops.h:203
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00e3a)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81f13a70)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c4e7)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/udp.c (ffffffff81f3f19b)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_pernet_init
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
In kernel/printk/printk.c (ffffffff8390084c)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/dma/swiotlb.c (ffffffff811ec88e)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_adjust_nareas
```
```
In kernel/futex/core.c (ffffffff839059c9)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff812aafa9)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d75dd)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/bpf/hashtab.c (ffffffff8134b5b2)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff8135185a)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/bloom_filter.c (ffffffff81355a06)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81359846)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff81374cb6)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/stackmap.c (ffffffff8137cc3c)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/watch_queue.c (ffffffff813b306b)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/readahead.c (ffffffff813c87c3)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/vmscan.c (ffffffff813e1232)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:lru_gen_shrink_node
```
```
In mm/mm_init.c (ffffffff83915337)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/mm_init.c:alloc_large_system_hash
```
```
In mm/percpu.c (ffffffff813f8b60)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff8391838d)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff814145ae)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/memory.c:fault_around_bytes_set
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:alloc_anon_folio
```
```
In mm/vmalloc.c (ffffffff81441799)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff81445af9)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff8391c628)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/huge_memory.c (ffffffff8391e984)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init_sysfs
  - mm/huge_memory.c:__thp_vma_allowable_orders
  - mm/huge_memory.c:__thp_vma_allowable_orders
```
```
In fs/pipe.c (ffffffff814ee845)
Location: include/linux/bitops.h:203
Inline: True
```
```
In fs/file.c (ffffffff8150db55)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/mballoc.c (ffffffff81602f60)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81639574)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/selinux/ss/hashtab.c (ffffffff816f7467)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In security/selinux/ss/avtab.c (ffffffff816f9f56)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In crypto/dh.c (ffffffff8178a925)
Location: include/linux/bitops.h:203
Inline: True
```
```
In block/blk-crypto-profile.c (ffffffff818084b2)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff818167ad)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_uring_create
```
```
In lib/kfifo.c (ffffffff8185bb15)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff8185e17b)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff81880213)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In lib/stackdepot.c (ffffffff81928020)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81956b69)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/pci/pci.c (ffffffff819669e2)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_restore_rebar_state
```
```
In drivers/pci/msi/msi.c (ffffffff81980db8)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b09d4)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/clk/clk-divider.c (ffffffff81a93a82)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81a96a4f)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fractional_divider_general_approximation
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81b22c74)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b5586f)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5f19a)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b621f9)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/nested.c (ffffffff81b693bf)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6cbab)
Location: include/linux/bitops.h:203
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e7d7)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
```
```
In drivers/iommu/iova.c (ffffffff81b7de0e)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16558)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/spi/spi.c (ffffffff81cdc280)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxwords
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d779d0)
Location: include/linux/bitops.h:203
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81d98aa8)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9f35d)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff81dcc7ff)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81e413cd)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8d82)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81f67641)
Location: include/linux/bitops.h:203
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc519a)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81fd7f50)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff146a)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/udp.c (ffffffff8200549a)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_pernet_init
```
```
In lib/objpool.c (ffffffff82191c18)
Location: include/linux/bitops.h:203
Inline: True
Inline callers:
  - lib/objpool.c:objpool_init
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
In kernel/printk/printk.c (ffff800011445c40)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffff8000114494d8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffff80001022e7bc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffff800010244c54)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffff8000102777fc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffff80001027b3cc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (ffff8000102869d4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/stackmap.c (ffff80001028b838)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffff8000102befa4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (ffff8000102e413c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffff800011455ec0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffff8000102f3f2c)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffff8000114580f8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffff800011459d80)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffff80001038fb24)
Location: include/linux/bitops.h:167
Inline: True
```
```
In fs/file.c (ffff8000103b0b10)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffff800010402e88)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffff80001049472c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffff8000104bcc50)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffff800010633b94)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffff800010635f50)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffff800010643f28)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011474a74)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (ffff8000106750e8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_prepare
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (ffff8000106757c8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare
```
```
In drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c (ffff8000106758c0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_prepare
```
```
In drivers/pci/msi.c (ffff8000107139bc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffff80001071c5f8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721318)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075bd68)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
```
In drivers/clk/clk-divider.c (ffff8000107c3fa4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fractional-divider.c (ffff8000107c701c)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/clk/rockchip/clk.c (ffff8000107ec9d0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_fractional_approximation
```
```
In drivers/clk/sunxi/clk-sunxi.c (ffff8000107f2030)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sunxi.c:sun6i_get_ahb1_factors
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c96fc)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/iova.c (ffff8000108cdd34)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d5aa0)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a54680)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/xhci.c (ffff800010a74b50)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a79a74)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8d878)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/input/evdev.c (ffff800010a9e260)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffff800010b10360)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffff800010b148ec)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/of/base.c (ffff800010b6a854)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In net/core/sysctl_net_core.c (ffff800010bc53d0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffff800010c1f934)
Location: include/linux/bitops.h:167
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffff800010c31018)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffff800010c698a8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffff800010c76d24)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (ffff800010d816c0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/printk/printk.c (c152027c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (c1523698)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/bpf/hashtab.c (c04aa830)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (c04ad404)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (c04b7064)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/stackmap.c (c04baf04)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (c04eb270)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/percpu.c (c050828c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (c1530f40)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (c05166e8)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/vmalloc.c (c052c0bc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (c153207c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In fs/pipe.c (c05769bc)
Location: include/linux/bitops.h:167
Inline: True
```
```
In fs/file.c (c05903f0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (c05d6314)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (c06561b4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (c06802ec)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/pstore/ram.c (c06d6b70)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
```
```
In lib/kfifo.c (c07d9f00)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (c07dbec0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (c07ea700)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154cf6c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (c081d4bc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_prepare
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (c081db64)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare
```
```
In drivers/bus/uniphier-system-bus.c (c0829650)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_add_bank
```
```
In drivers/pci/msi.c (c089f1b4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
```
In drivers/pci/endpoint/pci-epf-core.c (c08a585c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/pci/controller/pci-mvebu.c (c08a969c)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/pci/controller/pcie-rcar.c (c08ae680)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
```
```
In drivers/video/fbdev/amba-clcd.c (c08de86c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
```
In drivers/clk/clk-divider.c (c08efc08)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:_div_round_closest
  - drivers/clk/clk-divider.c:_div_round_closest
  - drivers/clk/clk-divider.c:_div_round_up
```
```
In drivers/clk/clk-fractional-divider.c (c08f239c)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/clk/rockchip/clk.c (c0906120)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_fractional_approximation
```
```
In drivers/usb/host/ehci-hcd.c (c0b29430)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/xhci.c (c0b485d4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (c0b4d4b4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-mtk-sch.c (c0b5fc20)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:setup_sch_info
```
```
In drivers/input/evdev.c (c0b7f230)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (c0bee438)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/of/base.c (c0c4de64)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In net/core/sysctl_net_core.c (c0ce113c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (c0d37554)
Location: include/linux/bitops.h:167
Inline: True
```
```
In net/core/bpf_sk_storage.c (c0d48548)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (c0d78d1c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (c0d852ec)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (c0e7bc70)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In arch/powerpc/kernel/dma-iommu.c (c000000000050824)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_get_required_mask
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d3a88)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup_iov_resources
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_setup_default_config
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_set_bypass
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
```
```
In arch/powerpc/platforms/pseries/msi.c (c0000000000f7f80)
Location: include/linux/bitops.h:167
Inline: True
```
```
In kernel/printk/printk.c (c00000000136a7b4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (c00000000136e6d8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (c0000000002b7d9c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (c0000000002d89e8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (c00000000032091c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (c000000000324bfc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (c0000000003320b0)
Location: include/linux/bitops.h:167
Inline: True
```
```
In kernel/bpf/stackmap.c (c0000000003377e4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (c000000000377988)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (c0000000003a4708)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (c00000000137edfc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (c0000000003bab60)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/vmalloc.c (c0000000003e0c90)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (c0000000013818f8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (c000000001383a40)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (c0000000004877f8)
Location: include/linux/bitops.h:167
Inline: True
```
```
In fs/file.c (c0000000004ac524)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (c00000000050f7ac)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (c0000000005bdbb4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (c0000000005f2b54)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (c0000000007d902c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (c0000000007dc59c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (c0000000007f0364)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (c00000000088330c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (c00000000088cb70)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b20408)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/xhci.c (c000000000b4ac88)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (c000000000b51150)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (c000000000b7e928)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (c000000000c039e4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/of/base.c (c000000000c440e4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In net/core/sysctl_net_core.c (c000000000c9feec)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (c000000000d12b64)
Location: include/linux/bitops.h:167
Inline: True
```
```
In net/core/bpf_sk_storage.c (c000000000d2b288)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e64c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (c000000000d7e8e0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (c000000000ec1600)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/printk/printk.c (ffffffe0000078a0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffe00000a942)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/bpf/hashtab.c (ffffffe0001b0306)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffe0001b316c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffe0001bbe76)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/stackmap.c (ffffffe0001bf440)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffe0001e129c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (ffffffe0001fa826)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffe000014e26)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffe000205d3a)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/vmalloc.c (ffffffe000217fe6)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/page_alloc.c (ffffffe0000169a6)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffe00001815a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffe00025fa4e)
Location: include/linux/bitops.h:167
Inline: True
```
```
In fs/file.c (ffffffe000274f3c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffe0002b063c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffe0003193ce)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffe000338956)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffe000461bde)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffe000463e5a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffe000470d1a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffe0004ddcb4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffe0004e32a8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/clk/clk-divider.c (ffffffe000511c1a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffe0005140bc)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000670194)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffe00068cc8a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000691232)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffe0006adef4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffe0006fd398)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/of/base.c (ffffffe00071ffec)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In net/core/sysctl_net_core.c (ffffffe000752300)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffe000799736)
Location: include/linux/bitops.h:167
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a792c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf87a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffe0007d9d8e)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (ffffffe0008adb2c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/printk/printk.c (ffffffff828b71e1)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff828ba05b)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff811a94e0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bd4ee)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff811ec54c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811ef2bd)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff811f817e)
Location: include/linux/bitops.h:167
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811fb75f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffff81227e25)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (ffffffff81245c29)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff828c621b)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff81254b5b)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127182e)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff828c8195)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff828c99f9)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff812df865)
Location: include/linux/bitops.h:167
Inline: True
```
```
In fs/file.c (ffffffff812f7c05)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8133d033)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff813b60f1)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813dbc65)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff815217ec)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff8152344f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff8152fef0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff8159dc0c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815a3e30)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c74c1)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff816194eb)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff8161b655)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816a2883)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a6432)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ae31a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff816b6f9d)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8854)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/nvme/host/core.c (ffffffff81743644)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:__nvme_revalidate_disk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d513a)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817ef03f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f40d2)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff81812362)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff8185dd72)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff818c903f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81918bf0)
Location: include/linux/bitops.h:167
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81929808)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff8195848a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81963eb5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (ffffffff81a4c151)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/printk/printk.c (ffffffff828af46c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff828b26ee)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff8119c460)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b02ce)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff811df2dc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811e204d)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff811eaece)
Location: include/linux/bitops.h:167
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811ee4af)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffff8121af65)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (ffffffff81238bd9)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff828be940)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff8124799b)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126379e)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff828c08ba)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff828c211e)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff812d04a5)
Location: include/linux/bitops.h:167
Inline: True
```
```
In fs/file.c (ffffffff812e8825)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8132dcf3)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff813a6b81)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813cc6e5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff81511adc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff8151372f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff815201d0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff8158cd9c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81592fd0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/clk/clk-divider.c (ffffffff8160da1b)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff8160fb85)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff81680273)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff81683e22)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168bc7a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff81694bdd)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696494)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/nvme/host/core.c (ffffffff817252d4)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:__nvme_revalidate_disk
```
```
In drivers/usb/host/xhci.c (ffffffff817b414f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817b9272)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff817d9aa2)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff81825342)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In net/core/sysctl_net_core.c (ffffffff81882f7f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff818d29a0)
Location: include/linux/bitops.h:167
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff818e35b8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff81911f7a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff8191d9a5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (ffffffff81a08d41)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/printk/printk.c (ffffffff828ca11d)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff828ccdde)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff811a72b0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bb2be)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff811ea31c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811ed08d)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff811f5f4e)
Location: include/linux/bitops.h:167
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811f952f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffff81225bc5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (ffffffff812439c9)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff828d8f9b)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff812528fb)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126f5ce)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff828daf15)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff828dc779)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff812dd675)
Location: include/linux/bitops.h:167
Inline: True
```
```
In fs/file.c (ffffffff812f5a15)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8133ab03)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff813b3951)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813d9105)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff8151d87c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff8151f4df)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff8152bc30)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff8159e18c)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815a43c0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c7a51)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff816472cb)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81649435)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816d0af3)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d46a2)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dc4fa)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff816e546d)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e6d24)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81811bda)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8182bb0f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81830ba2)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff818514e2)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff818ad3a2)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff818b142e)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sysctl_net_core.c (ffffffff8191a03f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff81969d80)
Location: include/linux/bitops.h:167
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a998)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c2c5a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff819ce685)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (ffffffff81ab8001)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/printk/printk.c (ffffffff828cf4cf)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/futex.c (ffffffff828d21d8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/trace/tracing_map.c (ffffffff811b5050)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c935e)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/bpf/hashtab.c (ffffffff811f86fc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811fb53f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/devmap.c (ffffffff812044ac)
Location: include/linux/bitops.h:167
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81207fcf)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In mm/readahead.c (ffffffff81234ec5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/percpu.c (ffffffff81253189)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/workingset.c (ffffffff828de3bc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/memory.c (ffffffff812622cb)
Location: include/linux/bitops.h:167
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127efec)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff828e0336)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/hugetlb.c (ffffffff828e1b90)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/pipe.c (ffffffff812ee5f5)
Location: include/linux/bitops.h:167
Inline: True
```
```
In fs/file.c (ffffffff81306b55)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8134dcb3)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/ext4/mballoc.c (ffffffff813c84e7)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813ee3f5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In lib/kfifo.c (ffffffff815370ec)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffffffff81538eff)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/genalloc.c (ffffffff81545a30)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In drivers/pci/msi.c (ffffffff815b85bc)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815be7c0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815e15f1)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/clk/clk-divider.c (ffffffff8166185b)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff816639c5)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816eb253)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816eeda2)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f6b3a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel-svm.c (ffffffff8170011d)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701424)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182c6aa)
Location: include/linux/bitops.h:167
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81845adf)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184ad72)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (ffffffff8186c302)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/edac/edac_mc.c (ffffffff818c9612)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff818cd6be)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sysctl_net_core.c (ffffffff8193b27f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/sock_map.c (ffffffff8198c1a0)
Location: include/linux/bitops.h:167
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8199cec8)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cc72a)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff819d8215)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/xdp/xsk_queue.c (ffffffff81ac4421)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
</details>
</li>
</ul>

## Differences
