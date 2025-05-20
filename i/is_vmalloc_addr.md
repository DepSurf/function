# Function: <code>is_vmalloc_addr</code>

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
In kernel/memremap.c (0)
Location: include/linux/mm.h:377
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm.h:377
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/mm.h:377
Inline: True
```
```
In mm/vmalloc.c (ffffffff811ceaee)
Location: include/linux/mm.h:377
Inline: True
Inline callers:
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:377
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/linux/mm.h:377
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/mm.h:377
Inline: True
```
```
In drivers/spi/spi.c (ffffffff815e778c)
Location: include/linux/mm.h:377
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8160d579)
Location: include/linux/mm.h:377
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/mm.h:377
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/mm.h:377
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/mm.h:377
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/mm.h:377
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
In kernel/memremap.c (ffffffff8119dc25)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - kernel/memremap.c:memunmap
```
```
In mm/util.c (ffffffff811c48f5)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff811cafe6)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff811ebc7e)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In mm/memory_hotplug.c (ffffffff8120ef6f)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/match.c (ffffffff813b1fae)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1b35)
Location: include/linux/mm.h:481
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81645762)
Location: include/linux/mm.h:481
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8166d124)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/md/dm-stats.c (ffffffff8170e5cb)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In net/netlink/af_netlink.c (ffffffff817b73f1)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff81807f5c)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff818782ed)
Location: include/linux/mm.h:481
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/mm/fault.c (ffffffff8106e5d2)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/memremap.c (ffffffff811ad645)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - kernel/memremap.c:memunmap
```
```
In mm/util.c (ffffffff811d4a05)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff811db11b)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff811fceae)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff813c916e)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3b25)
Location: include/linux/mm.h:468
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81676eff)
Location: include/linux/mm.h:468
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8169ae21)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/md/dm-stats.c (ffffffff8174076b)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In net/netlink/af_netlink.c (ffffffff817e6e91)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff8183902c)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff818ac81f)
Location: include/linux/mm.h:468
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/mm/fault.c (ffffffff8106dd1f)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/memremap.c (ffffffff811b4b25)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - kernel/memremap.c:memunmap
```
```
In mm/util.c (ffffffff811dd825)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff811e4af9)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff81207bce)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff813de82a)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814ef905)
Location: include/linux/mm.h:502
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8168b60f)
Location: include/linux/mm.h:502
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff816afef0)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/md/dm-stats.c (ffffffff8175a43e)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In net/netlink/af_netlink.c (ffffffff81806be7)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a54c)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff818cf74d)
Location: include/linux/mm.h:502
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/ldt.c (ffffffff81031d35)
Location: include/linux/mm.h:519
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81072d2f)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/memremap.c (ffffffff811c8b95)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - kernel/memremap.c:memunmap
```
```
In mm/util.c (ffffffff811f32a5)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff811fad90)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff81220cbe)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff814051ba)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81524485)
Location: include/linux/mm.h:519
Inline: True
```
```
In drivers/spi/spi.c (ffffffff816f4f9f)
Location: include/linux/mm.h:519
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8171b46a)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/md/dm-stats.c (ffffffff817cc67e)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In net/netlink/af_netlink.c (ffffffff818858c7)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff818da46c)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff819546bd)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/ldt.c (ffffffff81032fdb)
Location: include/linux/mm.h:554
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810757c4)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/iomem.c (ffffffff811e90c5)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
```
```
In mm/util.c (ffffffff812144e5)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff8121c050)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff81242b5e)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff814362a3)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a1ef)
Location: include/linux/mm.h:554
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817326d5)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff8175a22e)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/md/dm-stats.c (ffffffff81815054)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In net/netlink/af_netlink.c (ffffffff818d9261)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff81930efe)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff819ae971)
Location: include/linux/mm.h:554
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/ldt.c (ffffffff810343d1)
Location: include/linux/mm.h:582
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8107b5ce)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/iomem.c (ffffffff811f9dd5)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
```
```
In mm/util.c (ffffffff812273b5)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff8122f030)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff8125729e)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff81452ec3)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571aff)
Location: include/linux/mm.h:582
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817550c5)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff8177e7ae)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/md/dm-stats.c (ffffffff81841064)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In net/netlink/af_netlink.c (ffffffff81905a51)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff819607fb)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff819e5091)
Location: include/linux/mm.h:582
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/ldt.c (ffffffff8103615c)
Location: include/linux/mm.h:643
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8107f0f4)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/iomem.c (ffffffff81211d45)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
```
```
In mm/util.c (ffffffff812370a5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff8123f033)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff8126861e)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff81480872)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (ffffffff814c6ba6)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a1fe3)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817911c5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817bce58)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/md/dm-stats.c (ffffffff81884266)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In net/netlink/af_netlink.c (ffffffff81966ca0)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff819c5384)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff81a54208)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/ldt.c (ffffffff81036a87)
Location: include/linux/mm.h:643
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81080184)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/iomem.c (ffffffff8121f535)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
```
```
In mm/util.c (ffffffff81245275)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff8124d493)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff81275ac7)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff8149a576)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (ffffffff814e0785)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c2e63)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81659389)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0505)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/spi/spi.c (ffffffff817b4db5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817ed8b4)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180ae81)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814a83)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81840e1a)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bc7e)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/md/dm-stats.c (ffffffff818b6186)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f36e5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/netlink/af_netlink.c (ffffffff8199d720)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff819fbf24)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff81a8ae18)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a6bc0)
Location: mm/vmalloc.c:45
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - kernel/iomem.c:devm_memremap_release
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - security/apparmor/match.c:unpack_table
  - security/apparmor/policy_unpack.c:deflate_compress
  - block/blk-map.c:bio_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/md/dm-stats.c:dm_stats_delete
  - drivers/md/dm-stats.c:dm_stats_delete
  - drivers/md/dm-stats.c:dm_stats_delete
  - drivers/md/dm-stats.c:dm_stats_delete
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff812a6bc0-ffffffff812a6c0b: is_vmalloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b2060)
Location: mm/vmalloc.c:45
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/iomem.c:devm_memremap_release
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - security/apparmor/match.c:unpack_table
  - security/apparmor/policy_unpack.c:deflate_compress
  - block/blk-map.c:bio_map_kern
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/md/dm-stats.c:dm_stats_delete
  - drivers/md/dm-stats.c:dm_stats_delete
  - drivers/md/dm-stats.c:dm_stats_delete
  - drivers/md/dm-stats.c:dm_stats_delete
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff812b2060-ffffffff812b20ab: is_vmalloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7730)
Location: mm/vmalloc.c:58
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/iomem.c:devm_memremap_release
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:deflate_compress
  - block/blk-map.c:blk_rq_map_kern
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff812b7730-ffffffff812b777b: is_vmalloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812f9e40)
Location: mm/vmalloc.c:73
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/iomem.c:devm_memremap_release
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:deflate_compress
  - block/blk-map.c:blk_rq_map_kern
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff812f9e40-ffffffff812f9e8b: is_vmalloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81360130)
Location: mm/vmalloc.c:75
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/mm/fault.c:page_fault_oops
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/iomem.c:devm_memremap_release
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/usercopy.c:check_heap_object
  - security/apparmor/match.c:unpack_table
  - security/apparmor/match.c:unpack_table
  - security/apparmor/policy_unpack.c:compress_zstd
  - block/blk-map.c:blk_rq_map_kern
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff81360130-ffffffff81360177: is_vmalloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813db220)
Location: mm/vmalloc.c:78
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/mm/fault.c:page_fault_oops
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/iomem.c:devm_memremap_release
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/usercopy.c:check_heap_object
  - security/apparmor/match.c:unpack_table
  - security/apparmor/match.c:unpack_table
  - security/apparmor/policy_unpack.c:compress_zstd
  - block/blk-map.c:blk_rq_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff813db220-ffffffff813db27a: is_vmalloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8140f9a0)
