# Function: <code>proc_create_single_data</code>

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
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320a90)
Location: fs/proc/generic.c:613
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/rtc-proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff81320a90-ffffffff81320ad8: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337b90)
Location: fs/proc/generic.c:615
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff81337b90-ffffffff81337bd8: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135fd00)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff8135fd00-ffffffff8135fd48: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377f60)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff81377f60-ffffffff81377fa8: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0e70)
Location: fs/proc/generic.c:629
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/bootconfig.c:proc_boot_config_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/connector/connector.c:cn_init
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff813c0e70-ffffffff813c0eb7: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2d60)
Location: fs/proc/generic.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/bootconfig.c:proc_boot_config_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/connector/connector.c:cn_init
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff813d2d60-ffffffff813d2da7: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9bf0)
Location: fs/proc/generic.c:644
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/bootconfig.c:proc_boot_config_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff813d9bf0-ffffffff813d9c37: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142b320)
Location: fs/proc/generic.c:644
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/bootconfig.c:proc_boot_config_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff8142b320-ffffffff8142b367: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a49e0)
Location: fs/proc/generic.c:647
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/bootconfig.c:proc_boot_config_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff814a49e0-ffffffff814a4a36: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539ee0)
Location: fs/proc/generic.c:647
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/bootconfig.c:proc_boot_config_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff81539ee0-ffffffff81539f36: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81572180)
Location: fs/proc/generic.c:646
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/bootconfig.c:proc_boot_config_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff81572180-ffffffff815721d6: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aab30)
Location: fs/proc/generic.c:646
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/bootconfig.c:proc_boot_config_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff815aab30-ffffffff815aab86: proc_create_single_data (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443e90)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffff800010443e90-ffff800010443f0c: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0609038)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - arch/arm/kernel/swp_emulate.c:swp_emulation_init
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/mtd/mtdcore.c:init_mtd
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
c0609038-c0609094: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0000000005595d0)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas-proc.c:proc_rtas_init
  - arch/powerpc/kernel/rtas-proc.c:proc_rtas_init
  - arch/powerpc/kernel/eeh.c:eeh_init_proc
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
c0000000005595d0-c000000000559640: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da8c8)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffe0002da8c8-ffffffe0002da932: proc_create_single_data (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81370540)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff81370540-ffffffff81370588: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360fd0)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff81360fd0-ffffffff81361018: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136e010)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff8136e010-ffffffff8136e058: proc_create_single_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_single_data(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381940)
Location: fs/proc/generic.c:616
Inline: False
Direct callers:
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/dma.c:proc_dma_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/rtc/proc.c:rtc_proc_add_device
  - net/sched/sch_api.c:psched_net_init
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff81381940-ffffffff81381988: proc_create_single_data (STB_GLOBAL)
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
