# Function: <code>byt_gpio_reg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81422a56)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:152
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146b190)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:730
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux
```
**Symbols:**

```
ffffffff8146b190-ffffffff8146b227: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148b570)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:730
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux
```
**Symbols:**

```
ffffffff8148b570-ffffffff8148b613: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81494ea0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:730
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux
```
**Symbols:**

```
ffffffff81494ea0-ffffffff81494f43: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d11a0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:733
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux
```
**Symbols:**

```
ffffffff814d11a0-ffffffff814d1243: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81502250)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:733
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux
```
**Symbols:**

```
ffffffff81502250-ffffffff815022fd: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81516d50)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:726
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux
```
**Symbols:**

```
ffffffff81516d50-ffffffff81516e01: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81544fb0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:586
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff81544fb0-ffffffff8154504c: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81565e90)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:568
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff81565e90-ffffffff81565f38: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81608bd0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:558
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff81608bd0-ffffffff81608c73: byt_gpio_reg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162d2f0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:558
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff8162d2f0-ffffffff8162d390: byt_gpio_reg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81610f70)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:558
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff81610f70-ffffffff8161100a: byt_gpio_reg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff816800a0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:558
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
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
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff816800a0-ffffffff8168013a: byt_gpio_reg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179bee0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:569
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
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
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff8179bee0-ffffffff8179bfab: byt_gpio_reg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b2840)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:569
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
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
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff818b2840-ffffffff818b290b: byt_gpio_reg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f5890)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:569
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
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
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff818f5890-ffffffff818f595b: byt_gpio_reg.isra.0 (STB_LOCAL)
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
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193d3f7)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:556
Inline: True
Inline callers:
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155d360)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:568
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff8155d360-ffffffff8155d408: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154c4a0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:568
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff8154c4a0-ffffffff8154c548: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155a1c0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:568
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff8155a1c0-ffffffff8155a268: byt_gpio_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *byt_gpio_reg(struct byt_gpio *vg, unsigned int offset, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81574050)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:568
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux
```
**Symbols:**

```
ffffffff81574050-ffffffff815740f8: byt_gpio_reg (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
