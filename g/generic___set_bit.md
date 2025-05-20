# Function: <code>generic___set_bit</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/ivm.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/workqueue.c (ffffffff81113401)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/shmem.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/file.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffffffff816fde42)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In io_uring/filetable.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/amd/init.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff81bdbf60)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be8642)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/socket.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/sock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/dev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/gro.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/pm.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/radix-tree.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/vsprintf.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
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
In arch/x86/events/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/ivm.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/workqueue.c (ffffffff8111fa01)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/shmem.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/file.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffffffff81737e62)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In io_uring/filetable.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/amd/init.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c4075d)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/socket.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/sock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/dev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/gro.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/pm.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/radix-tree.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/vsprintf.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
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
In arch/x86/events/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/ivm.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/workqueue.c (ffffffff81129f51)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/shmem.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/file.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffffffff81778952)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In io_uring/filetable.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In io_uring/register.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/bitmap-str.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/amd/init.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/iommu/iommufd/iova_bitmap.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/gpu/drm/drm_edid.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/gpu/drm/drm_mm.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf6046)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/socket.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/sock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/dev.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/gro.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/radix-tree.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/vsprintf.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/generic-non-atomic.h:28
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
