# Function: <code>class_raw_spinlock_irqsave_constructor</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811581bf)
Location: include/linux/spinlock.h:553
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:try_to_wake_up
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193d3ba)
Location: include/linux/spinlock.h:553
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8194054f)
Location: include/linux/spinlock.h:553
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81942fa9)
Location: include/linux/spinlock.h:553
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
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
