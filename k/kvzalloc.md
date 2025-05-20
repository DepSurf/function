# Function: <code>kvzalloc</code>

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
In security/apparmor/match.c (ffffffff813791be)
Location: security/apparmor/include/lib.h:73
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff813b1f46)
Location: security/apparmor/include/lib.h:73
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff813c9106)
Location: security/apparmor/include/lib.h:74
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In mm/swap_slots.c (ffffffff811ec4d6)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/swap_state.c (ffffffff8120c506)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81210d48)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
```
```
In fs/xattr.c (ffffffff8127b7bb)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff8130f76d)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81334683)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/apparmor/match.c (ffffffff813de7af)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff813e6bbd)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff8146b847)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In net/core/dev.c (ffffffff817cb653)
Location: include/linux/mm.h:530
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fc3f)
Location: include/linux/mm.h:530
Inline: True
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
In mm/slab_common.c (ffffffff811fd49c)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swap_slots.c (ffffffff81202856)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/swap_state.c (ffffffff81225c86)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8122829e)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
```
```
In fs/xattr.c (ffffffff8129e25b)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff8133464d)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81358b93)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/apparmor/match.c (ffffffff8140513f)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8140dd3d)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff81497b37)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In net/core/dev.c (ffffffff81844eaa)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff8188bd50)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff818befdf)
Location: include/linux/mm.h:547
Inline: True
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
In mm/slab_common.c (ffffffff8121e7a2)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In fs/xattr.c (ffffffff812c49c6)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff8136290e)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81387510)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/apparmor/match.c (ffffffff8143622e)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f9b1)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff814ccacb)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In net/core/dev.c (ffffffff818910fb)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff818df844)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914be9)
Location: include/linux/mm.h:582
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
In mm/slab_common.c (ffffffff81231782)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffffffff81261586)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812940a2)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (ffffffff812d9bc6)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff8137ab1e)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813a0050)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In security/apparmor/match.c (ffffffff81452e4e)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8145c8a1)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff814e0f90)
Location: include/linux/mm.h:610
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5def)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff816fe7e0)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In net/core/dev.c (ffffffff818b172b)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff8190c3d4)
Location: include/linux/mm.h:610
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194339b)
Location: include/linux/mm.h:610
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
In mm/slab_common.c (ffffffff81241c12)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffffffff8127c4f6)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812b02d2)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (ffffffff812f8128)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff813a4cc2)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813ca39f)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff81420b56)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (ffffffff81480800)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81489e2b)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff8150ce47)
Location: include/linux/mm.h:676
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172f5bb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8173897d)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In net/core/dev.c (ffffffff818fe4cb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff8196df64)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a793f)
Location: include/linux/mm.h:676
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
In mm/slab_common.c (ffffffff8125009a)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffffffff8128bfd6)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812c1dc2)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (ffffffff81309d48)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff813bdb2d)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813e36a8)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff8143a946)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (ffffffff8149a509)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814a3ceb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff8152ac97)
Location: include/linux/mm.h:676
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81753a4b)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8175c67d)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (ffffffff8185d38f)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff819307fb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff819a4a14)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de9cf)
Location: include/linux/mm.h:676
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
In mm/slab_common.c (ffffffff8127e6da)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffffffff812bb595)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In fs/xattr.c (ffffffff81343ed8)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff81409aed)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81430a08)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff8148ad86)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/apparmorfs.c (ffffffff814ef59a)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:deflate_decompress
```
```
In security/apparmor/match.c (ffffffff814f2b26)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - security/apparmor/match.c:unpack_table
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcc11)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff8158e2a7)
Location: include/linux/mm.h:759
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8181252b)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8181be97)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a0763)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/input/evdev.c (ffffffff8193155d)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff81a0442b)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netif_alloc_rx_queues
```
```
In net/netfilter/core.c (ffffffff81a8db0a)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb6fc)
Location: include/linux/mm.h:759
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9b35)
Location: include/linux/mm.h:759
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create
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
In kernel/trace/trace.c (ffffffff811bd745)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
```
```
In mm/swapfile.c (ffffffff812c7035)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In fs/xattr.c (ffffffff81350248)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/proc/proc_sysctl.c (ffffffff813d922b)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff8141c8f3)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff814497b8)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff814a83a5)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/apparmorfs.c (ffffffff8150ca1a)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:deflate_decompress
```
```
In security/apparmor/match.c (ffffffff8150fcf6)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - security/apparmor/match.c:unpack_table
```
```
In security/apparmor/policy_unpack.c (ffffffff81519e61)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff815aada9)
Location: include/linux/mm.h:787
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8182177b)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8182aeeb)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818af703)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/input/evdev.c (ffffffff81938803)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff81a0648b)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netif_alloc_rx_queues
```
```
In net/netfilter/core.c (ffffffff81a97ada)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad769f)
Location: include/linux/mm.h:787
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9aabc)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9945)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In kernel/trace/trace.c (ffffffff811bd245)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
```
```
In mm/swapfile.c (ffffffff812cd975)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In fs/xattr.c (ffffffff81356d9b)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/proc/proc_sysctl.c (ffffffff813e06cb)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff81422f33)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff8144f128)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff814ae2f1)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/apparmorfs.c (ffffffff8151308b)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In security/apparmor/match.c (ffffffff81516a24)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81520771)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff815b58b9)
Location: include/linux/mm.h:810
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804a9a)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8180e1cb)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892e33)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/input/evdev.c (ffffffff8191c072)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff819ecfdb)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff81a82e2a)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac277d)
Location: include/linux/mm.h:810
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b899eb)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8925)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In kernel/trace/trace.c (ffffffff811e7d15)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
```
```
In mm/swapfile.c (ffffffff81312d15)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In fs/xattr.c (ffffffff813a585b)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/proc/proc_sysctl.c (ffffffff814320ff)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff81476714)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff814a2c8a)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff81508a1c)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:newary
```
```
In security/apparmor/apparmorfs.c (ffffffff81570c8b)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In security/apparmor/match.c (ffffffff81574a24)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8157e911)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff8161bd49)
Location: include/linux/mm.h:811
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188f0ca)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff818987db)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819258a7)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/input/evdev.c (ffffffff819be762)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff81a9e1eb)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff81b3ca7f)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b8062f)
Location: include/linux/mm.h:811
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c55afb)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76675)
Location: include/linux/mm.h:811
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In kernel/trace/trace.c (ffffffff8121db2e)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
```
```
In mm/swapfile.c (ffffffff8137d945)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In fs/xattr.c (ffffffff81429ab9)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - fs/xattr.c:do_getxattr
```
```
In fs/proc/proc_sysctl.c (ffffffff814acbcf)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff814f8a19)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff8152a114)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff8159961e)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:newary
```
```
In security/apparmor/apparmorfs.c (ffffffff8160b551)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In security/apparmor/match.c (ffffffff81612000)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - security/apparmor/match.c:unpack_table
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d1af)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff816e9739)
Location: include/linux/slab.h:756
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199e95a)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d85d9)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff819e26f9)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7e243)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/input/evdev.c (ffffffff81b1d5a5)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff81c12a0d)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff81cc94ee)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d109d4)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3a212)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/packet/af_packet.c (ffffffff81df1b34)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1af27)
Location: include/linux/slab.h:756
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In kernel/trace/trace.c (ffffffff812680be)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
```
```
In mm/swapfile.c (ffffffff813fac05)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In fs/xattr.c (ffffffff814b6c07)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - fs/xattr.c:do_getxattr
```
```
In fs/proc/proc_sysctl.c (ffffffff81542fef)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff81593139)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff815c8aa4)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff8164289e)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:newary
```
```
In security/apparmor/apparmorfs.c (ffffffff816bdb3e)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:decompress_zstd
```
```
In security/apparmor/match.c (ffffffff816c4d20)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - security/apparmor/match.c:unpack_table
```
```
In security/apparmor/policy_unpack.c (ffffffff816d053f)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff817d98c9)
Location: include/linux/slab.h:743
Inline: True
```
```
In drivers/acpi/property.c (ffffffff81974ea0)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_data_add_buffer_props
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b1032a)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b534c9)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff81b5e346)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (ffffffff81caf585)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff81dc2b2c)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/ethtool/common.c (ffffffff81e7c5bf)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/netfilter/core.c (ffffffff81e890be)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6734)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02b72)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/packet/af_packet.c (ffffffff81fc5b04)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2487)
Location: include/linux/slab.h:743
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In kernel/trace/trace.c (ffffffff8127f27e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
```
```
In mm/swapfile.c (ffffffff8142dc55)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In fs/xattr.c (ffffffff814eb90f)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/xattr.c:do_getxattr
```
```
In fs/proc/proc_sysctl.c (ffffffff8157b432)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff815ca17e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff8160085e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff8167ae31)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:newary
```
```
In security/apparmor/apparmorfs.c (ffffffff816f65f6)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:decompress_zstd
```
```
In security/apparmor/match.c (ffffffff816fdc25)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8170911f)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff81818c4a)
Location: include/linux/slab.h:726
Inline: True
```
```
In drivers/acpi/property.c (ffffffff819bb6f5)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_data_add_buffer_props
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5e3ea)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6971)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff81bb1906)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (ffffffff81d16b85)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff81e31fdc)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/ethtool/common.c (ffffffff81ed8957)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/netfilter/core.c (ffffffff81ee70ae)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f3568a)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6230b)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/packet/af_packet.c (ffffffff8202a04e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e6b7)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In kernel/trace/trace.c (ffffffff81299ffe)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
```
```
In mm/swapfile.c (ffffffff81467715)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In fs/xattr.c (ffffffff8151f7af)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - fs/xattr.c:do_getxattr
```
```
In fs/proc/proc_sysctl.c (ffffffff815b3ce2)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff81602f8e)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff816395ae)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/pstore/platform.c (ffffffff816ad458)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - fs/pstore/platform.c:decompress_record
  - fs/pstore/platform.c:pstore_register
