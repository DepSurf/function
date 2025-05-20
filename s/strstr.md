# Function: <code>strstr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1d90)
Location: lib/string.c:809
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - mm/memblock.c:early_memblock
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/quirks.c:nvenet_msi_disable
  - drivers/pci/quirks.c:nvenet_msi_disable
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_matches
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
```
**Symbols:**

```
ffffffff813f1d90-ffffffff813f1df2: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438730)
Location: lib/string.c:806
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - mm/memblock.c:early_memblock
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/quirks.c:nvenet_msi_disable
  - drivers/pci/quirks.c:nvenet_msi_disable
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81438730-ffffffff81438792: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455720)
Location: lib/string.c:806
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - mm/memblock.c:early_memblock
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/quirks.c:nvenet_msi_disable
  - drivers/pci/quirks.c:nvenet_msi_disable
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81455720-ffffffff81455782: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f7180)
Location: lib/string.c:832
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - mm/memblock.c:early_memblock
  - security/security.c:security_setprocattr
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff818f7180-ffffffff818f71ea: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197db80)
Location: lib/string.c:899
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff8197db80-ffffffff8197dbea: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819da070)
Location: lib/string.c:899
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff819da070-ffffffff819da0df: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a12290)
Location: lib/string.c:900
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81a12290-ffffffff81a122ff: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81710)
Location: lib/string.c:962
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81a81710-ffffffff81a81780: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab87e0)
Location: lib/string.c:943
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81ab87e0-ffffffff81ab8850: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3440)
Location: lib/string.c:1000
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__list_lookup_parent
  - security/apparmor/policy.c:__list_lookup_parent
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_change
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff815f3440-ffffffff815f34b0: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617af0)
Location: lib/string.c:996
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__list_lookup_parent
  - security/apparmor/policy.c:__list_lookup_parent
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_change
  - lib/dynamic_debug.c:ddebug_change
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81617af0-ffffffff81617b50: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fb150)
Location: lib/string.c:996
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_change
  - lib/dynamic_debug.c:ddebug_change
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff815fb150-ffffffff815fb1a7: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668a00)
Location: lib/string.c:1012
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_change
  - lib/dynamic_debug.c:ddebug_change
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81668a00-ffffffff81668a62: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81782160)
Location: lib/string.c:825
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_change
  - lib/dynamic_debug.c:ddebug_change
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81782160-ffffffff8178221d: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203efc0)
Location: lib/string.c:751
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_change
  - lib/dynamic_debug.c:ddebug_change
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff8203efc0-ffffffff8203f079: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bd430)
Location: lib/string.c:749
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:tr_needs_alloc_snapshot
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_user.c:user_event_set_print_fmt
  - kernel/trace/trace_events_user.c:user_field_format
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_change
  - lib/dynamic_debug.c:ddebug_change
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff820bd430-ffffffff820bd4e9: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff82197d30)
Location: lib/string.c:734
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:tr_needs_alloc_snapshot
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_user.c:user_event_set_print_fmt
  - kernel/trace/trace_events_user.c:user_field_format
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_learning_profile
  - lib/dynamic_debug.c:ddebug_change
  - lib/dynamic_debug.c:ddebug_change
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff82197d30-ffffffff82197de9: strstr (STB_GLOBAL)
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
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/libstub/string.c (ffff800011441440)
Location: drivers/firmware/efi/libstub/string.c:18
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
  - drivers/firmware/efi/libstub/arm-stub.c:efi_entry
  - drivers/firmware/efi/libstub/efi-stub-helper.c:handle_cmdline_files
  - drivers/firmware/efi/libstub/efi-stub-helper.c:handle_cmdline_files
  - drivers/firmware/efi/libstub/efi-stub-helper.c:efi_parse_options
  - drivers/firmware/efi/libstub/efi-stub-helper.c:efi_parse_options
  - drivers/firmware/efi/libstub/efi-stub-helper.c:efi_parse_options
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffff800010d92f80-ffff800010d93010: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f4bc)
Location: lib/string.c:943
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
  - sound/core/init.c:snd_component_add
  - sound/soc/soc-core.c:fmt_single_name
  - sound/soc/soc-dapm.c:snd_soc_dapm_link_dai_widgets
  - sound/soc/soc-ops.c:snd_soc_info_volsw
```
**Symbols:**

```
c0e8f4bc-c0e8f534: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6f80)
Location: lib/string.c:943
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/powerpc/kernel/udbg.c:register_early_udbg_console
  - arch/powerpc/kernel/rtas_pci.c:rtas_setup_phb
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_init
  - arch/powerpc/kernel/module_64.c:module_frob_arch_sections
  - arch/powerpc/kernel/legacy_serial.c:check_legacy_serial_console
  - arch/powerpc/mm/numa.c:early_numa
  - arch/powerpc/mm/numa.c:early_numa
  - arch/powerpc/mm/numa.c:early_numa
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/tty/hvc/hvc_vio.c:hvc_vio_init_early
```
**Symbols:**

```
c000000000ed6f80-c000000000ed7060: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bce28)
Location: lib/string.c:943
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffe0008bce28-ffffffe0008bcea2: strstr (STB_GLOBAL)
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
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57630)
Location: lib/string.c:943
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81a57630-ffffffff81a576a0: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14710)
Location: lib/string.c:943
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81a14710-ffffffff81a14780: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3a20)
Location: lib/string.c:943
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81ac3a20-ffffffff81ac3a90: strstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *strstr(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfef0)
Location: lib/string.c:943
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/common.c:print_cpu_info
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/resource.c:strict_iomem
  - kernel/resource.c:strict_iomem
  - kernel/trace/ftrace.c:ftrace_match
  - kernel/trace/trace.c:err_pos
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - mm/memblock.c:early_memblock
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_find_yesno
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/util.c:tomoyo_permstr
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbutils.c:acpi_db_match_argument
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/firmware/dmi_scan.c:dmi_name_in_vendors
  - drivers/firmware/dmi_scan.c:dmi_name_in_serial
  - drivers/firmware/dmi_scan.c:dmi_matches
```
**Symbols:**

```
ffffffff81acfef0-ffffffff81acff60: strstr (STB_GLOBAL)
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
