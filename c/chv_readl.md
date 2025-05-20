# Function: <code>chv_readl</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816305cb)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:596
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8161426c)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:596
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816833ec)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:596
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179f607)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:598
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_intr_line
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b62e7)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:600
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f93a7)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:600
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81940777)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:601
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show
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
