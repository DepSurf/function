# Function: <code>round_jiffies_relative</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810eb6f0)
Location: kernel/time/timer.c:283
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:setup_vmstat
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - net/core/dst.c:dst_gc_task
  - net/rfkill/core.c:rfkill_poll
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff810eb6f0-ffffffff810eb764: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f2420)
Location: kernel/time/timer.c:381
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - net/core/dst.c:dst_gc_task
  - net/core/dst.c:dst_gc_task
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff810f2420-ffffffff810f249f: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f95a0)
Location: kernel/time/timer.c:381
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - net/core/dst.c:dst_gc_task
  - net/core/dst.c:dst_gc_task
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff810f95a0-ffffffff810f961f: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fbac0)
Location: kernel/time/timer.c:384
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff810fbac0-ffffffff810fbb3f: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811063b0)
Location: kernel/time/timer.c:384
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff811063b0-ffffffff8110642f: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811119d0)
Location: kernel/time/timer.c:401
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff811119d0-ffffffff81111a55: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111d010)
Location: kernel/time/timer.c:400
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff8111d010-ffffffff8111d095: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81127c90)
Location: kernel/time/timer.c:400
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff81127c90-ffffffff81127d09: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81133c30)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff81133c30-ffffffff81133ca9: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81144d80)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:start_shepherd_timer
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_device.c:edac_device_workq_function
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff81144d80-ffffffff81144df8: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140e80)
Location: kernel/time/timer.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:start_shepherd_timer
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_device.c:edac_device_workq_function
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff81140e80-ffffffff81140ef8: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141830)
Location: kernel/time/timer.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_device.c:edac_device_workq_function
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff81141830-ffffffff811418a9: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81164cf0)
Location: kernel/time/timer.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_device.c:edac_device_workq_function
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff81164cf0-ffffffff81164d69: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199770)
Location: kernel/time/timer.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_device.c:edac_device_workq_function
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff81199770-ffffffff81199807: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d7da0)
Location: kernel/time/timer.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_device.c:edac_device_workq_function
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff811d7da0-ffffffff811d7e37: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec210)
Location: kernel/time/timer.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_device.c:edac_device_workq_function
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff811ec210-ffffffff811ec2a7: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81202240)
Location: kernel/time/timer.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_device.c:edac_device_workq_function
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff81202240-ffffffff812022db: round_jiffies_relative (STB_GLOBAL)
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
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019d868)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffff80001019d868-ffff80001019d90c: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e5fb4)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
c03e5fb4-c03e6030: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fbe50)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
c0000000001fbe50-c0000000001fbed8: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012ae1c)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffe00012ae1c-ffffffe00012ae84: round_jiffies_relative (STB_GLOBAL)
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
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c3e0)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff8112c3e0-ffffffff8112c459: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111ec50)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff8111ec50-ffffffff8111ecc9: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a100)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff8112a100-ffffffff8112a179: round_jiffies_relative (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136750)
Location: kernel/time/timer.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/check.c:check_corruption
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
**Symbols:**

```
ffffffff81136750-ffffffff811367cd: round_jiffies_relative (STB_GLOBAL)
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
