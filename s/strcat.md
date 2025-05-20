# Function: <code>strcat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strcat(char *dest, const char *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1910)
Location: lib/string.c:245
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff813f1910-ffffffff813f193d: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strcat(char *dest, const char *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814382d0)
Location: lib/string.c:245
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff814382d0-ffffffff814382fd: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strcat(char *dest, const char *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814552c0)
Location: lib/string.c:245
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff814552c0-ffffffff814552ed: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104be45)
Location: include/linux/string.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:show_trigger
  - kernel/params.c:param_attr_show
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff818f6960-ffffffff818f698d: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104f885)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff8197d360-ffffffff8197d38d: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8105259d)
Location: include/linux/string.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff819d98b0-ffffffff819d98d9: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8104fbfd)
Location: include/linux/string.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81a11ad0-ffffffff81a11af9: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81052d56)
Location: include/linux/string.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81a81030-ffffffff81a81059: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053646)
Location: include/linux/string.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81ab8230-ffffffff81ab8259: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058636)
Location: include/linux/string.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
```
**Symbols:**

```
ffffffff815f2e50-ffffffff815f2e79: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81057436)
Location: include/linux/string.h:304
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
```
**Symbols:**

```
ffffffff81617500-ffffffff81617529: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81057d7a)
Location: include/linux/fortify-string.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
```
**Symbols:**

```
ffffffff815fab80-ffffffff815faba9: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81060c4a)
Location: include/linux/fortify-string.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
```
**Symbols:**

```
ffffffff81668420-ffffffff81668449: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
char *strcat(const char * p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106d4f7)
Location: include/linux/fortify-string.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
```
**Symbols:**

```
ffffffff81781c90-ffffffff81781cc8: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
char *strcat(const char * p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107d686)
Location: include/linux/fortify-string.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
```
**Symbols:**

```
ffffffff8203e9f0-ffffffff8203ea28: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
char *strcat(const char * p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107f996)
Location: include/linux/fortify-string.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
```
**Symbols:**

```
ffffffff820bcef0-ffffffff820bcf28: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
char *strcat(const char * p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810874a6)
Location: include/linux/fortify-string.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - kernel/trace/trace_events_hist.c:hist_field_name
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
```
**Symbols:**

```
ffffffff821977f0-ffffffff82197828: strcat (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffff800010239910)
Location: include/linux/string.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/clk/zynqmp/clkc.c:zynqmp_register_clocks
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffff800010d92758-ffff800010d9278c: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c04750c0)
Location: include/linux/string.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:get_defined_attribute
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:get_defined_attribute
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/musb/musb_core.c:musb_core_init
  - drivers/usb/musb/musb_core.c:musb_core_init
  - drivers/usb/musb/musb_core.c:musb_core_init
  - drivers/usb/musb/musb_core.c:musb_core_init
  - drivers/usb/musb/musb_core.c:musb_core_init
  - drivers/usb/musb/musb_core.c:musb_core_init
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - sound/sound_core.c:register_sound_special_device
  - sound/core/init.c:snd_component_add
  - sound/core/init.c:snd_component_add
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
c0e8ecfc-c0e8ed3c: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002c76f0)
Location: include/linux/string.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
c000000000ed6400-c000000000ed6454: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strcat(char *dest, const char *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bc99c)
Location: lib/string.c:282
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffe0008bc99c-ffffffe0008bc9d8: strcat (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053316)
Location: include/linux/string.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81a57080-ffffffff81a570a9: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81043296)
Location: include/linux/string.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/ip_tunnel.c:__ip_tunnel_create
```
**Symbols:**

```
ffffffff81a14160-ffffffff81a14189: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810535f6)
Location: include/linux/string.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81ac3470-ffffffff81ac3499: strcat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *strcat(char *p, const char *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81054ab6)
Location: include/linux/string.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
  - drivers/base/memory.c:print_allowed_zone
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/md/dm-sysfs.c:dm_attr_uuid_show
  - drivers/md/dm-sysfs.c:dm_attr_name_show
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81acf940-ffffffff81acf969: strcat (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *p</code>
</li>
<li>
<b>Param added. </b>
<code>const char *q</code>
</li>
<li>
<b>Param removed. </b>
<code>char *dest</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *src</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *p</code> ➡️ <code>const char * p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *dest</code>
</li>
<li>
<b>Param added. </b>
<code>const char *src</code>
</li>
<li>
<b>Param removed. </b>
<code>char *p</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *q</code>
</li>
</ul>
</details>
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
