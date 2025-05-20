# Function: <code>match_string</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438670)
Location: lib/string.c:642
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/power/charger-manager.c:cm_notify_event
```
**Symbols:**

```
ffffffff81438670-ffffffff814386bb: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455660)
Location: lib/string.c:642
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/power/supply/charger-manager.c:cm_notify_event
```
**Symbols:**

```
ffffffff81455660-ffffffff814556ab: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f70d0)
Location: lib/string.c:642
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff818f70d0-ffffffff818f7120: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197dad0)
Location: lib/string.c:643
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff8197dad0-ffffffff8197db20: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9fc0)
Location: lib/string.c:643
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff819d9fc0-ffffffff819da002: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a121e0)
Location: lib/string.c:644
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81a121e0-ffffffff81a12222: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81660)
Location: lib/string.c:686
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81a81660-ffffffff81a8169f: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8730)
Location: lib/string.c:688
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81ab8730-ffffffff81ab876f: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3370)
Location: lib/string.c:737
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:parse_resource
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff815f3370-ffffffff815f33b7: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617a20)
Location: lib/string.c:734
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:parse_resource
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81617a20-ffffffff81617a67: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fb090)
Location: lib/string.c:734
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff815fb090-ffffffff815fb0cf: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668940)
Location: lib/string.c:735
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81668940-ffffffff8166897f: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff816ecaa0)
Location: lib/string_helpers.c:885
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/verity/measure.c:fsverity_get_digest
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/acpi/scan.c:acpi_info_matches_ids
  - drivers/acpi/scan.c:acpi_info_matches_ids
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff816ecaa0-ffffffff816ecafa: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff817dd340)
Location: lib/string_helpers.c:929
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/acpi/scan.c:acpi_info_matches_ids
  - drivers/acpi/scan.c:acpi_info_matches_ids
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff817dd340-ffffffff817dd39a: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8181cb50)
Location: lib/string_helpers.c:929
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/cgroup/rdma.c:parse_resource
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/acpi/scan.c:acpi_info_matches_ids
  - drivers/acpi/scan.c:acpi_info_matches_ids
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/amd-pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8181cb50-ffffffff8181cbaa: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81862960)
Location: lib/string_helpers.c:946
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/cgroup/rdma.c:parse_resource
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/acpi/scan.c:acpi_info_matches_ids
  - drivers/acpi/scan.c:acpi_info_matches_ids
  - drivers/base/property.c:fwnode_property_match_property_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/amd-pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81862960-ffffffff818629ba: match_string (STB_GLOBAL)
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
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92e08)
Location: lib/string.c:688
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pmx_set_by_name
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_clock
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_branches
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffff800010d92e08-ffff800010d92e8c: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f3c4)
Location: lib/string.c:688
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_branches
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - sound/soc/soc-dapm.c:dapm_connect_mux
```
**Symbols:**

```
c0e8f3c4-c0e8f420: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6bf0)
Location: lib/string.c:688
Inline: False
Direct callers:
  - arch/powerpc/xmon/xmon.c:scanhex
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
c000000000ed6bf0-c000000000ed6c54: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bccc4)
Location: lib/string.c:688
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffe0008bccc4-ffffffe0008bcd00: match_string (STB_GLOBAL)
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
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57580)
Location: lib/string.c:688
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81a57580-ffffffff81a575bf: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14660)
Location: lib/string.c:688
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81a14660-ffffffff81a1469f: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3970)
Location: lib/string.c:688
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81ac3970-ffffffff81ac39af: match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int match_string(const const char * *array, size_t n, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfe40)
Location: lib/string.c:688
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_set_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/integrity/ima/ima_main.c:hash_setup
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81acfe40-ffffffff81acfe7f: match_string (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
