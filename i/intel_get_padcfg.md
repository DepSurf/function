# Function: <code>intel_get_padcfg</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void *intel_get_padcfg(struct intel_pinctrl *pctrl, unsigned int pin, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5470)
Location: drivers/pinctrl/intel/pinctrl-intel.c:153
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff814d5470-ffffffff814d54c4: intel_get_padcfg (STB_LOCAL)
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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *intel_get_padcfg(struct intel_pinctrl *pctrl, unsigned int pin, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:124
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81631b00-ffffffff81631b9f: intel_get_padcfg (STB_LOCAL)
ffffffff81bf5901-ffffffff81bf591a: intel_get_padcfg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *intel_get_padcfg(struct intel_pinctrl *pctrl, unsigned int pin, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:134
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81615720-ffffffff816157bf: intel_get_padcfg (STB_LOCAL)
ffffffff81be781f-ffffffff81be7838: intel_get_padcfg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *intel_get_padcfg(struct intel_pinctrl *pctrl, unsigned int pin, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:134
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff816849e0-ffffffff81684a7f: intel_get_padcfg (STB_LOCAL)
ffffffff81ce1273-ffffffff81ce128c: intel_get_padcfg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *intel_get_padcfg(struct intel_pinctrl *pctrl, unsigned int pin, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:134
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff817a1120-ffffffff817a11d1: intel_get_padcfg (STB_LOCAL)
ffffffff81ea7a44-ffffffff81ea7a5c: intel_get_padcfg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *intel_get_padcfg(struct intel_pinctrl *pctrl, unsigned int pin, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b81a0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:141
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff818b81a0-ffffffff818b8273: intel_get_padcfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *intel_get_padcfg(struct intel_pinctrl *pctrl, unsigned int pin, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fb210)
Location: drivers/pinctrl/intel/pinctrl-intel.c:143
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set_pull
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff818fb210-ffffffff818fb2e3: intel_get_padcfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *intel_get_padcfg(struct intel_pinctrl *pctrl, unsigned int pin, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81942840)
Location: drivers/pinctrl/intel/pinctrl-intel.c:144
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81942840-ffffffff81942913: intel_get_padcfg (STB_LOCAL)
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
