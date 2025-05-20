# Function: <code>sysfs_streq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1c80)
Location: lib/string.c:616
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/bus.c:match_name
  - drivers/base/bus.c:match_name
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
```
**Symbols:**

```
ffffffff813f1c80-ffffffff813f1ccf: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438620)
Location: lib/string.c:616
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/bus.c:match_name
  - drivers/base/bus.c:match_name
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff81438620-ffffffff8143866f: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455610)
Location: lib/string.c:616
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/bus.c:match_name
  - drivers/base/bus.c:match_name
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff81455610-ffffffff8145565f: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f7080)
Location: lib/string.c:616
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/bus.c:match_name
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff818f7080-ffffffff818f70cf: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197da80)
Location: lib/string.c:617
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/bus.c:match_name
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff8197da80-ffffffff8197dacf: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9f70)
Location: lib/string.c:617
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/bus.c:match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/base/memory.c:store_auto_online_blocks
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff819d9f70-ffffffff819d9fbe: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a12190)
Location: lib/string.c:618
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/bus.c:match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff81a12190-ffffffff81a121de: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81620)
Location: lib/string.c:660
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/bus.c:match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/nvdimm/dimm_devs.c:__security_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff81a81620-ffffffff81a81660: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab86f0)
Location: lib/string.c:662
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff81ab86f0-ffffffff81ab8730: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3330)
Location: lib/string.c:703
Inline: False
Direct callers:
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - lib/string.c:__sysfs_match_string
  - lib/string.c:__sysfs_match_string
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:state_store
  - drivers/base/memory.c:state_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
```
**Symbols:**

```
ffffffff815f3330-ffffffff815f3370: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff816179e0)
Location: lib/string.c:700
Inline: False
Direct callers:
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - lib/string.c:__sysfs_match_string
  - lib/string.c:__sysfs_match_string
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/base/core.c:device_match_name
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:state_store
  - drivers/base/memory.c:state_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff816179e0-ffffffff81617a20: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fb050)
Location: lib/string.c:700
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - lib/string.c:__sysfs_match_string
  - lib/string.c:__sysfs_match_string
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/base/core.c:device_match_name
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:state_store
  - drivers/base/memory.c:state_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_lpm_latch_mode_write
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_lpm_latch_mode_write
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff815fb050-ffffffff815fb090: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668900)
Location: lib/string.c:701
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - lib/string.c:__sysfs_match_string
  - lib/string.c:__sysfs_match_string
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/base/core.c:device_match_name
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:state_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff81668900-ffffffff81668940: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff816ebff0)
Location: lib/string_helpers.c:851
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - lib/string_helpers.c:__sysfs_match_string
  - lib/string_helpers.c:__sysfs_match_string
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/base/core.c:device_match_name
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:state_store
  - drivers/base/memory.c:mhp_online_type_from_str
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff816ebff0-ffffffff816ec08a: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff817dc7b0)
Location: lib/string_helpers.c:895
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - lib/string_helpers.c:__sysfs_match_string
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/base/core.c:device_match_name
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:state_store
  - drivers/base/memory.c:mhp_online_type_from_str
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff817dc7b0-ffffffff817dc84a: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8181bf00)
Location: lib/string_helpers.c:895
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - lib/string_helpers.c:__sysfs_match_string
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/base/core.c:device_match_name
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:state_store
  - drivers/base/memory.c:mhp_online_type_from_str
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff8181bf00-ffffffff8181bf9a: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81861cb0)
Location: lib/string_helpers.c:912
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - mm/memory_hotplug.c:set_memmap_mode
  - mm/memory_hotplug.c:set_memmap_mode
  - mm/ksm.c:advisor_mode_store
  - mm/ksm.c:advisor_mode_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - lib/string_helpers.c:__sysfs_match_string
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/pci/pci.c:reset_method_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/base/core.c:device_match_name
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:state_store
  - drivers/base/memory.c:mhp_online_type_from_str
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/gpu/drm/drm_sysfs.c:status_store
  - drivers/gpu/drm/drm_sysfs.c:status_store
  - drivers/gpu/drm/drm_sysfs.c:status_store
  - drivers/gpu/drm/drm_sysfs.c:status_store
  - drivers/gpu/drm/drm_debugfs.c:connector_write
  - drivers/gpu/drm/drm_debugfs.c:connector_write
  - drivers/gpu/drm/drm_debugfs.c:connector_write
  - drivers/gpu/drm/drm_debugfs.c:connector_write
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:coredump_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff81861cb0-ffffffff81861d4a: sysfs_streq (STB_GLOBAL)
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
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92b68)
Location: lib/string.c:662
Inline: False
Direct callers:
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - lib/string.c:__sysfs_match_string
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffff800010d92b68-ffff800010d92bd8: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f338)
Location: lib/string.c:662
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/usb/musb/musb_core.c:mode_store
  - drivers/usb/musb/musb_core.c:mode_store
  - drivers/usb/musb/musb_core.c:mode_store
  - drivers/usb/gadget/udc/core.c:soft_connect_store
  - drivers/usb/gadget/udc/core.c:soft_connect_store
  - drivers/usb/gadget/udc/core.c:srp_store
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
c0e8f338-c0e8f3c4: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6b50)
Location: lib/string.c:662
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
c000000000ed6b50-c000000000ed6be8: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcc68)
Location: lib/string.c:662
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffe0008bcc68-ffffffe0008bccc4: sysfs_streq (STB_GLOBAL)
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
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57540)
Location: lib/string.c:662
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/nvme/host/multipath.c:nvme_subsys_iopolicy_store
  - drivers/nvme/host/multipath.c:nvme_subsys_iopolicy_store
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff81a57540-ffffffff81a57580: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14620)
Location: lib/string.c:662
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/nvme/host/multipath.c:nvme_subsys_iopolicy_store
  - drivers/nvme/host/multipath.c:nvme_subsys_iopolicy_store
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff81a14620-ffffffff81a14660: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3930)
Location: lib/string.c:662
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff81ac3930-ffffffff81ac3970: sysfs_streq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool sysfs_streq(const char *s1, const char *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfe00)
Location: lib/string.c:662
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/base/core.c:device_match_name
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/base/memory.c:auto_online_blocks_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:dax_bus_match
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/scsi/scsi_sysfs.c:store_host_reset
  - drivers/watchdog/watchdog_pretimeout.c:find_governor_by_name
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - lib/string.c:__sysfs_match_string
```
**Symbols:**

```
ffffffff81acfe00-ffffffff81acfe40: sysfs_streq (STB_GLOBAL)
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
