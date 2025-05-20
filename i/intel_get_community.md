# Function: <code>intel_get_community</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct intel_community *intel_get_community(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5280)
Location: drivers/pinctrl/intel/pinctrl-intel.c:120
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
```
**Symbols:**

```
ffffffff814d5280-ffffffff814d52e3: intel_get_community (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81bf5985)
Location: drivers/pinctrl/intel/pinctrl-intel.c:91
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81be78a4)
Location: drivers/pinctrl/intel/pinctrl-intel.c:101
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81ce1357)
Location: drivers/pinctrl/intel/pinctrl-intel.c:101
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81ea7b2b)
Location: drivers/pinctrl/intel/pinctrl-intel.c:101
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b8fa3)
Location: drivers/pinctrl/intel/pinctrl-intel.c:108
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fc023)
Location: drivers/pinctrl/intel/pinctrl-intel.c:110
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set_pull
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set_pull
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct intel_community *intel_get_community(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81943d53)
Location: drivers/pinctrl/intel/pinctrl-intel.c:111
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff81941820-ffffffff819418ac: intel_get_community (STB_GLOBAL)
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
<b>Regular</b>
<ul>
</ul>
