# Function: <code>proc_mkdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f480)
Location: fs/proc/generic.c:458
Inline: False
Direct callers:
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:init_irq_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - fs/jbd2/journal.c:journal_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:pci_proc_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
```
**Symbols:**

```
ffffffff8127f480-ffffffff8127f497: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac4c0)
Location: fs/proc/generic.c:462
Inline: False
Direct callers:
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
```
**Symbols:**

```
ffffffff812ac4c0-ffffffff812ac4d7: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c1db0)
Location: fs/proc/generic.c:464
Inline: False
Direct callers:
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
```
**Symbols:**

```
ffffffff812c1db0-ffffffff812c1dc7: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812cf010)
Location: fs/proc/generic.c:447
Inline: False
Direct callers:
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
```
**Symbols:**

```
ffffffff812cf010-ffffffff812cf027: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3760)
Location: fs/proc/generic.c:449
Inline: False
Direct callers:
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
```
**Symbols:**

```
ffffffff812f3760-ffffffff812f3777: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320880)
Location: fs/proc/generic.c:488
Inline: False
Direct callers:
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff81320880-ffffffff81320897: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337980)
Location: fs/proc/generic.c:490
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff81337980-ffffffff81337997: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135fb00)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff8135fb00-ffffffff8135fb17: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377d60)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff81377d60-ffffffff81377d77: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0c20)
Location: fs/proc/generic.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/input/input.c:input_init
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff813c0c20-ffffffff813c0c95: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2a80)
Location: fs/proc/generic.c:520
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/input/input.c:input_init
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff813d2a80-ffffffff813d2af5: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9910)
Location: fs/proc/generic.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff813d9910-ffffffff813d9985: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142b040)
Location: fs/proc/generic.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff8142b040-ffffffff8142b0b5: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a46b0)
Location: fs/proc/generic.c:518
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff814a46b0-ffffffff814a4731: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539b50)
Location: fs/proc/generic.c:518
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff81539b50-ffffffff81539bd1: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571df0)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff81571df0-ffffffff81571e71: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa7a0)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff815aa7a0-ffffffff815aa821: proc_mkdir (STB_GLOBAL)
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
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443ba0)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffff800010443ba0-ffff800010443bdc: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608db4)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:proc_cpu_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - sound/core/info.c:snd_info_init
```
**Symbols:**

```
c0608db4-c0608ddc: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0000000005592e0)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - arch/powerpc/kernel/proc_powerpc.c:proc_ppc64_create
  - arch/powerpc/kernel/proc_powerpc.c:proc_ppc64_create
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
c0000000005592e0-c000000000559300: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da684)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffe0002da684-ffffffe0002da6ba: proc_mkdir (STB_GLOBAL)
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
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81370340)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff81370340-ffffffff81370357: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360dd0)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff81360dd0-ffffffff81360de7: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136de10)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff8136de10-ffffffff8136de27: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *proc_mkdir(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381740)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/root.c:proc_root_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_sysctl.c:proc_sys_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff81381740-ffffffff81381757: proc_mkdir (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
