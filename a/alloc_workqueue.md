# Function: <code>alloc_workqueue</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bea00)
Location: kernel/workqueue.c:4211
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff810bea00-ffffffff810bee48: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4fb0)
Location: kernel/workqueue.c:4229
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff810c4fb0-ffffffff810c53b0: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cc9d0)
Location: kernel/workqueue.c:4238
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/trace/trace.c:latency_fsnotify_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/zswap.c:init_zswap
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
  - net/mptcp/pm.c:mptcp_pm_init
```
**Symbols:**

```
ffffffff810cc9d0-ffffffff810ccc69: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7b50)
Location: kernel/workqueue.c:4251
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:latency_fsnotify_init
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/zswap.c:init_zswap
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff810c7b50-ffffffff810c7de9: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c95e0)
Location: kernel/workqueue.c:4258
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:latency_fsnotify_init
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/zswap.c:init_zswap
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff810c95e0-ffffffff810c9879: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4297
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:latency_fsnotify_init
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/zswap.c:init_zswap
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/iommu/io-pgfault.c:iopf_queue_alloc
  - drivers/block/loop.c:loop_configure
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff81ca54af-ffffffff81ca54d8: alloc_workqueue.cold (STB_LOCAL)
ffffffff810dc2e0-ffffffff810dc7b6: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4280
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/trace/ftrace.c:ftrace_check_for_weak_functions
  - kernel/trace/trace.c:trace_eval_init
  - kernel/trace/trace.c:latency_fsnotify_init
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/zswap.c:init_zswap
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:__ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/iommu/io-pgfault.c:iopf_queue_alloc
  - drivers/block/loop.c:loop_configure
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff81e54d83-ffffffff81e54dac: alloc_workqueue.cold (STB_LOCAL)
ffffffff810f5a40-ffffffff810f5f42: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4289
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/trace/ftrace.c:ftrace_check_for_weak_functions
  - kernel/trace/trace.c:trace_eval_init
  - kernel/trace/trace.c:latency_fsnotify_init
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init_late
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:__ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/iommu/io-pgfault.c:iopf_queue_alloc
  - drivers/block/loop.c:loop_configure
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff8205675b-ffffffff82056784: alloc_workqueue.cold (STB_LOCAL)
ffffffff81117f80-ffffffff8111848d: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4622
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/trace/ftrace.c:ftrace_check_for_weak_functions
  - kernel/trace/trace.c:trace_eval_init
  - kernel/trace/trace.c:latency_fsnotify_init
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - mm/slub.c:kmem_cache_init_late
  - fs/super.c:sb_init_dio_done_wq
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:__ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_punt_bio_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/iommu/io-pgfault.c:iopf_queue_alloc
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtio_blk_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-stripe.c:dm_stripe_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff820d4dca-ffffffff820d4df3: alloc_workqueue.cold (STB_LOCAL)
ffffffff811251a0-ffffffff811256c5: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4662
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/trace/ftrace.c:ftrace_check_for_weak_functions
  - kernel/trace/trace.c:trace_eval_init
  - kernel/trace/trace.c:latency_fsnotify_init
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/slub.c:kmem_cache_init_late
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - fs/super.c:sb_init_dio_done_wq
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:__ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_punt_bio_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/iommu/io-pgfault.c:iopf_queue_alloc
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtio_blk_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-stripe.c:dm_stripe_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff821afcb1-ffffffff821afcda: alloc_workqueue.cold (STB_LOCAL)
ffffffff8112f9a0-ffffffff8112fcc9: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff8000101234a8)
Location: kernel/workqueue.c:4229
Inline: False
Direct callers:
  - virt/kvm/eventfd.c:kvm_irqfd_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/soc/fsl/qbman/qman.c:qman_wq_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffff8000101234a8-ffff8000101238a0: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0376da0)
Location: kernel/workqueue.c:4229
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
c0376da0-c0377164: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016d460)
Location: kernel/workqueue.c:4229
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
c00000000016d460-c00000000016d944: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000dbc44)
Location: kernel/workqueue.c:4229
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffe0000dbc44-ffffffe0000dc01e: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bf320)
Location: kernel/workqueue.c:4229
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff810bf320-ffffffff810bf720: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810adb40)
Location: kernel/workqueue.c:4229
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/nfit/core.c:nfit_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_transport_fc.c:fc_host_setup
  - drivers/scsi/scsi_transport_fc.c:fc_host_setup
  - drivers/scsi/storvsc_drv.c:storvsc_probe
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/hv/connection.c:vmbus_connect
  - drivers/hv/connection.c:vmbus_connect
  - drivers/hv/connection.c:vmbus_connect
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff810adb40-ffffffff810adf40: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810be880)
Location: kernel/workqueue.c:4229
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff810be880-ffffffff810bec80: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct workqueue_struct *alloc_workqueue(const char *fmt, unsigned int flags, int max_active, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6bf0)
Location: kernel/workqueue.c:4229
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-cgroup.c:blkcg_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/vfio/virqfd.c:vfio_virqfd_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_dev_init
```
**Symbols:**

```
ffffffff810c6bf0-ffffffff810c6ff0: alloc_workqueue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