Location: mm/vmalloc.c:78
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/mm/fault.c:page_fault_oops
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/iomem.c:devm_memremap_release
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/usercopy.c:check_heap_object
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:compress_zstd
  - block/blk-map.c:blk_rq_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff8140f9a0-ffffffff8140f9fa: is_vmalloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143c300)
Location: mm/vmalloc.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/mm/fault.c:page_fault_oops
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/usercopy.c:check_heap_object
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:compress_zstd
  - block/blk-map.c:blk_rq_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_delete
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff8143c300-ffffffff8143c35a: is_vmalloc_addr (STB_GLOBAL)
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
In arch/arm64/mm/ioremap.c (ffff8000100adf24)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - arch/arm64/mm/ioremap.c:iounmap
```
```
In virt/kvm/arm/mmu.c (0)
Location: include/linux/mm.h:643
Inline: True
```
```
In kernel/iomem.c (ffff8000102ab96c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
```
```
In mm/util.c (ffff8000102d8240)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffff8000102e3dfc)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffff80001030bee8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In security/apparmor/match.c (ffff800010590610)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (ffff8000105dd2ec)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c23c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/dma/mv_xor.c (ffff8000108074b0)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816414)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
```
```
In drivers/virtio/virtio_ring.c (ffff80001082262c)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bac8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a39b4)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c9224)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_free
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb434)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d9358)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/spi/spi.c (ffff8000109c84fc)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e3644)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eb768)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/usb/core/hcd.c (ffff800010a1c820)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a417e0)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4dc48)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7f86c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b994)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/md/dm-stats.c (ffff800010b0e150)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/firmware/qcom_scm-64.c (ffff800010b4f9c8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7f3b0)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/netlink/af_netlink.c (ffff800010c4abc8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3a20)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffff800010d56fc8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:__packet_get_status
  - net/packet/af_packet.c:__packet_get_status
  - net/packet/af_packet.c:__packet_set_status
  - net/packet/af_packet.c:__packet_set_status
  - net/packet/af_packet.c:__packet_set_status
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
In kernel/iomem.c (c04d8d60)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
```
```
In mm/util.c (c04ff650)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (c05080d0)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (c0528008)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (c0741368)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (c078a758)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (c08ce824)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/dma/mv_xor.c (c092524c)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/virtio/virtio_ring.c (c093f6c8)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c0989400)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/msm_serial.c (c099cc38)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/iommu/io-pgtable-arm.c (c09bff54)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/omap-iommu.c (c09c47b8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c6d30)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/iommu/exynos-iommu.c (c09ca6f8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
```
```
In drivers/spi/spi.c (c0ab2098)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acdb2c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad7138)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
```
```
In drivers/usb/core/hcd.c (c0af57ac)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c0b13f6c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b1fd30)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (c0b52c28)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5dd9c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/gadget/udc/core.c (c0b73d8c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9a948)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
```
```
In drivers/md/dm-stats.c (c0bec534)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/mmc/host/sdhci.c (c0c24c18)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
```
```
In drivers/firmware/qcom_scm-32.c (c0c36218)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
```
```
In drivers/firmware/tegra/ivc.c (c0c43910)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5c1ec)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (c0c62b14)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/netlink/af_netlink.c (c0d5b7a8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (c0dbf2bc)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (c0e585ec)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_current_block
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
In mm/util.c (c000000000397f3c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (c0000000003a44b4)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (c0000000003dbec0)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (c000000000703ce4)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (c00000000076e9e8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008addc4)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/virtio/virtio_ring.c (c0000000008ccb2c)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c0000000009343dc)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c000000000969100)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt
```
```
In drivers/spi/spi.c (c000000000a89cc0)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (c000000000ad7cb8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0250c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15460)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (c000000000b583ac)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67904)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/md/dm-stats.c (c000000000c00e60)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b558)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/netlink/af_netlink.c (c000000000d48ca8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (c000000000dcb2b0)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (c000000000e91708)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_current_block
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
In kernel/iomem.c (ffffffe0001d353c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
```
```
In mm/util.c (ffffffe0001f2b60)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffe0001fa6da)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffe000215380)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffe0003de01c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (ffffffe000420482)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9bf6)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffe000518f16)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe000555442)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/spi/spi.c (ffffffe00061899e)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffe000641580)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffe00065d80e)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066a690)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000696000)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a06fe)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/md/dm-stats.c (ffffffe0006fb1a2)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071baba)
Location: include/linux/mm.h:643
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007b7f58)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b836)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffe00088e7d6)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:__packet_get_status
  - net/packet/af_packet.c:__packet_get_status
  - net/packet/af_packet.c:__packet_set_status
  - net/packet/af_packet.c:__packet_set_status
  - net/packet/af_packet.c:__packet_set_status
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
In arch/x86/kernel/ldt.c (ffffffff81036be7)
Location: include/linux/mm.h:643
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8107f184)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/iomem.c (ffffffff81217b85)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
```
```
In mm/util.c (ffffffff8123d8c5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff81245ae3)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff8126e117)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff81492b56)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (ffffffff814d8d65)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b6fb3)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161f229)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81675f75)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/spi/spi.c (ffffffff81779895)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817a5c94)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c3261)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cce63)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f91ca)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/md/dm-stats.c (ffffffff8185c006)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81894a15)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/netlink/af_netlink.c (ffffffff8193d590)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff8199bcc4)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff81a2a4a8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/ldt.c (ffffffff81026517)
Location: include/linux/mm.h:643
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106e167)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/iomem.c (ffffffff8120ad95)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
```
```
In mm/util.c (ffffffff812308c5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff81238a93)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff812600c7)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff81483576)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (ffffffff814c9715)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a5d93)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81613849)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81655055)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb889)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_do_bvec
```
```
In drivers/spi/spi.c (ffffffff81759645)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817981c4)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817be36a)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c91ce)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/md/dm-stats.c (ffffffff818235d6)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/hv/channel.c (ffffffff81850a05)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/hv/channel.c:virt_to_hvpfn
```
```
In net/netlink/af_netlink.c (ffffffff818f7090)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff81955784)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff819e7698)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/ldt.c (ffffffff81036a47)
Location: include/linux/mm.h:643
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8107f134)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/iomem.c (ffffffff81215925)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
```
```
In mm/util.c (ffffffff8123b665)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff81243883)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff8126beb7)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff8148ebf6)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (ffffffff814d4df5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b7543)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8164d1c9)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a4345)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/spi/spi.c (ffffffff817a9c35)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817e2734)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817ffd01)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809903)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81835c9a)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840afe)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868f68)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
```
In drivers/md/dm-stats.c (ffffffff818ab636)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In net/netlink/af_netlink.c (ffffffff8198e720)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nfnetlink.c (ffffffff819988e3)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06564)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff81a96058)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/ldt.c (ffffffff81037947)
Location: include/linux/mm.h:643
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81081224)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/iomem.c (ffffffff81224925)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
```
```
In mm/util.c (ffffffff8124ad75)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/util.c:kvfree
```
```
In mm/percpu.c (ffffffff81253043)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff8127b9f7)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:is_vmalloc_or_module_addr
```
```
In security/apparmor/match.c (ffffffff814a6b06)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In block/bio.c (ffffffff814ed9a5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d0fb3)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81667859)
Location: include/linux/mm.h:643
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816be7d5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/spi/spi.c (ffffffff817c3ac5)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817fd484)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81819e11)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823a13)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184ffd0)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185afce)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/md/dm-stats.c (ffffffff818c7876)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905175)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/netlink/af_netlink.c (ffffffff819b0fd0)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10be4)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/packet/af_packet.c (ffffffff81aa2cc8)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:free_pg_vec
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
