# Function: <code>__arch_hweight32</code>

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
In arch/x86/events/intel/rapl.c (ffffffff81f5fe81)
Location: arch/x86/include/asm/arch_hweight.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff81f7585a)
Location: arch/x86/include/asm/arch_hweight.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff8123b53e)
Location: arch/x86/include/asm/arch_hweight.h:26
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In block/cfq-iosched.c (ffffffff813dec47)
Location: arch/x86/include/asm/arch_hweight.h:26
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In lib/memweight.c (ffffffff813fe11f)
Location: arch/x86/include/asm/arch_hweight.h:26
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151fcd0)
Location: arch/x86/include/asm/arch_hweight.h:26
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8164b58d)
Location: arch/x86/include/asm/arch_hweight.h:26
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/extcon/extcon.c (ffffffff816ee8d9)
Location: arch/x86/include/asm/arch_hweight.h:26
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_update_state
```
```
In net/netlink/af_netlink.c (ffffffff8174dc79)
Location: arch/x86/include/asm/arch_hweight.h:26
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/kernel/aperture_64.c (ffffffff81f9dfb9)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff812633f5)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In block/cfq-iosched.c (ffffffff81429bde)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:__cfq_slice_expired
```
```
In lib/memweight.c (ffffffff8144578e)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81572b2b)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816b0029)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/extcon/extcon.c (ffffffff817539db)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_update_state
```
```
In net/netlink/af_netlink.c (ffffffff817b9dbb)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/kernel/aperture_64.c (ffffffff81fd953c)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff81276845)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In block/cfq-iosched.c (ffffffff81443afc)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:__cfq_slice_expired
```
```
In lib/memweight.c (ffffffff81463f7e)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159f1a1)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816de1c9)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/hwmon/hwmon.c (ffffffff8171402c)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8177ffab)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/netlink/af_netlink.c (ffffffff817e975b)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/kernel/aperture_64.c (ffffffff820ba398)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff81283ccc)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In block/cfq-iosched.c (ffffffff81452b6e)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:__cfq_slice_expired
```
```
In lib/memweight.c (ffffffff81469000)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff815b3052)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816f20d9)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/hwmon/hwmon.c (ffffffff8172c4cd)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/extcon/extcon.c (ffffffff8179e54c)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffffffff817e2133)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff8180942e)
Location: arch/x86/include/asm/arch_hweight.h:22
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a07d)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff826c0d47)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff812a687c)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In block/cfq-iosched.c (ffffffff8147dffc)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:__cfq_slice_expired
```
```
In lib/memweight.c (ffffffff814952d0)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81619c92)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8175e3bb)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/hwmon/hwmon.c (ffffffff8179dc9a)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/extcon/extcon.c (ffffffff818156ac)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffffffff8185cca7)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81888420)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aa5d)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff826eaf6e)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff812cd43e)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In block/cfq-iosched.c (ffffffff814b3e3b)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:__cfq_slice_expired
```
```
In lib/memweight.c (ffffffff814ca68d)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816538fe)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8179ef08)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/hwmon/hwmon.c (ffffffff817e5244)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/extcon/extcon.c (ffffffff8185f579)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffffffff818a8868)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff818dbdba)
Location: arch/x86/include/asm/arch_hweight.h:23
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b22d)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828a1b7d)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff812e2761)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff814df3bb)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81671afe)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/spi/spi-mem.c (ffffffff817567f5)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/usb/host/xhci.c (ffffffff817c4fd7)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/hwmon/hwmon.c (ffffffff81810cd7)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/extcon/extcon.c (ffffffff8187ef19)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffffffff818cc9ed)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81908775)
Location: arch/x86/include/asm/arch_hweight.h:17
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ccce)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828b9e51)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff813007b5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff8150b20b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816a7827)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/spi/spi-mem.c (ffffffff81792cf5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/usb/host/xhci.c (ffffffff81800ffe)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81852b7f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/soundwire/mipi_disco.c (ffffffff818c30d4)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
```
```
In drivers/soundwire/stream.c (ffffffff818c402c)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/soundwire/stream.c:sdw_get_slave_dpn_prop
  - drivers/soundwire/stream.c:sdw_get_slave_dpn_prop
```
```
In drivers/extcon/extcon.c (ffffffff818c9517)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffffffff819199bd)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81969a5d)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d64e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828c0312)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff81312e1c)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff8152902b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816ca565)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/spi/spi-mem.c (ffffffff817b6845)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d67af)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/usb/host/xhci.c (ffffffff818320ae)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81884758)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818fb967)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffffffff8194bfdd)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff819a04e3)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e25e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
```
```
In arch/x86/kernel/aperture_64.c (ffffffff82ce46b1)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In fs/fs-writeback.c (ffffffff8134c77c)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff8158c8db)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8177f116)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/spi/spi-mem.c (ffffffff8187d665)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a47fd)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/usb/host/xhci.c (ffffffff819044f9)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81952f87)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2566)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a1caac)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81a79ce1)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e87e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
```
```
In arch/x86/kernel/aperture_64.c (ffffffff82fd1f12)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In fs/fs-writeback.c (ffffffff81359786)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff815a934b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81c097ea)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/spi/spi-mem.c (ffffffff8188bb95)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b38a4)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/usb/host/xhci.c (ffffffff8190cd79)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81957df7)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2146)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/core/dev.c (ffffffff81a00555)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/rtnetlink.c (ffffffff81a1ce8a)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81a82b4f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101fcae)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
```
```
In arch/x86/kernel/aperture_64.c (ffffffff831dcb13)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In fs/namespace.c (ffffffff8134d431)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81360391)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff815b3f4b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81bfb18e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/spi/spi-mem.c (ffffffff8186e4f5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81896a83)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/usb/host/xhci.c (ffffffff818f02e9)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff8193ba37)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a82d2)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_get_low_power_modes
```
```
In drivers/extcon/extcon.c (ffffffff819b73a6)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/core/dev.c (ffffffff819e69d5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/rtnetlink.c (ffffffff81a03fb3)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81a6bc2d)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102314e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
```
```
In arch/x86/kernel/aperture_64.c (ffffffff832bfbe8)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In fs/namespace.c (ffffffff8139b401)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813add71)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In fs/io_uring.c (ffffffff813e6b9f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_timeout_prep
```
```
In security/tomoyo/util.c (ffffffff8156c8e8)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
```
In lib/memweight.c (ffffffff8161a14b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81cfbd59)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/spi/spi-mem.c (ffffffff818fe595)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192aa15)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In drivers/usb/host/xhci.c (ffffffff8198cf89)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff819e0267)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a55907)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_low_power_modes
```
```
In drivers/extcon/extcon.c (ffffffff81a65f56)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/core/dev.c (ffffffff81a9b265)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/rtnetlink.c (ffffffff81ab659b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81b25259)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bb51)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81026f1d)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
```
```
In arch/x86/kernel/aperture_64.c (ffffffff8347209b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In fs/namespace.c (ffffffff8141f4a7)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81433ad2)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In security/tomoyo/util.c (ffffffff81608cde)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
```
In io_uring/io_uring.c (ffffffff816d55c2)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_timeout_prep
  - io_uring/io_uring.c:io_timeout_remove_prep
```
```
In lib/memweight.c (ffffffff816e772b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/regulator/irq_helpers.c (ffffffff818ed7ae)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_irq_map_event_simple
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81ec44ff)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/spi/spi-mem.c (ffffffff81a4fe25)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a81369)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In drivers/usb/host/xhci.c (ffffffff81ae91b9)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81b44f46)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff834bff59)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc510f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_low_power_modes
```
```
In drivers/extcon/extcon.c (ffffffff81bd7505)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/core/dev.c (ffffffff81c14931)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/rtnetlink.c (ffffffff81c3024a)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81cacd4e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb5e1)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c67d)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
```
```
In arch/x86/kernel/aperture_64.c (ffffffff83e9954f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In fs/namespace.c (ffffffff814a9edf)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814c13c2)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In security/tomoyo/util.c (ffffffff816ba5f0)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
```
In io_uring/timeout.c (ffffffff81799202)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove_prep
```
```
In lib/memweight.c (ffffffff817d755b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a4529e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_irq_map_event_simple
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aa085e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/spi/spi-mem.c (ffffffff81bd8f05)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/usb/host/xhci.c (ffffffff81c75489)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdc0b6)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83efec06)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6d16f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_low_power_modes
```
```
In drivers/extcon/extcon.c (ffffffff81d83e25)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/core/dev.c (ffffffff81dc5a71)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/rtnetlink.c (ffffffff81de3552)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81e6a5ee)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
```
In net/netlink/genetlink.c (ffffffff81e6eb85)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf221)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c6cd)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
```
```
In arch/x86/kernel/aperture_64.c (ffffffff836bcf6f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In fs/namespace.c (ffffffff814dedb5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814f6752)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In security/tomoyo/util.c (ffffffff816f2f86)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
```
In io_uring/timeout.c (ffffffff817da28f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove_prep
```
```
In lib/memweight.c (ffffffff8181676b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a8f44e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_irq_map_event_simple
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aec179)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/spi/spi-mem.c (ffffffff81c2f8f5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/usb/host/xhci.c (ffffffff81cdc939)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81d440d6)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83724a76)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81dda633)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_low_power_modes
```
```
In drivers/extcon/extcon.c (ffffffff81df2215)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/core/dev.c (ffffffff81e34ed1)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/rtnetlink.c (ffffffff81e5498a)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81ec65be)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
```
In net/netlink/genetlink.c (ffffffff81ecac95)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820201b1)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8103282d)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
```
```
In arch/x86/kernel/aperture_64.c (ffffffff838eda2f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In fs/super.c (ffffffff814e4c53)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
```
```
In fs/namespace.c (ffffffff81511ba5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8152ae92)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In security/selinux/ss/avtab.c (ffffffff816fa333)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/tomoyo/util.c (ffffffff8172fd46)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
```
In io_uring/timeout.c (ffffffff8181e57f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove_prep
```
```
In lib/memweight.c (ffffffff8185ba4b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/regulator/irq_helpers.c (ffffffff81ae1cbe)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_irq_map_event_simple
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81b3f6b9)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/gpu/drm/drm_blend.c (ffffffff81c7f336)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_blend_mode_property
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c891f0)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_getconnector
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_scaling_mode_property
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_scaling_mode_property
```
```
In drivers/gpu/drm/drm_plane.c (ffffffff81cabbd3)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_plane.c:drm_create_scaling_filter_prop
```
```
In drivers/gpu/drm/drm_crtc_helper.c (ffffffff81cc7399)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc_helper.c:drm_connector_get_single_encoder
```
```
In drivers/spi/spi-mem.c (ffffffff81ce27b5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/usb/host/xhci.c (ffffffff81d91959)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfaaa6)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff839588e6)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
```
```
In drivers/extcon/extcon.c (ffffffff81ea8865)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/core/dev.c (ffffffff81ef2f71)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/rtnetlink.c (ffffffff81f13d00)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81f8982e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
```
In net/netlink/genetlink.c (ffffffff81f8d3c5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef2e1)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
  - net/ipv6/ioam6_iptunnel.c:ioam6_validate_trace_hdr
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
In fs/fs-writeback.c (ffff8000103c8338)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106b00f0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
```
```
In drivers/usb/host/xhci.c (ffff800010a72f60)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/hwmon/hwmon.c (ffff800010ad1440)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In drivers/extcon/extcon.c (ffff800010b88b14)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffff800010bed464)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffff800010c4eadc)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/arm/kernel/setup.c (c1504e00)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/smp.c (c1505ca8)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_prepare_cpus
```
```
In arch/arm/kernel/machine_kexec.c (c03151cc)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_kexec_prepare
```
```
In arch/arm/probes/kprobes/checkers-common.c (c032826c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/checkers-common.c:checker_stack_use_stmdx
```
```
In arch/arm/mach-exynos/exynos.c (c032cbf4)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion
```
```
In arch/arm/mach-mvebu/platsmp.c (c150e588)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_init_cpus
```
```
In kernel/workqueue.c (c0371710)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (c0377da0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In kernel/sched/core.c (c038d180)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (c039b8d4)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In kernel/sched/deadline.c (c03a55ac)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (c03a873c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (c03ae5fc)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (c03b1560)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/printk/printk.c (c03c85b0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In kernel/irq/affinity.c (c03d6e50)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (c03df5e4)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (c03fbe80)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (c03ffc6c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (c1523684)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (c0405524)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (c04248c0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (c0428d78)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (c04396d4)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (c0441cd4)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (c04434c0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (c0444670)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (c0493c74)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (c04aaab8)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (c04ad4c0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (c04adce8)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (c04aeb18)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (c04b0180)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In kernel/bpf/devmap.c (c04b6f8c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (c04b7af0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In kernel/bpf/xskmap.c (c04b8d00)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In kernel/padata.c (c04d81d0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (c0501f08)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (c152e4a0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/percpu.c (c050818c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In fs/fs-writeback.c (c05a4224)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In fs/aio.c (c05d096c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In lib/bitmap.c (c07d2560)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In lib/bucket_locks.c (c07ddc10)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/sbitmap.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In drivers/irqchip/irq-gic.c (c08152bc)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_get_cpumask
```
```
In drivers/bus/brcmstb_gisb.c (c154eb20)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853a1c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
```
```
In drivers/dma/mv_xor.c (c0925324)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In drivers/soc/tegra/flowctrl.c (c093ad48)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/soc/tegra/flowctrl.c:flowctrl_cpu_suspend_enter
```
```
In drivers/base/arch_topology.c (c1598d24)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/mtd/nand/raw/nand_base.c (c0a9b314)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_check_erased_buf
```
```
In drivers/usb/host/xhci.c (c0b46c4c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/input/input.c (c0b7a7bc)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/hwmon/hwmon.c (c0bb2190)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
```
In drivers/thermal/thermal_core.c (c0bb57ec)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
```
```
In drivers/thermal/cpu_cooling.c (c0bbc8e0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_state2power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/md/dm-stats.c (c0beb2d8)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff58c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpuidle/coupled.c (c0c05088)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:coupled_cpu_online
  - drivers/cpuidle/coupled.c:cpuidle_coupled_register_device
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c0c344e4)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/firmware/qcom_scm.c (c0c35654)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
```
```
In drivers/extcon/extcon.c (c0c6cfd8)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In drivers/perf/arm-cci.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In drivers/perf/arm-ccn.c (c0c7c550)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_active_counters
```
```
In drivers/perf/arm_pmu.c (c0c7eb04)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
```
In sound/soc/soc-pcm.c (c0cb0254)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - sound/soc/soc-pcm.c:soc_pcm_codec_params_fixup
```
```
In net/core/dev.c (c0cea738)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/ethtool.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: False
```
```
In net/core/rtnetlink.c (c0d059ec)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/net-sysfs.c (c0d2377c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (c0d48534)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/netlink/af_netlink.c (c0d5ebf0)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
```
In net/ipv4/inet_hashtables.c (c0d78d04)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - fs/fs-writeback.c:wbc_detach_inode
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - net/core/rtnetlink.c:do_setlink
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
**Symbols:**

```
c0000000000b3b98-c0000000000b3b98: __arch_hweight32 (STB_GLOBAL)
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
In fs/fs-writeback.c (ffffffe000286d52)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In drivers/usb/host/xhci.c (ffffffe00068b44c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
```
In drivers/hwmon/hwmon.c (ffffffe0006cde40)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffe00073166c)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
```
```
In net/core/rtnetlink.c (ffffffe00076f97e)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffe0007ba9ac)
Location: include/asm-generic/bitops/arch_hweight.h:7
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d64e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828ab2e8)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff8130b3fc)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff8152160b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8168ffb5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/spi/spi-mem.c (ffffffff8177b325)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/usb/host/xhci.c (ffffffff817ea48e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff8182a5d8)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8189cc97)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffffffff818ebfad)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff81940353)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ceee)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828a35af)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff812fc01c)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff815118fb)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8166d9a5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/spi/spi-mem.c (ffffffff8175b0d5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff8178085f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/usb/host/xhci.c (ffffffff817af59e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff817f1c68)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818a5ded)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff818f9e43)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d60e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828be1e7)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff813091ec)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff8151d69b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816be225)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/spi/spi-mem.c (ffffffff817ab6c5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cb62f)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/usb/host/xhci.c (ffffffff81826f2e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81879c08)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818ec387)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffffffff8193cfdd)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff819914e3)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d85e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828c1334)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In fs/fs-writeback.c (ffffffff8131aefc)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In lib/memweight.c (ffffffff81536f0b)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816d87f5)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/spi/spi-mem.c (ffffffff817c5655)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e58cf)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/usb/host/xhci.c (ffffffff81840e0e)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81895608)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8190d407)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
```
In net/core/rtnetlink.c (ffffffff8195e85c)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/netlink/af_netlink.c (ffffffff819b3f62)
Location: arch/x86/include/asm/arch_hweight.h:15
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
</details>
</li>
</ul>

## Differences
