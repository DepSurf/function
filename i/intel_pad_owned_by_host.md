# Function: <code>intel_pad_owned_by_host</code>

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
bool intel_pad_owned_by_host(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d52f0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:173
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_usable
```
**Symbols:**

```
ffffffff814d52f0-ffffffff814d5387: intel_pad_owned_by_host (STB_LOCAL)
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
bool intel_pad_owned_by_host(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:144
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81632080-ffffffff81632180: intel_pad_owned_by_host (STB_LOCAL)
ffffffff81bf5950-ffffffff81bf5969: intel_pad_owned_by_host.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool intel_pad_owned_by_host(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:154
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81615c90-ffffffff81615d76: intel_pad_owned_by_host (STB_LOCAL)
ffffffff81be786e-ffffffff81be7888: intel_pad_owned_by_host.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool intel_pad_owned_by_host(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:154
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81684d40-ffffffff81684e26: intel_pad_owned_by_host (STB_LOCAL)
ffffffff81ce128c-ffffffff81ce12a6: intel_pad_owned_by_host.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool intel_pad_owned_by_host(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:154
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff817a1510-ffffffff817a160c: intel_pad_owned_by_host (STB_LOCAL)
ffffffff81ea7a5c-ffffffff81ea7a8a: intel_pad_owned_by_host.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool intel_pad_owned_by_host(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b8620)
Location: drivers/pinctrl/intel/pinctrl-intel.c:161
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff818b8620-ffffffff818b873e: intel_pad_owned_by_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool intel_pad_owned_by_host(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fb690)
Location: drivers/pinctrl/intel/pinctrl-intel.c:163
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff818fb690-ffffffff818fb7ae: intel_pad_owned_by_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool intel_pad_owned_by_host(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81942cc0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:164
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81942cc0-ffffffff81942dde: intel_pad_owned_by_host (STB_LOCAL)
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
