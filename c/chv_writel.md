# Function: <code>chv_writel</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148d640)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:697
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81496fe0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:703
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d3300)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:696
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815043b0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:696
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81518ed0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:676
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81547069)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:676
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81567f89)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:678
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160bd59)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:613
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816304a6)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:601
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81614147)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:601
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816832c7)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:601
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179f4be)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:603
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_intr_line
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b619e)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:605
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f925e)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:605
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8194062e)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:606
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
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
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154e599)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:678
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155c2b9)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:678
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81576149)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:678
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_mmio_access_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set_oden
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux
```
</details>
</li>
</ul>

## Differences
