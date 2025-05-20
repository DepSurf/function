# Function: <code>kstrndup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811abd00)
Location: mm/util.c:84
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/argv_split.c:argv_split
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff811abd00-ffffffff811abd58: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4780)
Location: mm/util.c:84
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/argv_split.c:argv_split
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
```
**Symbols:**

```
ffffffff811c4780-ffffffff811c47df: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4870)
Location: mm/util.c:84
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/argv_split.c:argv_split
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
```
**Symbols:**

```
ffffffff811d4870-ffffffff811d48cf: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd5d0)
Location: mm/util.c:89
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff811dd5d0-ffffffff811dd64c: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3050)
Location: mm/util.c:89
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff811f3050-ffffffff811f30cc: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214340)
Location: mm/util.c:89
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff81214340-ffffffff812143bc: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227210)
Location: mm/util.c:82
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff81227210-ffffffff8122728c: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:89
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_devices
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff812379ba-ffffffff812379c6: kstrndup.cold (STB_LOCAL)
ffffffff81236d10-ffffffff81236d86: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:96
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff81245c78-ffffffff81245c84: kstrndup.cold (STB_LOCAL)
ffffffff81244ed0-ffffffff81244f46: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:96
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:__ftrace_function_set_filter
  - kernel/trace/trace_probe.c:__parse_imm_string
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/argv_split.c:argv_split
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
```
**Symbols:**

```
ffffffff812739fb-ffffffff81273a07: kstrndup.cold (STB_LOCAL)
ffffffff81272b80-ffffffff81272bf6: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:97
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:__ftrace_function_set_filter
  - kernel/trace/trace_probe.c:__parse_imm_string
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/dynamic_debug.c:dynamic_debug_exec_queries
  - lib/argv_split.c:argv_split
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
```
**Symbols:**

```
ffffffff81be6ef7-ffffffff81be6f03: kstrndup.cold (STB_LOCAL)
ffffffff8127d230-ffffffff8127d2a6: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:97
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:__ftrace_function_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/dynamic_debug.c:dynamic_debug_exec_queries
  - lib/argv_split.c:argv_split
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
```
**Symbols:**

```
ffffffff81bd8c63-ffffffff81bd8c6f: kstrndup.cold (STB_LOCAL)
ffffffff812823c0-ffffffff81282432: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:97
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:__ftrace_function_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/dynamic_debug.c:dynamic_debug_exec_queries
  - lib/argv_split.c:argv_split
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
```
**Symbols:**

```
ffffffff81cbaa7a-ffffffff81cbaa86: kstrndup.cold (STB_LOCAL)
ffffffff812c0430-ffffffff812c04a2: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:98
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:__ftrace_function_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:__ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - lib/dynamic_debug.c:dynamic_debug_exec_queries
  - lib/argv_split.c:argv_split
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
```
**Symbols:**

```
ffffffff81e6c398-ffffffff81e6c3a4: kstrndup.cold (STB_LOCAL)
ffffffff8131cf10-ffffffff8131cf9b: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81390ff0)
Location: mm/util.c:98
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:__ext4_fill_super
  - security/smack/smack_access.c:smk_parse_smack
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:unpack_profile
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff81390ff0-ffffffff81391087: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3900)
Location: mm/util.c:99
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:__ftrace_function_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:__ext4_fill_super
  - security/smack/smack_access.c:smk_parse_smack
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:unpack_profile
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff813c3900-ffffffff813c39b6: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee4c0)
Location: mm/util.c:99
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:__ftrace_function_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:parse_apply_sb_mount_options
  - security/smack/smack_access.c:smk_parse_smack
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:unpack_profile
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff813ee4c0-ffffffff813ee576: kstrndup (STB_GLOBAL)
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
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d7ed8)
Location: mm/util.c:96
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/amba/bus.c:driver_override_store
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divs_clk_setup
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffff8000102d7ed8-ffff8000102d7f8c: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff31c)
Location: mm/util.c:96
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_probe.c:parse_probe_arg
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/amba/bus.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
c04ff31c-c04ff3ac: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c0000000003979a0)
Location: mm/util.c:96
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/of_helpers.c:pseries_of_derive_parent
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
c0000000003979a0-c000000000397a98: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2800)
Location: mm/util.c:96
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_devices
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffe0001f2800-ffffffe0001f286c: kstrndup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:96
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff8123e2c8-ffffffff8123e2d4: kstrndup.cold (STB_LOCAL)
ffffffff8123d520-ffffffff8123d596: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:96
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/hv/vmbus_drv.c:driver_override_store
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff812312c8-ffffffff812312d4: kstrndup.cold (STB_LOCAL)
ffffffff81230520-ffffffff81230596: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:96
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff8123c068-ffffffff8123c074: kstrndup.cold (STB_LOCAL)
ffffffff8123b2c0-ffffffff8123b336: kstrndup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
char *kstrndup(const char *s, size_t max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:96
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - mm/vmpressure.c:vmpressure_register_event
  - fs/ext4/super.c:ext4_fill_super
  - security/apparmor/policy_unpack.c:unpack_profile
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/platform.c:driver_override_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:driver_override_store
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/argv_split.c:argv_split
```
**Symbols:**

```
ffffffff8124b7c0-ffffffff8124b7cc: kstrndup.cold (STB_LOCAL)
ffffffff8124a9d0-ffffffff8124aa46: kstrndup (STB_GLOBAL)
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