```
```
In ipc/sem.c (ffffffff816b71fa)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:newary
```
```
In security/apparmor/apparmorfs.c (ffffffff81733356)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:decompress_zstd
```
```
In security/apparmor/match.c (ffffffff8173b1b7)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81746baf)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8179fb65)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_kvzalloc
```
```
In lib/rhashtable.c (ffffffff8185df7a)
Location: include/linux/slab.h:734
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951a0d)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/acpi/property.c (ffffffff81a05f25)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_data_add_buffer_props
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb1cfa)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfac21)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff81c05df6)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/gpu/drm/drm_property.c (ffffffff81cadd9b)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_create_blob
```
```
In drivers/input/evdev.c (ffffffff81dcc835)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff81ef0479)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/ethtool/common.c (ffffffff81f9c777)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/netfilter/core.c (ffffffff81faaebe)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/tcp_metrics.c (ffffffff83969956)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
```
```
In net/ipv4/fib_semantics.c (ffffffff820288db)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/packet/af_packet.c (ffffffff820f9b4d)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142737)
Location: include/linux/slab.h:734
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In virt/kvm/kvm_main.c (ffff8000100b7f88)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In mm/slab_common.c (ffff8000102e6ff4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffff8000103276f4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffff8000103662a4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (ffff8000103be450)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffff800010494758)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffff8000104bcc50)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffff8000105227f0)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (ffff8000105905b0)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffff800010599a5c)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffff800010635ddc)
Location: include/linux/mm.h:676
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c9f8c)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/nvdimm/dimm_devs.c (ffff80001095439c)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffff80001095ddb4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (ffff800010a9e288)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffff800010bcc724)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffff800010c53e00)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91b54)
Location: include/linux/mm.h:676
Inline: True
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
In mm/slab_common.c (c050b1b8)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (c053eb50)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (c0556938)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (c059b1cc)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (c06561d4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (c0680300)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (c06dd408)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (c0741308)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (c074abd0)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (c07dbcc8)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In drivers/input/evdev.c (c0b7f270)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In sound/core/info.c (c0c897e8)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - sound/core/info.c:snd_info_text_entry_write
```
```
In net/core/dev.c (c0ce6af8)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (c0d63840)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (c0da0860)
Location: include/linux/mm.h:676
Inline: True
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
In mm/slab_common.c (c0000000003a8b4c)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (c0000000003fe3b0)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (c000000000450a6c)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (c0000000004bc058)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (c0000000005bdbf4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (c0000000005f2b7c)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (c00000000066be90)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (c000000000703c80)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (c000000000710d1c)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (c0000000007dc340)
Location: include/linux/mm.h:676
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a019a4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (c000000000a0fa54)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (c000000000b7e964)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (c000000000caba58)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (c000000000d53710)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (c000000000da20bc)
Location: include/linux/mm.h:676
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
In mm/slab_common.c (ffffffe0001fcce4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffffffe0002275e4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffe000243090)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (ffffffe00027f0be)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffe000319412)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffe000338992)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffe000387d7e)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (ffffffe0003de032)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e6160)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffe000463b62)
Location: include/linux/mm.h:676
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3bc8)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffe0005cbe66)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (ffffffe0006adf40)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffe0007581aa)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffe0007be60a)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1bdc)
Location: include/linux/mm.h:676
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
In mm/slab_common.c (ffffffff812486ea)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffffffff812845b6)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812ba3a2)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (ffffffff81302328)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff813b610d)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813dbc88)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff81432f26)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (ffffffff81492ae9)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8149c2cb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff81523277)
Location: include/linux/mm.h:676
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8170813b)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff81710d6d)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (ffffffff8181239f)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff818d07fb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff81944884)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e83f)
Location: include/linux/mm.h:676
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
In mm/slab_common.c (ffffffff8123b69a)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffffffff81276426)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812ab562)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (ffffffff812f2f48)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff813a6b9d)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813cc708)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff814239a6)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (ffffffff81483509)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8148cceb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff81513557)
Location: include/linux/mm.h:676
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dbbbb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff816e47ed)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (ffffffff817d9adf)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff8188a6db)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff818fe374)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff819382ff)
Location: include/linux/mm.h:676
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
In mm/slab_common.c (ffffffff8124648a)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffffffff812823c6)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812b81b2)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (ffffffff81300118)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff813b396d)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813d9128)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff8142f0c6)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (ffffffff8148eb89)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8149836b)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff8151f307)
Location: include/linux/mm.h:676
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81746f0b)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8174fb3d)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (ffffffff8185151f)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff819217fb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff81995a14)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e900f)
Location: include/linux/mm.h:676
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
In mm/slab_common.c (ffffffff81255c9a)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swapfile.c (ffffffff812920b6)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812c8ae2)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/xattr.c (ffffffff81311458)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/xattr.c:getxattr
```
```
In fs/ext4/mballoc.c (ffffffff813c8503)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813ee418)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/sem.c (ffffffff81446236)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/apparmor/match.c (ffffffff814a6a99)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814b04bb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In lib/rhashtable.c (ffffffff81538d27)
Location: include/linux/mm.h:676
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8176234b)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8176afbd)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/input/evdev.c (ffffffff8186c33f)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/dev.c (ffffffff819401cb)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/netfilter/core.c (ffffffff819b85f4)
Location: include/linux/mm.h:676
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2d6f)
Location: include/linux/mm.h:676
Inline: True
```
</details>
</li>
</ul>

## Differences
