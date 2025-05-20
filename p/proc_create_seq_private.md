# Function: <code>proc_create_seq_private</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320a30)
Location: fs/proc/generic.c:583
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff81320a30-ffffffff81320a83: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337b30)
Location: fs/proc/generic.c:585
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff81337b30-ffffffff81337b83: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135fca0)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff8135fca0-ffffffff8135fcf2: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377f00)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff81377f00-ffffffff81377f52: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0e10)
Location: fs/proc/generic.c:598
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff813c0e10-ffffffff813c0e62: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2d00)
Location: fs/proc/generic.c:618
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff813d2d00-ffffffff813d2d52: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9b90)
Location: fs/proc/generic.c:613
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
```
**Symbols:**

```
ffffffff813d9b90-ffffffff813d9be2: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142b2c0)
Location: fs/proc/generic.c:613
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
```
**Symbols:**

```
ffffffff8142b2c0-ffffffff8142b312: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4970)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/build_utility.c:proc_schedstat_init
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
```
**Symbols:**

```
ffffffff814a4970-ffffffff814a49d4: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539e60)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/build_utility.c:proc_schedstat_init
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
```
**Symbols:**

```
ffffffff81539e60-ffffffff81539ec4: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81572100)
Location: fs/proc/generic.c:615
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/build_utility.c:proc_schedstat_init
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
```
**Symbols:**

```
ffffffff81572100-ffffffff81572164: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aaab0)
Location: fs/proc/generic.c:615
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/build_utility.c:proc_schedstat_init
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fb_procfs.c:fb_init_procfs
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
```
**Symbols:**

```
ffffffff815aaab0-ffffffff815aab14: proc_create_seq_private (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443e00)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffff800010443e00-ffff800010443e8c: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608fd8)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
c0608fd8-c0609038: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000559550)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
c000000000559550-c0000000005595d0: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da854)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffe0002da854-ffffffe0002da8c8: proc_create_seq_private (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813704e0)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff813704e0-ffffffff81370532: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360f70)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff81360f70-ffffffff81360fc2: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136dfb0)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff8136dfb0-ffffffff8136e002: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_seq_private(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813818e0)
Location: fs/proc/generic.c:586
Inline: False
Direct callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/time/timer_list.c:init_timer_list_procfs
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmalloc.c:proc_vmalloc_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_proc_net_init
```
**Symbols:**

```
ffffffff813818e0-ffffffff81381932: proc_create_seq_private (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
