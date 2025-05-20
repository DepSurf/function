# Function: <code>pde_data</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d55aa)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - kernel/resource.c:r_show
  - kernel/resource.c:r_start
```
```
In kernel/irq/proc.c (ffffffff8116c839)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
```
```
In fs/ext4/mballoc.c (ffffffff814efa35)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_next
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_start
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
```
```
In fs/jbd2/journal.c (ffffffff81548665)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_open
```
```
In ipc/util.c (ffffffff8159387f)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In drivers/pci/proc.c (ffffffff817dd725)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_lseek
```
```
In drivers/acpi/proc.c (ffffffff8182a4a9)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
```
```
In drivers/scsi/scsi_proc.c (ffffffff81a0a469)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:proc_scsi_host_open
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
```
```
In net/core/neighbour.c (ffffffff81c22c95)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_show
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0abbd)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81d15a55)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81d1ab92)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
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
In kernel/resource.c (ffffffff810f45aa)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - kernel/resource.c:r_show
  - kernel/resource.c:r_start
```
```
In kernel/irq/proc.c (ffffffff811a1899)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
```
```
In fs/ext4/mballoc.c (ffffffff81589d75)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_next
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_start
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
```
```
In fs/jbd2/journal.c (ffffffff815e8225)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_open
```
```
In ipc/util.c (ffffffff8163c3ff)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In drivers/pci/proc.c (ffffffff81900405)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_lseek
```
```
In drivers/acpi/proc.c (ffffffff8195c9e9)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
```
```
In drivers/scsi/scsi_proc.c (ffffffff81b89b89)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:proc_scsi_host_open
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
```
```
In net/core/neighbour.c (ffffffff81dd4cd5)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_show
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0494)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81edbe15)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81ee2583)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
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
In kernel/resource.c (ffffffff811009da)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - kernel/resource.c:r_show
  - kernel/resource.c:r_start
```
```
In kernel/irq/proc.c (ffffffff811b36b9)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
```
```
In fs/ext4/mballoc.c (ffffffff815c05b5)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_next
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_start
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
```
```
In fs/jbd2/journal.c (ffffffff8161fb35)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_open
```
```
In ipc/util.c (ffffffff8167487f)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In drivers/pci/proc.c (ffffffff81943995)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_lseek
```
```
In drivers/acpi/proc.c (ffffffff819a30c9)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
```
```
In drivers/scsi/scsi_proc.c (ffffffff81bdda79)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:proc_scsi_host_open
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
```
```
In net/core/neighbour.c (ffffffff81e45a55)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_show
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2f144)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81f3b055)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_seq_start
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81f40302)
Location: include/linux/proc_fs.h:118
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_get_first
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
In kernel/resource.c (ffffffff8110a30a)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - kernel/resource.c:r_show
  - kernel/resource.c:r_start
```
```
In kernel/irq/proc.c (ffffffff811c3539)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
```
```
In fs/ext4/mballoc.c (ffffffff815f9355)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_next
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_start
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
```
```
In fs/jbd2/journal.c (ffffffff81658a45)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_open
```
```
In ipc/util.c (ffffffff816b0c3f)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In drivers/pci/proc.c (ffffffff8198cc65)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_lseek
```
```
In drivers/acpi/proc.c (ffffffff819eb779)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
```
```
In drivers/scsi/scsi_proc.c (ffffffff81c32839)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:proc_scsi_host_open
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
```
```
In net/core/neighbour.c (ffffffff81f046e5)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_show
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4694)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff82001165)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_seq_start
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff82005c86)
Location: include/linux/proc_fs.h:119
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_get_first
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
