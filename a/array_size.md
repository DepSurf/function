# Function: <code>array_size</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810ee3b7)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff811392ae)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145747)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/tracing_map.c (ffffffff8118a6d0)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff811bea43)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/binfmt_elf.c (ffffffff81305e21)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813097c5)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffffffff8149ba5a)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b55f)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff827356e3)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/ethtool.c (ffffffff8189c229)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffffffff819b11fc)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In kernel/power/swap.c (ffffffff810f9a27)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff81144b7e)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151307)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/tracing_map.c (ffffffff81198030)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff811cf66e)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/binfmt_elf.c (ffffffff8131b5b1)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131efc5)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffffffff814b5d6c)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bbddf)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828ef60f)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/ethtool.c (ffffffff818beae1)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffffffff819e85e5)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (ffffffff81a06607)
Location: include/linux/overflow.h:247
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In kernel/power/swap.c (ffffffff8110214f)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff8114ff81)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c5d6)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/tracing_map.c (ffffffff811a5c00)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff811e418d)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (ffffffff81331145)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/binfmt_elf.c (ffffffff81342e86)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8134681b)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffffffff814e42bc)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8290ab9a)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/ethtool.c (ffffffff8190acc3)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffffffff81a588db)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (ffffffff81a75f79)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In kernel/power/swap.c (ffffffff8110e560)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff8115bc11)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
```
In kernel/trace/tracing_map.c (ffffffff811b1430)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff811f09dd)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (ffffffff81344cb6)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/binfmt_elf.c (ffffffff8135b2c4)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135eb29)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffffffff814fd67c)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff82914591)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/ethtool.c (ffffffff8193d2d3)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffffffff81a8e9c6)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (ffffffff81aace39)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In kernel/power/swap.c (ffffffff811195f1)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff8116c115)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
```
```
In kernel/trace/tracing_map.c (ffffffff811c9810)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff8121301d)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
```
In fs/io_uring.c (ffffffff8137c6d3)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/binfmt_elf.c (ffffffff813a0128)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813a33cc)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/core.c (ffffffff8155d142)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/core.c:check_partition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff82d272cf)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/netlink/policy.c (ffffffff81a7d772)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/ioctl.c (ffffffff81a81a7e)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
```
```
In net/packet/af_packet.c (ffffffff81b85b82)
Location: include/linux/overflow.h:253
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
In kernel/power/swap.c (ffffffff81114e3a)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff811687b5)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
```
```
In kernel/trace/tracing_map.c (ffffffff811c6ed0)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff812147fd)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
```
In mm/memcontrol.c (ffffffff81302726)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/io_uring.c (ffffffff8138f513)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In block/partitions/core.c (ffffffff8157953f)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - block/partitions/core.c:check_partition
```
```
In drivers/tty/vt/consolemap.c (ffffffff817673b9)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff830159b6)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9ed8)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/netlink/policy.c (ffffffff81a86c98)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/ioctl.c (ffffffff81a8a3de)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
```
```
In net/packet/af_packet.c (ffffffff81b95592)
Location: include/linux/overflow.h:263
Inline: True
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
In kernel/power/swap.c (ffffffff811157a2)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff81169555)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
```
```
In kernel/trace/tracing_map.c (ffffffff811c7ec0)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff81217060)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
```
In mm/memcontrol.c (ffffffff81308ddc)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/io_uring.c (ffffffff8139e8d7)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In security/landlock/ruleset.c (ffffffff81537e1c)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In block/partitions/core.c (ffffffff81580f9f)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - block/partitions/core.c:check_partition
```
```
In drivers/tty/vt/consolemap.c (ffffffff8174aff9)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff83220954)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aeee8)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/netlink/policy.c (ffffffff81a6fd79)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/ioctl.c (ffffffff81a7394e)
Location: include/linux/overflow.h:263
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
```
```
In net/packet/af_packet.c (ffffffff81b84682)
Location: include/linux/overflow.h:263
Inline: True
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
In kernel/power/swap.c (ffffffff811359c2)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/dma/swiotlb.c (ffffffff8115e8e3)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/kexec_file.c (ffffffff8118efb5)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
```
```
In kernel/trace/tracing_map.c (ffffffff811f3820)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff8124d820)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In mm/memcontrol.c (ffffffff81354ffc)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/io_uring.c (ffffffff813eec32)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In security/landlock/ruleset.c (ffffffff81596a10)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In block/partitions/core.c (ffffffff815e62af)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - block/partitions/core.c:check_partition
```
```
In drivers/tty/vt/consolemap.c (ffffffff817ccaa9)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8330a271)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d53b)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/netlink/policy.c (ffffffff81b294c9)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/ioctl.c (ffffffff81b2d4be)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
```
```
In net/ipv4/igmp.c (ffffffff81ba144a)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
```
```
In net/packet/af_packet.c (ffffffff81c50b24)
Location: include/linux/overflow.h:131
Inline: True
```
</details>
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
In virt/kvm/kvm_main.c (ffff8000100bf070)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
```
```
In kernel/trace/tracing_map.c (ffff80001022f0c0)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffff800010274188)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (ffff8000104030c0)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/binfmt_elf.c (ffff800010420c44)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff8000104244f0)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffff8000105ff214)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d44c)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
```
```
In net/core/ethtool.c (ffff800010bdcd50)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffff800010d5bb78)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (ffff800010d81770)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In kernel/power/swap.c (c03c1474)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/bpf/verifier.c (c04a6810)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (c05d6514)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/binfmt_elf.c (c05e8bbc)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (c07aa4d8)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/dma/ipu/ipu_idmac.c (c09280e4)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
```
```
In net/core/ethtool.c (c0cf7560)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (c0e5bcf0)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (c0e7bd20)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In arch/powerpc/kernel/rtasd.c (c00000000134d978)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan_init
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0a30)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In kernel/kexec_file.c (c000000000234294)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
```
In kernel/trace/tracing_map.c (c0000000002b895c)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (c00000000031bda0)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (c00000000050f9ac)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/binfmt_elf.c (c00000000052f8d4)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c0000000005334ec)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (c0000000007992ac)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In net/core/ethtool.c (c000000000cbcf90)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (c000000000e97510)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (c000000000ec16d4)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In kernel/bpf/verifier.c (ffffffe0001acafe)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (ffffffe0002b086a)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/binfmt_elf.c (ffffffe0002c16a8)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffffffe00043a808)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In net/core/ethtool.c (ffffffe0007640ec)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffffffe000891ec2)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (ffffffe0008adab6)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In kernel/power/swap.c (ffffffff81106b38)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff81154231)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
```
In kernel/trace/tracing_map.c (ffffffff811a9a50)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff811e8ffd)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (ffffffff8133d296)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/binfmt_elf.c (ffffffff813538a4)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81357109)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffffffff814f5c5c)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828f9ccb)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/ethtool.c (ffffffff818dd2a3)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffffffff81a2e056)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (ffffffff81a4c1c9)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In kernel/power/swap.c (ffffffff810f7a20)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff81147551)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
```
In kernel/trace/tracing_map.c (ffffffff8119c9d0)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff811dbdbd)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (ffffffff8132df56)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/binfmt_elf.c (ffffffff81344564)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81347db9)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffffffff814e616c)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828f1eaa)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/ethtool.c (ffffffff818970e3)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffffffff819eb246)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (ffffffff81a08db9)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In kernel/power/swap.c (ffffffff81104a30)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff81152011)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
```
In kernel/trace/tracing_map.c (ffffffff811a7820)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff811e6dcd)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (ffffffff8133ad66)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/binfmt_elf.c (ffffffff81351374)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81354bd9)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffffffff814f1cec)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8290ebdd)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/ethtool.c (ffffffff8192e2d3)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffffffff81a99c06)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (ffffffff81ab8079)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
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
In kernel/power/swap.c (ffffffff8110fe10)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/kexec_file.c (ffffffff8115ef01)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
```
In kernel/trace/tracing_map.c (ffffffff811b55c0)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/bpf/verifier.c (ffffffff811f517d)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In fs/io_uring.c (ffffffff8134df16)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/binfmt_elf.c (ffffffff81364914)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813681b9)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In block/partitions/check.c (ffffffff8150ad4c)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff829155f3)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/ethtool.c (ffffffff8194f9a3)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/packet/af_packet.c (ffffffff81aa6937)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/xdp/xsk_queue.c (ffffffff81ac4499)
Location: include/linux/overflow.h:253
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_swap
```
</details>
</li>
</ul>

## Differences
